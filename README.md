# Задание 1

|**№ п/п**|**Критерий**|**Комментарий**|**Оценка**|**Обоснование оценки**|
|---------|------------|---------------|----------|----------------------|
|1|**Орфография и пунктуация**|Если в тексте много ошибок, понять его будет сложно — конечная цель не будет достигнута, инструкцию читать не будут.  Инструкции, написанные грамотно, демонстрируют уважение к читателю и общий уровень компании. Несколько пунктуационных ошибок, скорее всего, не повлияют на восприятие информации|4|Грубых ошибок не нашла. Есть ошибки в пунктуации в описании ПО|
|2|**Согласование слов в предложении**|Затрудняет восприятие информации. Если часто будет нарушено, то инструкцию до конца не дочитают|4|Есть вопросы к описанию к ПО и  обзору возможностей в **Руководстве по  системному администрированию**|
|3|**Единый стиль оформления**|Улучшает восприятие информации. Возможно, способствует укреплению имиджа компании: хорошая документация — хорошая компания; плохая документация — и ПО “из костылей”|4|Заметила разный подход к оформлению скриншотов, наименований вкладок, полей|
|4|**Описание процедур в повелительном наклонении**|Опять же улучшает восприятие информации, в некотором смысле best practices для документации|3|Часто встречаются конструкции “необходимо + глагол”, которые можно заменить на глагол в повелительном наклонении. Есть неодназначные формулировки.  Пример: “Все остальные поля оставьте без изменений и создайте пользователя”.  Что подразумевается под действием “создайте пользователя”? Вероятно, нужно явно написать “Нажмите кнопку Создать”|
|5|**Лаконичность изложения**|Длинные предложения, тавтологии и слова, загромождающие текст, усложняют восприятие информации|3|Примеры:<ol><li>“На странице создания ~~нового~~ пользователя”.</li><li>“Которая установит ~~все~~ необходимые зависимости”.</li><li>“Чтобы увидеть правило, ~~выполните действия:~~”</li></ol>|
|6|**Структурированность информации**|Опять же улучшает восприятие информации, сокращает время на изучение документации|4|Руководство по системному администрированию я бы оценила на 3, так как в обзоре всего instance информация плохо структурирована. Руководство оператора на 4. Информация о рекомендованных браузерах приведена после описания способов авторизации. На мой взгляд, логично сначала написать про браузеры, а затем про авторизацию. Остальные — на 5|
|7|**Дублирование информации**|Возможно, оправдано, когда мы предупреждаем о критических действиях. В иных случаях я бы избегала повторов|4|Пример: в **Руководстве по системному администрированию** дважды встречается предложение “Подробная ролевая модель описана в разделе Авторизация Руководства по безопасности .”|
|8|**Полнота**|Ссылки на другие источники там, где необходимо, чтобы читателю не пришлось догадываться и додумывать|5|Не нашла мест, которые хотелось бы дополнить отсылкой к другим источникам|
|9|**Актуальность ссылок**||5|Не нашла неработающие ссылки|

_*Выделила бы такие критерии, как **Фактологическая точность**, **Соответствие ЦА**, **Соответствие стайлгайду**, но дать полноценную оценку по этим критериям не могу._

**Общая оценка: 4-.**  На мой взгляд, вес каждого из перечисленных критериев в общей оценке отличается.

# Задание 2
1. Проверьте орфографию и пунктуацию, согласование слов в предложении. Избавьтесь от тавтологий.
1. Приведите к единому стилю оформление скриншотов: 
   * На всех скриншотах выделяйте элементы одним цветом. В инструкции есть скриншоты без выделения элементов, с выделением сиреневым цветом, выделением красным цветом.
   * Либо используйте нумерацию для полей (поле 0, поле 1), либо откажитесь от нее и используйте наименования полей (на мой взгляд, предпочтительнее).
1. Приведите к единому стилю оформление наименований вкладок.
1. Приведите к единому стилю оформление наименований полей и их значений.
1. Добавьте визуальное выделение элементов текста, которые требуют особого внимания читателя. Например, в **Руководстве оператора** “Рекомендуется выполнять процедуру периодической смены своего пароля”.
1. Откажитесь от использования слов "необходимо", “нужно” в тех случаях, когда текст можно трансформировать в конструкцию с глаголом повелительного наклонения. 
1. В **Руководстве по системному администрированию** проанализируйте и улучшите структуру раздела “Обзор всего instanсe”.
1. В **Руководстве по установке** уберите слово “команда” из предложений вида “выполните что-то с помощью команды”. 
1. Проанализируйте, везде ли содержимое раздела соответствует заголовку. Если нет — переформулируйте. 

_* Можно рекомендовать пересмотреть размер скриншотов. Предполагаю, что стайлгайд обязывает делать их на всю страницу по ширине, но в **Руководстве оператора** скриншот **Reviewers** занимает, на мой взгляд, неоправданно много места по вертикали._

# Задание 3
_* Не возьмусь править инструкции полностью, но попробую предложить вариант для той части, которая структурирована, на мой взгляд, хуже всего._

## Руководство по системному администрированию**

### Обзор инструментов управления instance
Инструменты управления instance логически объединены по страницам в зависимости от типов сущностей. Ниже приведено название страниц области администрирования (Admin area) и список действий, доступных на них:
1. На странице **Dashboard** можно просмотреть отчеты по состоянию: общую статистику по количеству проектов, групп, компонентов, запущенных runners, активных features.
1. На странице **Projects** можно:
   * просмотреть список всех проектов;
   * удалить проект — кнопка **Delete**;
   * отредактировать проект — кнопка **Edit**;
   * создать новый проект — кнопка **New Project**.
1. На странице **Users** можно:
   * просмотреть список всех пользователей instance;
   * заблокировать пользователя —  кнопка **Delete User**;
   * удалить с историей действий — кнопка **Delete with contributions**;
   * отредактировать параметры пользователя: имя, почта, пароль, уровень доступа, ссылки на социальные сети;
   * создать пользователя — кнопка **New user**.
1. ...

## Руководство по установке

### Аппаратные требования
#### Вариант 1
Комплект технических средств (КТС) должен соответствовать следующим минимальным характеристикам:
* Сервер приложений (включая Nginx):
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.
* БД:
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.
* REDIS:
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.

#### Вариант 2
Требования к минимальной конфигурации:
* Сервер приложений (включая Nginx):
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.
* БД:
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.
* REDIS:
  * ЦПУ 4 ядра;
  * ОЗУ 8Gb;
  * HDD 100Gb;
  * наличие сетевой карты.

_* Можно представить в виде таблицы._

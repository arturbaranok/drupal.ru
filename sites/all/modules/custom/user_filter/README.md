# Модуль User Filter для Drupal 7
[Репозиторий модуля](https://github.com/awd-studio/user_filter)
_________________________________

## Модуль User Filter

Добавляет фильтр, позволяющий выводить информацию о пользователе сайта, записав его в формате "@username".

Необходимо включить фильтр для необходимых форматов на странице *"admin/config/content/formats"*.
_________________________________

## Модуль User Filter Notify

Позволяет отправлять пользователям уведомления об упоминании их другими пользователями, путем указания "@username" в комментариях или нодах.

Поддерживает токены.
Добавляет новый вид токенов *"Author"*, позволяющий выводить информацию об авторе содержимого и *"Text"*, позволяющий вывести текст в котором пользователь был упомянут.

Включить и настроить уведомление можно настранице *"admin/config/people/accounts"*.
_________________________________

## Модуль User Filter PopUp

Позволяет выводить информацию об упомянутом пользователе во всплывающем окне.

Добавляет новый View Mode - "User Info", для пользователя, информация из которого и выводится. 

Настроить информацию выводимую во всплывающем окне можно на странице *"admin/config/people/accounts/display/user_info"*.

Так же можно задать свой шаблон отображения поместив в папку с темой файл, с именем *user-profile--user_info.tpl.php* и сбросив кеш.

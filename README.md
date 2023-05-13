# Project for optimization routine process

### Parser for extraction data of certifications for personnel from inside site company (dec 2021)

#### Версия 2.0

Дает возможность добавлять и удалять сотрудников через графический интерфейc, так же выбирать чьи данные выгружать

Работает при наличии в папке файлов:
sb_user.txt, rs_user.txt - список сотрудников;
certifications.txt - список сертификаций.

#### Версия 1.0

Работает при наличии в папке файлов:
bom_user_full.txt - список сотрудников;
certifications.txt - список сертификаций.

При изменении файлов необходимо соблюдать исходное форматирование:
bom_user_full - между GIN и именем должна быть ': ', имя должно соответствовать с Quest;
certifications - заполняется через перенос строки.

BUGS:
Выдает ошибку, если неправильный GIN или сотрудника нет в системе - ИСПРАВЛЕНО (все сертификации помечаются N/A);
Если перепаутан GIN у сотрудников, выгружал данные другого сотрудника - ИСПРАВЛЕНО (все сертификации помечаются N/A).

### Screen

![alt text](https://github.com/Frvzr/slb_parser/blob/main/screens/1.JPG)

# Домашнее задание по десятому семинару 
## Дата 22.12.2022 (четверг)
### [работа с bootstrap](https://olegsamy.github.io/10DZ_boostrap) 

Текст задания 
1.	Необходимо сделать гамбургер меню из первого задания
2.	Поменять контент меню, чтобы в нем были 3 ссылки меню (Главная, Каталог, Контакты)
3.	Сделать так чтобы гамбургер меню появлялся уже на планшетной версиии проекта
4.	На мобильной версии при открытии гамбургер меню, элементы должны располагаться вертикально 
# Решение
1. переименовываем ссылки
2. скрываем лишние пункты меню классом - visually-hidden
3. допустим планшетная версия начинается в контрольной точке < 768px md - navbar-expand-md 
4. мобильная версия < 576px sm - flex-sm-column

# Дилемма мастера зелий

## Цель
Разработать многопоточную программу на C++, которая решает уникальную переосмысленную
проблему, известную как "Дилемма мастеров зелий".
## Предыстория
"The Potion Masters' Dilemma" - это вариация проблемы синхронизации, в которой участвуют три
потока, которым необходимо синхронизировать доступ к общим ресурсам.
## Дилемма мастеров зелий
Есть три мастера зелий, у которых неполный набор ингредиентов. У каждого из них есть
неограниченный запас одного из трех ингредиентов: волос единорога, перо феникса или чешуя
дракона. Существует также магическое существо, у которого есть неограниченный запас всех трех
ингредиентов. Магическое существо кладет два случайных ингредиента на общий стол. Мастер
зелий, у которого есть оставшийся ингредиент, готовит волшебное зелье, используя свой
ингредиент и два ингредиента со стола. Это продолжается бесконечно.
## Описание задания
Создайте программу на C++, используя принципы объектно-ориентированного
программирования, которая имитирует поведение мастеров зелий и волшебного существа.
## Класс мастера зелий
Класс мастера зелий должен включать в себя:
- ID или имя для идентификации мастера зелий.
- Метод, имитирующий процесс приготовления волшебного зелья (это может быть простая
задержка).
## Класс магических существ
Класс "Магическое существо" должен включать в себя:
- Метод, который помещает два случайных ингредиента на стол (здесь также может быть
использована задержка).
## Главная программа
Основная программа должна создавать экземпляры класса "Мастер зелий" и класса "Магическое
существо". Она должна имитировать поведение Мастера зелий и магического существа,
гарантируя, что правильный Мастер зелий приготовит зелье, когда соответствующие ингредиенты
окажутся на столе.


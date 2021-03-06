# Lab 4
# Створення GUI з допомогою Matisse 
[![Gitter](https://badges.gitter.im/PPC-SE-2020/OOP.svg)](https://gitter.im/PPC-SE-2020/OOP?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Мета роботи - навчитись створювати прості графічні інтерфейси з допомогою Netbeans Swing GUI Builder( [Matisse](https://netbeans.org/features/java/swing.html)). 

![Demo](https://github.com/liketaurus/TUI-Labs/blob/master/Lab%204%20-%20Matisse/GUI-Lab-4.PNG)

Допоміжні матеріали: 
- [Скрінкасти](https://netbeans.org/kb/docs/java/gui-builder-screencast.htmll) 
- [Навчальні матеріали](https://netbeans.org/kb/docs/java/gui-functionality.html)
- [Репозиторій](https://github.com/liketaurus/OOP-JAVA) з классами з усіх попередніх лаб (завдання 'Banking')

Ви можете обрати завдання на бажану оцінку - три, чотири або п'ять. *УВАГА! Завдання "на чотири" та "на п'ять" потребують виконання завдання "на три"!* 

## На "трійку" 
1. Завантажте jar-файл з усіма потрібними классами (*Bank, Customer, Account* та ін.) з наших попередніх лаб - [MyBank](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/jars/MyBank.jar) 
2. Створіть в Netbeans новий проект з назвою MatisseDemo (або використайте проект, створений в ході виконання попередньої роботи). *УВАГА! Чекбокс *Create Main Class* треба **очистити** (**не створювати виконуваний клас**)!* 
3. Додайте до проекту завантажену вами бібліотеку - правою кнопкой на проекті, обрати *Properties*, потім у дереві категорій обрати *Libraries* (другий пункт зверху), натиснути у правій частині вікна кнопку *Add JAR/Folder*, обрати jar-файл, завантажений у п. 1, натиснути *Ok* 
4. Додайте до проекту нову форму JFrame. З допомогою Matisse створіть інтерфейс, [прототип](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/Lab%204%20-%20Matisse/GUI-Lab-4.PNG) якого ви бачили на початку цього завдання. *УВАГА! Форма має або масштабуватись у зручний спосіб, або зміну її розмірів слід заборонити (властивість **Resizeable**)!*
5. Вивчіть автоматично згенерований код у файлі, впевніться, що ви розумієте як він має працювати 
6. Запустіть проект у звичайний спосіб. Ви маєте побачити вікно, ідентичне до прототипу. Продемонстрируйте результат викладачеві. 

## На "чотири"
1. Доповніть код таким чином, щоб з файлу **test.dat** (робота номер 8, [файл даних](https://github.com/ppc-ntu-khpi/GUI-Lab2-Starter/blob/master/data/test.dat) також є в цьому ж репозиторію) читалась інформація про клієнтів банку та їх рахунки 
2. Напишіть обробники подій для елементів керування, завдяки яким би при виборі клієнта та натисненні кнопки **Show** виводилась інформація про нього та всі його рахунки
3. Кнопка **About** має демонструвати діалогове вікно з інформацією про програму та її розробників (**[JOptionPane](https://docs.oracle.com/javase/7/docs/api/javax/swing/JOptionPane.html)**)
3. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві.

## На "п'ять"
1. Кнопка **Report** має виводити у нижній частині вікна звіт за клієнтами такого ж виду, як у роботі номер 8 (див. CustomerReport).
2. Запустіть проект, впевніться, що все працює як очікувалось. Продемонстрируйте результат викладачеві. 

**УВАГА! Не забудьте завантажити результат виконання роботи до вашого власного репозиторію - в проекті 'Banking' цей класс має бути в пакеті com.mybank.gui!**

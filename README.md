![Временной ряд](https://github.com/JoWiry/Time_Series_project/assets/71900299/81e5bbcc-2691-4fba-bfd0-ee3f2e89a3b9)
## 1. Постановка задачи

Перед нами стоит задача проанализировать ВВП африканской страны Гана. Для этого нам предоставили показатели ВВП Ганы за 62 года. 
Нам предстоит исследовать временной ряд, изучить его свойства, построить модели и сделать выводы по результатам.

**Основные цели проекта:**

1. Сделали декомпозицию и выявили наличие тренда и сезонности.

2. Разделили исходный набор данных на тренировочную и тестовую выборки и на основе тренировочных данных сделали вывод о наличии тренда.
3. Построена модель скользящего среднего, подобрали размер окна.
4. Провести тест на стационарность, и на основе его результатов выбрали лучшую модель - ARIMA .
5. Найти и заполнить пропущенные значения с помощью метода interpolate(), в результате немного улучшили показатели.
6. Расчитать волатильности с использованием моделей GARCH и линейной регрессии, сделать выводы
7. Построить модель Prophet

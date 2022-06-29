## Исследование модуля Matplotlib, создание документа с помощью Markdown

Matplotlib — библиотека на языке программирования Python для визуализации данных двумерной (2D) графикой (3D графика также поддерживается).

Данный модель поддерживает множество вариантов отображения:

* Графики (line plot)

* Диаграммы разброса (scatter plot)

* Столбчатые диаграммы (bar chart) и гистограммы (histogram)

* Круговые диаграммы (pie chart)

* Ствол-лист диаграммы (stem plot)

* Контурные графики (contour plot)

* Поля градиентов (quiver)

* Спектральные диаграммы (spectrogram)

Методы | Описание
------------ | -------------
plt.scatter() | маркер или точечное рисование
plt.plot() | ломаная линия
plt.text() | нанесение текста
plt.bar(), plt.barh(), plt.barbs(), broken_barh() | столбчатая диаграмма
plt.hist(), plt.hist2d(), plt.hlines | гистограмма
plt.pie() | круговая диаграмма
plt.boxplot() | "ящик с усами" (boxwhisker)
plt.errorbar() | оценка погрешности, "усы"
plt.contour() | изолинии;
plt.contourf() | изолинии с послойной окраской
plt.pcolor(), plt.pcolormesh() | псевдоцветное изображение матрицы (2D массива)
plt.imshow() | вставка графики (пиксели + сглаживание)
plt.matshow() | отображение данных в виде квадратов

### Пример

```python
import matplotlib.pyplot as plt 

year = [1950, 1975, 2000, 2018] 
population = [2.12, 3.681, 5.312, 6.981] 

plt.plot(year, population) 
plt.show()

```

![Картинка]([https://upload.wikimedia.org/wikipedia/ru/thumb/7/7c/Matplotlib_example_plot.png/400px-Matplotlib_example_plot.png](https://sun9-north.userapi.com/sun9-86/s/v1/if2/wK-XGRXigvSyeM-xwbnupumgrL_t9kwTxbUNbTjO_caXN9DoldZAHUX7snn6DuxMkEbYStFqoFmVvF3c8eABjxME.jpg?size=597x446&quality=96&type=album))

# Оценка районов/локаций Москвы с точки зрения их привлекательности для семей с детьми

## Описание проекта

Разработка моделей оценки районов\локаций Москвы с точки зрения их привлекательности для семей с детьми на основе открытых данных с использованием инструментов пространственного анализа.

## Решение

`ArcGIS` `ModelBuilder` `Python` `Pandas` `Seaborn` `Matplotlib`

На основе пространственных данных [OpenStreetMap](https://www.openstreetmap.org/#map=13/55.7444/37.6253) разработаны две модели классификации территорий города Москвы с точки зрения их привлекательности для семей с детьми:
1. **Классификация в бинарной шкале**: модель основана на пространственном анализе **векторных** данных, определяет для каждого объекта жилого фонда Москвы, является ли он благоприятным для проживания с детьми (0 - неблаприятные условия, 1 - благоприятные).
2. **Классификация в ранговой шкале**: модель основана на пространственном анализе **растровых** данных, определяет для каждого объекта жилого фонда Москвы значения в диапазоне от 1 до 5, что означает 1 - самые благоприятные условия для семей с детьми, 5 - самые неблагоприятные.

[Mos_children.gdb.zip](https://github.com/Kri5PO/Test/blob/main/Mos_children.gdb.zip) - архив с исходными данными

[Toolbox.tbx](https://github.com/Kri5PO/Test/blob/main/Toolbox.tbx) - набора инструментов для ArcGIS с разработанными моделями

[Открыть Notebook](https://github.com/Kri5PO/Test/blob/main/Mos_for_children.ipynb)

# Masks r-cnn tutorial #
P.S. подразумевается, что вы используете среду Anaconda
* Подготовка:

pip install tensorflow==1.14.0

pip install mrcnn или git clone https://github.com/matterport/Mask_RCNN

pip install cv2

* Начало работы:

Для начала соберем датасет. Лично я для этого использую поисковую выдачу яндекса, но ни кто не мешает использовать что-то другое.

Алгоритм действий:
1) Ищем изображения
2) Через Chrome сохраняем страницу с выдачей(полностью)
3) Находим папку с материалами страницы
4) Удаляем все лишние элементы(должны остаться: i, i(1), i(2)...)
5) Скачайте файл convertor.py в дерикторию с папкой
6) Запустите файл

После этих действий необхадимо удостовериться, что в папке нет копий(позже будет добавлен код)

Теперь приступим к аннотированию изображений. Я предпочитаю использовать веб-инструмент VIA (VGG Image Annotator)

https://www.cs.bgu.ac.il/~drobya/annotation.html - VIA

На главной странице можно увидеть "Getting Started" - прочитайте его.


# Постановка задачи

## Общее описание

На вход алгоритму приходит фотография, на которой изображены предметы на светлой горизонтальной плоскоти и многоугольник. По данной фотографии требуется определить, возможно ли разместить предметы внутри многоугольника.

Фотографии предметов и текстура горизонтальной плоскости находятся в папке objects. Многоугольник, подающийся на вход, рисуется темным маркером на листе бумаги формата А4 рядом с предметами.

## Требования к входным данным

- Разрешение фотографий от 800x600 до 1000x800. Качество должно быть таким, чтобы края объектов были четко различимы.
- Высота съемки до метра. Угол расположения камеры должен быть близок к прямому: плоскость камеры располагается параллельно плоскости, в которой расположены объекты.
- Объекты должны быть разделимы: пересечения недопустимы. Не допускается расположение в кадре лишь части объекта.
- Тень не должна сливаться с объектами: ее интенивность должна быть такой, чтобы края объектов были четко различимы.
- На вход алгоритма допускаются только выпуклые многоугольники с числом вершин от 3 до 8.
- Объекты на фото должны быть разными. Допускается наличие на фотографии только предметов из папки objects.
- Допускается вращение объектов только относительно оси, перпендикулярной плоскости их расположения.

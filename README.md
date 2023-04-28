# Photo_Colorization
Разработка автоматического подхода, который будет генерировать реалистичные раскраски черно-белых (B & W) фотографий  на Python, используя библиотеки Numpy, Matplotlib,OpenCV, DNN и Caffe. Написанный и отлаженный скрипт Python bw2c-ru.py принимает черно-белое изображение на входе и автоматически возвращает цветное изображение на выходе
Использована нейронная сеть от Rich Zhang которая была обучена на 1.3млн изображений,  файлы сохраненной модели для этой сети занимают около 300Мбайт

Загрузить файлы (https://drive.google.com/drive/folders/1FaDajjtAsntF_Sw5gqF0WyakviA5l8-a?usp=sharing)
colorization_deploy_v2.prototxt, 
colorization_release_v2.caffemodel,
pts_in_hull.npy, и сохранить в папку models.


Пример раскраски изображения:
![изображение](https://user-images.githubusercontent.com/96390154/233780088-b282f007-e383-408d-a356-c2f0d745a255.png)

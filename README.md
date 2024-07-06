# Выравнивание изображений номеров автомобилей

## Структура проекта
_labeled_detection_data_ - размеченный и аугментированный датасет для дообучения моделей yolo (рекомендуется использовать версии yolov7 и yolov8) 

_labeled_detection_data/train_ - тренировочная выборка

_labeled_detection_data/valid_ - валидационная выборка

_labeled_detection_data/run.yaml_ - файл для дообучения yolo

_pipeline_algo.ipynb_ - ноутбук с решением задачи с помощью алгоритмического поиска контуров

_pipeline_yolo.ipynb_ - ноутбук с решением задачи с помощью дообученной модели yolov8

_finetuned_yolov8l.pth_ - веса дообученной модели yolov8l под распознавание углов номерного знака

_yolo_finetune.ipynb_ - ноутбук с дообучением yolov8l



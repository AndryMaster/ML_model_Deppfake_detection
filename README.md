# Проект
## Антидипфейк: Вызов 2025

[Страница конкурса][intensive]

### Описание

> Конкурс «Антидипфейк: Вызов 2025» нацелен на создание эффективных инструментов
> для борьбы с дипфейками — синтетическим контентом, который становится всё более
> опасным инструментом дезинформации. В эпоху цифровой трансформации,
> когда информация распространяется молниеносно, важно разработать технологии,
> защищающие общество от манипуляций и ложных сведений. Конкурс стимулирует
> инновационное мышление и привлечение талантливых специалистов к решению одной
> из самых актуальных проблем современности.

Для проекта была выбрана модель SqueezeNeXt (~2M params) и 
феймворк PyTorch (& torchvision), также применялась аугментация данных.
Подробнее можно увидеть в файле `project.ipynb` 

### Пояснения

- `project.ipynb` - Jupyter Notebook с кодом проекта
- `project.html` - html версия для чтения проекта
- `models/` - директория с обученными моделями

## Ссылки на ресурсы

Архитектура _ResNet_:

- статья

Архитектура _SqueezeNeXt_:

- [medium] - статья на Medium
- [github] - пример реализации архитектуры на github
- [arxiv] - оригинальная статья на arxiv

Архитектура _ViT_:

- статья

## Исходники

Другие ссылки где посмотреть исходники

| Source | Link |
| ------ | ------ |
| YandexDisk | [https://disk.yandex.ru/d/PdQzdRuKim-lnQ][disk] |
| GitHub | [https://github.com/AndryMaster/ML_model_x-ray_images][git] |

## License
MIT


   [intensive]: <https://challenge.braim.org/landing/antideepfake_contest>
   [disk]: <https://disk.yandex.ru/d/PdQzdRuKim-lnQ>
   [git]: <https://github.com/AndryMaster/ML_model_x-ray_images>
   
   [medium]: <https://sh-tsang.medium.com/reading-squeezenext-hardware-aware-neural-network-design-image-classification-3fc8d1d3f76>
   [github]: <https://github.com/osmr/imgclsmob/blob/c03fa67de3c9e454e9b6d35fe9cbb6b15c28fda7/pytorch/pytorchcv/models/squeezenext.py>
   [arxiv]: <https://arxiv.org/abs/1803.10615>

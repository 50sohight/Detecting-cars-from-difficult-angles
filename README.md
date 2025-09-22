# Vehicle Detection from Challenging Angles
This repository is dedicated to my second project, completed during the second semester for the project practicum. On this page, you can find a trained YOLO model for detecting vehicles from difficult angles. The project also includes the dataset with annotations.

## Metrics obtained during fine-tuning
**Model trained on 400 images**
precision(B) ~ 0.94
recall(B) ~ 0.84
mAP50(B) ~ 0.91
*mAP50-95(B)* ~ 0.74

## Usage
The file main.ipynb contains three blocks created for: installing dependencies, using pre-trained models, and training your own models on this dataset.

### Using the Pre-trained Model
This repository provides two pre-trained models: one trained on 300 images and another on 400 images from the dataset. You can find them in the /runs/detect/ directory.
To use a model, upload your images to the images folder. Then, in the "Using the model" block, change the path to your image's filename and specify the output_path (the name and location where your processed image will be saved).

### Training
This section contains the code used to train the two provided models.

## Important
You are free to use the models and dataset as you see fit. Good luck!
Next, you will see a comparison between the regular YOLO and the pre-trained models.

# Обнаружение машин с тяжелых ракурсов
Данный репозиторий посвещен моему второму проекту, сделанному во время второго семестра для проектного практикума. На данной странице вы можете найти обученную модель YOLO для обнаружения машин в сложных ракурсах. Также проект содержит сам датасет с разметкой.  

## Метрики полученные в ходе дообучения
**Модель на 400 изображений**
precision(B) ~ 0.94
recall(B)	~ 0.84
mAP50(B) ~ 0.91
mAP50-95(B) ~ 0.74

## Использование
В файле main.ipynb представлены 3 блока созданных для: установки зависимостей, использовании предобученых моделей, тренировки своих моделей на данном датасете.  

### Использование предобученной модели
В данном репозитории предоставлены 2 обученные модели на 300 фотках и на 400 фотках из датасета, которые вы можете найти по пути /runs/detect/.  
Для использования модели загрузите свои фотографии в папку images, после чего в блоке "Using the model" заметине имя в пути на название вашей фотографии, а также output_path(название и место куда будет сохраняться ваше фото)  

### Обучение
В данном блоке вы найдете код который использовался для обучение данных двух моделей.

## Важное
Вы можете использовать модели и датасет так как посчитаете нужным - удачи!
Дальше вы увидите сравнение фоток обычной yolo и предобученных моделей.  
  
![1](https://github.com/user-attachments/assets/a438ec5c-f97a-4182-bc42-69a68a64641a)
![1_2](https://github.com/user-attachments/assets/0de2457e-fb85-49b7-a252-bbe4207eff00)
  
![3_2](https://github.com/user-attachments/assets/f25344e5-5e3b-4adf-8e32-f23a71dbbc58)
![3](https://github.com/user-attachments/assets/b1a4fe60-b263-497c-b1db-623e977abd28)
  
![4_2](https://github.com/user-attachments/assets/0b149e86-ba96-4155-b0fb-9bf5c8d13264)
![4](https://github.com/user-attachments/assets/ab074150-86b2-4909-8cd2-39623440a6a7)


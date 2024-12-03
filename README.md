# Model-for-AI-detection-of-pipeline-defects
Модель анализирует датасет, обрабатывает при помощи методов RF и TurboML.
Для работы необходимо ввести расположение файла (можно взять за основу предложенный файл "captured_data").
!ВАЖНО!
В основной ветке в файле Turbo_Forest_Dataset_2.0 сохранены результаты компиляции, с которыми можно ознакомиться.
Кратко по результатам: Точность около 83-85%.


This model analyses the choosen dataset, processes it with turbomachinery and randomforest methods
If you want to try this model, you should change data path: data = np.fromfile(r'YOUR PATH', dtype='B', count=-1)

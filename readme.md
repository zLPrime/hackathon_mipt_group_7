# Идентификация художника картины

### Описание проекта:   
Разработка математической модели с применением нейросетей для точного определения авторства картин. Прогнозирование будущего развития технологии в области художественной экспертизы. Задача CV (Computer VIsion) классификации.

### Этапы работы:   
- Поиск исходных данных, сбор и обработка
- Обучение и тестирование модели
- Интерпретация результатов

### Описание файлов:
Файл 'Хакатон_группа_7_Paintings_1.ipynb' содержит реализацию задачи посредством предобученной модели с архитектурой VGG16. Файл 'my_CNN_Хакатон_группа_7_Paintings_.ipynb' содержит реализацию "авторской" вручную написанной сверточной нейронной сети. Ее точность составила 20%, так как база картин не столь велика, но даже на тех же данных точность предобученной модели гораздо выше.

### Установка:
В реализации мы используем вручную заготовленную базу картин российских художников, которая хранится на гугл диске по этой ссылке: https://drive.google.com/file/d/1BwzLTUkP7UlFyhjlJ49ijd9ber3VW-Fn/view. Скопируйте арихв на свой гугл диск, чтобы получить к нему доступ из нашего кода. Конечно, обычно рассматривают от 1000 картин на одного художника, но в силу того, что базу составляли мы сами, таких чисел нам достичь не удалось. 
В остальном, достаточно следовать коду.

### Выводы:  
- Проведена работа на основе архитектуры, с использованием нейросети с высокой точностью в определении авторства картин.
- На тестовой базе достигнут уровень точности в 81 процент, что подтверждает эффективность модели.
- Полученные результаты свидетельствуют о потенциале данной технологии в области идентификации художественных почерков и стилей, открывая новые перспективы для развития и применения в сфере искусства и культуры.



# Проект 2. Анализ резюме на hh.ru

skillfactory_rds

Python 3.9.7

## Оглавление

[1.Описание проекта](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0)

[2.Какой кейс решаем?](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BA%D0%B5%D0%B9%D1%81-%D1%80%D0%B5%D1%88%D0%B0%D0%B5%D0%BC)

[3.Краткая информация о данных](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)

[4.Этапы работы над проектом](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D0%BD%D0%B0%D0%B4-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%BC) 

[5.Результат](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82)

[6.Выводы](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B)


### Описание проекта
Часть соискателей на портале hh.ru не указывает желаемую заработную плату, когда составляет своё резюме.

Это является помехой для рекомендательной системы HeadHunter, которая подбирает соискателям список наиболее подходящих вакансий, а работодателям — список наиболее подходящих специалистов.

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.  

:arrow_up: [к оглавлению](https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/README.md#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)


### Какой кейс решаем?

Прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить.

*Этапы выполнения проекта:*

Наш проект будет состоять из четырёх частей:
1. Базовый анализ структуры данных
2. Преобразование данных
3. Разведывательный анализ
4. Очистка данных

Каждая часть состоит из блока практических заданий, которые выполняются в программе jupyter-ноутбук
и контрольных вопросов на платформе, отвечая на которые можно проверить верность своего решения. 

*Метрика качества*

Правильно ответив на все контрольные вопросы можно максимально набрать 30 баллов.
Загрузив ноутбук со своим решением на GitHub и оформив его в соответствии с требованиями можно 
получить ещё 10 баллов (из них 8 баллов — за основное задание и 2 балла — за дополнительное) за выводы по разведывательному анализу.

*Что практикуем*

Учимся писать хороший код на Python.

Учимся визуализировать данные c помощью библиотек matplotlib, seaborn, plotly.

Учимся использовать переменные, основные структуры данных (списки, словари, множества), циклы, функции, библиотеки numpy и pandas

Учимся работать с GitHub.

### Краткая информация о данных

1. Данные о резюме находятся в хранилище Google Диск. 
Название файла: dst-3.0_16_1_hh_database.csv 
Разделитель: sep=';'
Ссылка: https://drive.google.com/file/d/10iv5wAsnXAy9BxCAInU1pV3YG_W-N55e/view?usp=sharing

2. Данные о курсах валют лежат в репозитории Github
Название файла: ExchangeRates.csv
Разделитель: sep = ','
Ссылка: https://github.com/PavelNovikov888/sf_data_science/blob/main/sf_data_science/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D1%8B/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%202.%20%D0%90https://drive.google.com/file/d/1Vr3sphzp_OnZCW491h6zgnnHF8d6Y_Fa/view?usp=sharing

### Этапы работы над проектом

Создал датафрейм из базы данных резюме.

Выполнил контрольные задания в блоке Исследование данных, Преобразование данных, Очистка данных

Сохранил исходную базу в хранилище Google Диск

Выгрузил на GitHub предварительно создав соответствующую структуру проектов.

Сохранил окружение для воспроизводимости кода(файл requirements.txt) и выложил файл в соответствующую папку проекта на GitHub 

### Результат

Практически применил полученные в ходе обучения знания по исследованию, визуализации, очистке данных.

Попрактиковался в написании кода. Получил практический опыт правильного оформления кода по стандарту PEP8.

Освоил инструментарий программы VS CODE в части создания программ, написания текстовых файлов, выгрузки изменений на GitHub, обеспечения воспроизводимости кода.

Получил опыт разработки проекта в условиях ограниченного времени.

Наладил взаимодействие с менторами.

### Выводы

Подготовка данных это важная и объемная по времени часть работы специалиста по данным.

# Курс "Нейронные сети и глубокое обучение" Самарского университета  
Лектор [Артем Владимирович Никоноров](https://ssau.ru/staff/66320001-nikonorov-artem-vladimirovich), д.т.н., artniko@gmail.com  
Ассистенты: [Виктория Витальевна Евдокимова](https://ssau.ru/staff/304968209-evdokimova-viktoriya-vitalevna/edu), 
            [Никита Александрович Фирсов](https://ssau.ru/staff/441332557-firsov-nikita-aleksandrovich/edu) 

Телеграмм группа курса:
https://t.me/DL_SamU_2022


Курс основывается на предыдущих более обзорных лекциях и туториалах по глубокому обучению и его приложениях, в частности, вот [небольшая обзорная лекция](https://youtu.be/Gpq1PFUee88) в Кавказском Математическом Центре. Также во многом этот курс является адаптацией известнейшего курса http://cs231n.stanford.edu/  

Материалы курса за 2020-21 годы расположены [здесь](https://github.com/da0c/DL_Course_SamU). 

Курс 2022 года состоит из трех частей:  
**Введение в глубокое обучение:** краткий обзор всех достижений машинного обучения до сверточных нейронных сетей, две лекции.  
**Основы глубокого обучения:** собственно основной материал курса, порядка 8 лекций.  
**Дополнительные главы глубокого обучения:** новинки и SOTA решения, трансформеры, метаобучение, zero shot learning и другое.  

## График проведения курса 2022-2023
**Видеозаписи лекций 2020-21 годов  можно найти по [ссылке](https://github.com/da0c/DL_Course_SamU).**  

**Лекции раз в неделю по [четвергам](https://ssau.ru/rasp?staffId=66320001&selectedWeek=3&selectedWeekday=1).
Начало в 19-00 по Самаре. Продолжительность лекции два астрономических часа.**

Первая лекция: 10.09.22 в 10:00 в Zoom.

**Следующая лекция: 13.10.22 в 19:00 по Самаре в Zoom.**

Подключиться к конференции Zoom  
https://us02web.zoom.us/j/8366671872?pwd=NS9ZaXNWWG55Y0pESUZIZHlRa0U5dz09  

Идентификатор конференции: 836 667 1872  
Код доступа: 810019  


## Лекционный план 2022-2023  

**Часть первая. Введение в глубокое обучение.**   
  
**Лекции 1,2. Классификация, основанная на данных**   

Введение в курс.  
Задача классификации изображений.  
Подходы основанные на данных.  
Основные идеи - От MLP до CNN.

[Видеозапись первой части](https://youtu.be/pruCadZdhmQ)  
[Видеозапись второй части](https://youtu.be/bsdpRfQM-O8)  
Презентация - TBD.
  
**Часть вторая. Основы глубокого обучения.**   
  
**Лекция 3. Функции потерь и оптимизация.**  

Мультиклассовый SVM и его функция потерь.  
Софтмакс и мультимодальная логистическая регрессия.  
Оптимизация функции потерь.  
Стохастический градиентный спуск (SGD).  
Разбор задач к самостоятельной: функции потерь для SVM и софтмакса.  

[Видеозапись третьей лекции](https://youtu.be/9nUzJxCeKIc)  
[Презентация к лекции 3](https://github.com/kvvik/DL_Course_SamU/blob/master/Lectures/Lecture_3_SGD_22.pdf)  
[Python-ноутбук к лекции 3](https://github.com/kvvik/DL_Course_SamU/blob/master/Lectures/Lecture_3.ipynb)  

**Лекция 4. Нейронные сети и обратное распространение ошибки.**  
 
Классификация с точки зрения нейронной сети.  
Многослойный перцептрон.  
Представление сети в виде вычислительного графа.
Алгоритм обратного распространения ошибки на вычислительном графе.  
Разбор задач к самостоятельной: прямое и обратное распротранение по вычислительному графу.  

[Видеозапись четвертой лекции, первая часть](https://youtu.be/Zx6YggTqTJs)  
[Видеозапись четвертой лекции, вторая часть](https://youtu.be/h4mE1AhLvAI)  

[Презентация к лекции 4](https://github.com/kvvik/DL_Course_SamU/blob/master/Lectures/lecture_4_BP_22.pdf)  

**Лекция 5. Сверточные сети (СНС).**  
История.  
Основные операции СНС.  
Применение СНС вне задач машинного зрения.  
Разбор задач к самостоятельной: расчет выхода сверточной сети.  

**Лекция 6. Инструментарий глубокого обучения.**  
CPU vs GPU vs TPU.  
Пакеты глубокого обучения, Tensorflow, Keras и другие.  
Вычислительные графы СНС.  

**Самостоятельня работа.**  
  
Три задачи из лекций 2-5.  
**Внимание:** участие в самостоятельной, как и сдача лабораторных, необходимое условие для допуска к экзамену.  

**Лекция 7. Обучение СНС, часть 1.**  

Активационные функции, обработка данных сетью.  
Пакетная нормализация и другие трюки.  
Transfer learning.

**Лекция 8. Обучение СНС, часть 2.**  

Политики обновления гиперпараметров.  
Тюнинг процесса обучения.
Аугментация данных.  

**Лекция 9. Архитектуры СНС**  

Базовые архитектуры - AlexNet, VGG, GoogleNet, ResNet, UNET и другие.  


**Часть третья. Дополнительные главы**
  
**Лекция 10. Генеративные и рекуррентные модели**  


1. RNN/LSTM.  
Механизм attention.
Обработка естественного языка.

2. GAN сети.

3. Детектирование и сегментация.

**Лекция 11. SOTA модели**  
Трансформеры   
Zero shot подходы  
Метаобучение  
Федеративное обучение  
 


## План лабораторных работ

Списки групп и статус выполнения лабораторных работ можно найти в [гугл-таблице](https://docs.google.com/spreadsheets/d/1dRMlUIZ1Wf_DmHZBubtRtNbHxteb7ThbJqqZhRCiMEw/edit#gid=0) . 


- [для групп 6231, 6233](lab_schedule_6231_6233.md)
- [для группы 1143](lab_schedule_1143.md)



## Литература и дополнительные источники  

1. Отличная книга на русском по глубокому обучению -  
[С. И. Николенко, А. Кадурин, Е. В. Архангельская, Глубокое обучение. Погружение в мир нейронных сетей. 2018](https://www.ozon.ru/context/detail/id/154415719/)  
2. Отличная книга по техническим аспектам реализации на Python -  
[Шолле Франсуа, Глубокое обучение на Python](https://www.ozon.ru/context/detail/id/145615583/)  

3. [Лекционный курс К.В. Воронцова по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29).
4. [Видеолекция академика Ю.И. Журавлева](https://www.youtube.com/watch?v=R3CMqrrIWOk) об истоках машинного обучения в СССР и о сочетании эвристики и науки в распознавании образов.  
5. Видеолекции С.И. Николенко по GAN сетям [1](https://www.youtube.com/watch?v=SlJgPIOlpiI), [2](https://www.youtube.com/watch?v=w38m5mTrG_M&t=1147s).
Хорошая проверка ваших знаний, на выходе из настоящего курса вы должны полностью понимать то, что говорится в этих лекциях по GAN.  
  
6. Хорошая вводная книга по питону и базовым библиотекам, таким как numpy, pandas, jupyter.
[Python и анализ данных. Второе издание [2020] Уэс Маккинни](https://www.ozon.ru/product/python-i-analiz-dannyh-vtoroe-izdanie-makkini-ues-285933371)  
[Альтернативная ссылка](https://vk.com/wall-51126445_67509)  
Важное замечание: первое издание книги содержит в себе короткое введение в python, изъятое из второго издания. Первое издание с руководством по питону можно найти [например здесь](https://t.me/physics_lib).  

[Хороший телеграмм канал с подборкой технических книг](https://t.me/physics_lib)  




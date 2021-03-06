# <p style="text-align: center;"> Классификация изображений с локализацией RIO </p>

**В данном проекте по имеющимся картинкам и аннотациям к ним необходимо построить нейросеть для классификации изображений и выделения на них ROI**

##### План выполнения работы:
- ознакомимся с представленными изображениями, аннотациями;
- создадим отложенную выборку для тестирования итоговой модели;
- аугментируем тренировочную выборку;
- подготовим массивы данных для обучения нейросети;
- возьмем предобученную нейросеть, построим два выхода для классификации изображений и определения положения BoundingBox'ов;
- в качестве функций потерь будем использовать binary_crossentropy для классификации и Mean_Squared_Error для регресии;
- в качестве метрик будем использовать Accuracy и MeanIoU соответственно;
- оценим получившиеся результаты на отложенной выборке.


**Для выполнения проекта использовались библиотеки:**  
- *Pandas*  
- *Numpy*  
- *PIL*
- *os*  
- *cv2*  
- *tarfile*
- *matplotlib*  
- *tensorflow*  
- *keras*
- *imgaug*  
- *imageio*

**Проект находится в стадии работы, т.к. полученные метрики считаю неудовлетворительными**

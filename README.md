# <center> Проект 1: Анализ резюме из HeadHunter

## Оглавление  
[1. Описание проекта](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Описание-проекта)  
[2. Задача](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#КЗадача)  
[3. Краткая информация о данных](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Результат)    
[6. Выводы](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Выводы) 

### Описание проекта    
Анализ базы банных HeadHunter с резюме соискателей.

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Оглавление)


### Задача    
Необходимо произвести предобработку базы данных HeadHunter с резюме соискателей для дальнейшего построения корректной модели для рекомендательной системы платформы HeadHunter.  


**Метрика качества**     
* Решение оформляется только в Jupyter Notebook;
* Решение оформляется в соответствии с ноутбуком-шаблоном;
* Каждое задание выполняется в отдельной ячейке, выделенной под задание;
* Код для каждого задания оформляется в одной-двух jupyter-ячейках;
* Решение должно использовать только пройденный материал: переменные, основные структуры данных (списки, словари, множества), циклы, функции, библиотеки numpy, pandas, matplotlib, seaborn, plotly; 
* Код должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий;
* Пользуйтесь руководством PEP 8;
* Графики оформляются в соответствии с теми правилами, которые мы приводили в модуле по визуализации данных;
* Обязательное требование: графики должны содержать название, отражающее их суть, и подписи осей;
* Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке (в шаблоне они помечены как ваши выводы здесь). Выводы должны быть представлены в виде небольших связанных предложений на русском языке.


**Что практикуем**     
* Написание хорошего кода на Python;
* Использование библиотек Numpy и Pandas, а также использования библиотек визуализации: Matplotlib, Seaborn, Plotly;
* Верный выбор графика для визуализации, умение читать инфоргафику и делать правильные выводы;   
* Работу с GitHub.


### Краткая информация о данных
* [Исходный файл в формате CSV](https://drive.google.com/file/d/1c-r3Xol9eg5ELvia4r4Vu6XUMqJZPcI1/view?usp=sharing)
Для анализа и дальнейшей предобработки данных был представлен файл csv формата, содержащий резюме соискателей работы на платформе HeadHunter.
Файл состоял из 12 столбцов и 44744 строк (тип данных object) отражающих следующую информацию о соискателе:
* Пол, возраст;
* Желаемый уровень заработной платы;                               
* Желаемую должность;       
* Город, переезд, командировки;    
* Занятость;                        
* График;                           
* Опыт работы;                      
* Последнее/нынешнее место работы;  
* Последняя/нынешняя должность;    
* Образование и ВУЗ;                
* Обновление резюме;                
* Наличие авто. 

  
:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Оглавление)


### Этапы работы над проектом  
**Исследование структуры данных:**  
Первоначально необходимо произвести исследование структуры данных, для дальнейшего понимания объема работы по предобработке, в том числе:
* Почитать данные;
* Вывести статистическую информацию о данных;
* Выявить количество непустых значений в данных.


**Преобразование данных**
Необходимо избавиться от неинформативных признаков и на их основе создать информативные:
* Анализ имеющихся признаков;
* Создание информативных признаков, путем преобразования имеющихся;
* Удаление неинформативных признаков. 


**Исследование зависимостей в данных**
Построение инфоргафики для исследования и понимания зависимостей признаков данных.


**Очистка данных**
Очистка данных от дубликатов и и пропусков:
* Выявление и последующее удаление дубликатов;
* Выявление и последующее удаление пропусков;
* Замена пропусков на иные значения путем использования агрегирующих методов.

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Оглавление)


### Результаты:  
В результате проделанной работы были созданны информативные признаки данных, выявлены и удалены все пропуски и дубликаты, построена инфографика для более глубокого понимания зависимостей и взаимосвязей признаков данных.   

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Оглавление)


### Выводы:  
Настоящая задача наглядно показывает работу специалиста Data Scientist, дает представление о будущей работе, помогает применить и отработать знания полученные на практике и подготавливает к дальнейшей профессиональной карьере.

:arrow_up:[к оглавлению](https://github.com/mrfluffypaws/10PROJECT-1.-HeadHunter/blob/main/README.md#Оглавление)


Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами

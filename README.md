# Manual_testing

В данном документе представлены примеры практических навыков ручного тестирования.

## Оглавление
1. [Составление тестовых артефактов](#составление-тестовых-артефактов)   
   1.1. [Чек-лист](#чек-лист-для-объекта-корзина)     
   1.2. [Тест-кейс](#тест-кейс)   
   1.3. [Баг-репорт](#баг-репорт)   
   1.4. [Тест-план](#тест-план-для-объекта-карточка-товара)   
2. [Техники тест-дизайна](#техники-тест-дизайна)   
   2.1. [Тестирование состояний и переходов](#тестирование-состояний-и-переходов-объекта-корзина)   
   2.2. [Таблица принятия решений](#таблица-принятия-решений)      
   2.3. [Попарное тестирование](#попарное-тестирование)      
   2.4. [Предугадывание ошибок](#предугадывание-ошибок)    
3. [Тестирование REST API]()
4. [UI тестирование]()

   
## Составление тестовых артефактов

По результату тестирования web-приложения https://megamarket.ru предлагаю ознакомиться с примерами моего составления следующих тестовых артефактов:

### Чек-лист для объекта "Корзина"

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/чек-лист.png "Чек-лист")

<br>

### Тест-кейс

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тк.png "ТК")

<br>

### Баг-репорт

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/бр.png "БР")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/прил1.png "БР")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/прил2.png "БР")

<br>

### Тест-план для объекта "Карточка товара"

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тп1.png "тп")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/Карточка%20товара-декомпозиция.jpeg "тп")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тп2.png "тп")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тд1.png "тп")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тд2.png "тп")
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тп3.png "тп")

<br>

## Техники тест-дизайна

По результату тестирования web-приложения https://megamarket.ru предлагаю ознакомиться с примерами моего практического применения техник тест-дизайна:

### Тестирование состояний и переходов объекта "Корзина"

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/диаграмма%20состояний.png "диаграмма")   

*Таблица состояний и переходов*   

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/таблица%20состояний.png "таблица")   

*Итоговый чек-лист*   

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/чл%20состояний.png "тп")

<br>

### Таблица принятия решений

*Тестируемая форма*   

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тпр.png "тпр")

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/тпр2.png "тпр")

<br>

### Попарное тестирование
Для тестирование фильтра в каталоге использовала инструмент для попарного тестирования https://pairwise.teremokgames.com   

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/фильтр.png "попарное")

<br>

В результате были получены следующие комбинации входных данных для кейсов:

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/попарное.png "попарное")

<br>

### Предугадывание ошибок
Ниже рассмотрены несколько сценариев проверок, по которым расписаны чек-листы на основе предугадывания ошибок

![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/предугадывание.png "предугадывание")

<br>

## Тестирование REST API

В результате тестирования клиент-серверной архитектуры web-приложения http://ecom-backend.sedtest-tools.ru:4000/ мной была проделана следующая работа:

- Декомпозиция и анализ продукта
![Alt-текст](https://github.com/anisimova-an-an/Manual_testing/blob/main/Backend-Backend.png "постман")
- Выбор техник тест-дизайна и проектирование коллекции тестов в Постман (вложенный файл с коллекцией и окружением)
[Ссылка на коллекцию](https://github.com/anisimova-an-an/Manual_testing/blob/main/simulator.postman_collection%20(1).json)
[Ссылка на окружение](https://github.com/anisimova-an-an/Manual_testing/blob/main/Проект.postman_environment%20(1).json)

- Реализация тестов
- Составление баг-репортов
https://redmine.sedtest-school.ru/projects/pt5-anisimova-an-an/issues (начиная с задачи 12240 по 12269)


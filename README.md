# Проекты на ReactJS (junior)

**👀 Ветка**: `counter` 
#### 1. Что такое состояние (state)? 
___
State - это обычный JavaScript-объект, он находится внутри компонента (по аналогии с переменными, которые объявлены внутри функции) и доступен только из компонента. 

#### 2. Хук useState
___
const [state, setState] = useState(initialState);

Во время первоначального рендеринга возвращаемое состояние (state) совпадает со значением, переданным в качестве первого аргумента (initialState).

Функция setState используется для обновления состояния. Она принимает новое значение состояния и ставит в очередь повторный рендер компонента.

setState(newState);
Во время последующих повторных рендеров первое значение, возвращаемое useState, всегда будет самым последним состоянием после применения обновлений.

#### 3. Как при клике на кнопку вызывать функцию? 
___ 
Необходимо использовать обработчик событий: onClick в него передать стрелочную функцию и вызов непосредственно функцию, которую мы хотим вызвать. А затем мы пишем непосредственно условия для этой функции

**👀 Ветка**: `modal`
1. Условный рендер
2. Как делать анимированное модальное окно
3. Как передавать в модально окно контент (children)
4. Как передавать пропсы

**👀 Ветка**: `quiz`
1. Поэтапный рендер контента
2. Прогрессбар
3. Передача пропсов для рендера результата опроса

## Список гостей (пользователей)
![1660249789449](https://user-images.githubusercontent.com/12086860/184236601-2c8d94bf-105c-4b48-982c-65a6ed4f8c51.png)

**🌿 Ветка**: `users`

**👀 Что изучим?**
1. Работа с хуком useEffect
2. Отправка запроса на бэкенд с помощью fetch и рендер этих данных
3. Скелетон с помощью библиотеки `react-content-loader`
4. Поиск пользователей
5. Рендер списка пользователей
6. Spread-оператор
7. Добавление/удаление пользователей из массива приглашений
8. Отображение информации о загрузке контента

## Конвертер валют
![1660250017350](https://user-images.githubusercontent.com/12086860/184237245-dd26fc7e-1b84-4490-b9cf-3d40a4ded550.png)

**🌿 Ветка**: currency-converter

**👀 Что изучим?**
1. Работа с хуком useEffect
2. Получение списка курса валют из отдельного API 
3. Конвертация одной валюты в другую и наоборот (без бэкенда)

## Коллекция фотографий
![1660250202173](https://user-images.githubusercontent.com/12086860/184237707-4810b1d8-f20b-40cf-93ea-37d2051b87ba.png)


**🌿 Ветка**: `photos`

**👀 Что изучим?**
1. Фильтрация коллекций с помощью категорий
2. Поиск коллекций
3. Пагинация
4. Получение, пагинация через бэкенд
5. Отображение информации о загрузке контента

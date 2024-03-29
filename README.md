﻿# 3D T-shirt + OpenAI + React + Three.js + Vite + Tailwind + Framer Motion
![3D my logo](https://i.ibb.co/0BRq6q1/my-logo-tshirt.png)
## Как запустить? 🤔
### git clone (https) -> npm i -> 
{  
cd server -> npm run  
cd ..  
cd client -> npm run dev  
}
### Чтобы OpenAI работал:
1. Войти в аккаунт
2. Перейти на platform.openai.com/account/api-keys
3. Создать Api-key
4. Вставить Api-key в server/.env (OPENAI_API_KEY=ваш ключ)

## Функционал: 
1. Возможность загрузить любую картинку на full && logo принт
2. Диапазон выбора любого цвета майки hex-colors
3. Взаимодействие с ChatGPT - по запросу можно поменять лого и фулл сруктуру майки
4. Скрыть/показать лого и фулл структуру
5. Цвет майки полностью связан с цветами кнопок
6. На всех всплывающих блоках есть анимация
7. 3D камера + позиционирование главного элемента в пространстве с тенью

## Примеры работы с OpenAI
:black_square_button: Запрос: 

>Create a tiger skin shirt pattern that closely resembles the texture and color of a real tiger's skin.
>The pattern should feature orange and black stripes that are approximately two inches wide and spaced about and spaced about an inch apart.
>The overall pattern should be large enough to cover the front and back of a shirt. 
>Please ensure that the pattern is beautifully color-graded with vivid colors and includes intricate and hyper-detailed details to make it look as realistic as possible  

:white_check_mark: Результат: 

![Tiger-full-result](https://i.ibb.co/TmFXrX4/tiger-tshirt-sm.png)

:white_check_mark: Результат с похожим запросом для лого:  

![Tiger-logo-result](https://i.ibb.co/qCGmB5Z/logo-tiger-sm.png)

:white_check_mark: Далее - можно играться как угодно:

![Any result](https://i.ibb.co/Yhc2hrP/anytexture.png)

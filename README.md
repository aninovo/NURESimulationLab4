# Лабораторна робота №4. Моделювання у середовищі CoppeliaSim

# Мета роботи
Ознайомитись із можливостями середовища робототехнічного моделювання CoppeliaSim. Використовувати існуючі моделі та компоненти, отримати навички корегування логіки їхньої роботи. Отримати уявлення про синтакс мови Lua.

Завдання 1-4 виконано у файлі сцени lr4.ttt.

Завдання 5 виконано у файлі lr4_1.ttt.
Для руху по лінії за основу був взятий код туторіала, але змінено швидкість робота та "чутливість" сенсору:

<pre>sensorReading[i] = (data[11] < 0.5) </pre> 

на 

<pre>sensorReading[i] = (data[11] < 0.7) </pre> 

# tariff_recommendation

### Условия:
Оператор мобильной связи выяснил: многие клиенты пользуются архивными тарифами. Необходимо построить систему, способную проанализировать поведение клиентов и предложить пользователям новый тариф: «Смарт» или «Ультра».

Описание данных:  
Каждый объект в наборе данных — это информация о поведении одного пользователя за месяц. Известно:  
сalls — количество звонков,  
minutes — суммарная длительность звонков в минутах,  
messages — количество sms-сообщений,  
mb_used — израсходованный интернет-трафик в Мб,  
is_ultra — каким тарифом пользовался в течение месяца («Ультра» — 1, «Смарт» — 0).

### Ход работы:
- Изучение и предобработка данных
- Деление выборки на тестовую, валидационную и обучающую
- Исследование качества моделей на при изменении гипперпараметров
- Проверка качества модели на тестовой выборке
- Проверка модели на адекватность

### Вывод:
В ходе работы выборка была поделена на 3 части:
обучающую - 60%,
валидационную - 20%
тестовую 20%
Было проведенно исследование с использование 3 основных алгоритмов классификации:
Дерево решений
Логистическая регрессия
Случайный лес
Лучший результат на тестовой выборке показала модель Случайного леса 0.788

# IteratorPattern

Шаблон Iterator забезпечує спосіб послідовного доступу до елементів колекції, не знаючи, як структура колекції.

Ідея полягає в тому, що агрегатний об’єкт, такий як масив або список, надасть вам спосіб доступу до його елементів, не відкриваючи його внутрішньої структури.

Завдання:
Вибрати зі списку днів тижня вибрати усі дні крім неділі і суботи.

Створено клас колекції, Weeks який є об’єктом Aggregate. Week sклас містить приватний масив рядка, що містить дні тижня.
Клас IWeeksIteratorнаш інтерфейс Iterator.
В методі MoveNext просто пропускаються останні два значення в масиві, тобто субота та неділя за допомогою змінної (weeks.Length -2)

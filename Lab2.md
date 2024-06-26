# 2. Описати 2-3 вимоги у вигляді "Use case description"

## Use case #1
**Назва, опис:** Користувач має можливість лишати фідбек <br>
**Актори:** Користувач <br>
**Передумова:** Користувач зайшов на сайт https://www.greencity.social/#/greenCity  <br>
**Післяумова:** Користувач надіслав фідбек розробникам

### Основний шлях
**Дії актора:**
1. Користувач зайшов на сайт
2. Користувач натискає на кнопку для надання фідбеку.
3. Користувач заповнює форму для надання фідбеку, вказавши свій email та написавши фідбек у спецільний інпут.
4. Користувач натискає кнопку *Надіслати*.

**Відповідь системи:** <br>
2.1 Система виводить на екран певну форму для заповнення щоб користувач міг надіслати фідбек. <br>
4.1 Система перевіряє чи всі поля заповнені. <br>
4.2 Система проводить валідацію email. <br>
4.3 Система відправляє розробнику фідбек. <br>
4.4 Система перезавантажує сторінку і виводить на екран повідомлення про успішне надання фідбеку.

### Основний шлях 2
**Дії актора:**
1. Користувач зайшов на сайт.
2. Користувач на сторінці *Про нас* натискає на email.
3. Користувач надсилає електроного листа з фідбеком.

**Відповідь системи:** <br>
2.1 Система відкриває додаток (якщо він встановлений) для надсилання повідомлень на пошту. <br>
3.1 Система надсилає зворотній лист де вказано про те, що лист було надіслано успішно і що відповідь буде надіслана скоро.

### Винятковий шлях #1
**Дії актора:**
3. Користувач не до кінця заповнює форму, не вказавши свій email та написавши фідбек у спецільний інпут.
4. Користувач натискає кнопку *Надіслати*.

**Відповідь системи:** <br>
4.1 Система перевіряє чи всі поля заповнені. <br>
4.2 Система виводить повідомлення про те, що не всі поля заповнені. 

### Винятковий шлях #2
**Дії актора:**
3. Користувач заповнює форму, вказавши невалідний email та написавши фідбек у спецільний інпут.
4. Користувач натискає кнопку *Надіслати*.

**Відповідь системи:** <br>
4.2 Система проводить валідацію email. <br>
4.3 Система виводить повідомлення про те, що email не є валідним.


## Use Case #2

**Назва, опис:** Користувач отримує гайд по користуванню сайтом <br>
**Актори:** Користувач <br>
**Передумова:** Користувач відвідує сайт https://www.greencity.social/#/greenCity <br>
**Післяумова:** Користувач ознайомлений з функціоналом сайту

### Основний шлях
**Дії актора:**
1. Користувач заходить на сайт.
2. Користувач переглядає гайд та натискає кнопку "Далі" для переходу до наступного кроку.
3. Користувач продовжує переглядати гайд, доки не ознайомиться з усіма необхідними функціями сайту.

**Відповідь системи:** <br>
2.1 Система відображає кожен крок гайда з вказівками щодо користування сайтом. <br>
3.1 Система переходить до наступного кроку гайда після натискання кнопки "Далі". 

### Основний шлях 2
**Дії актора:**
1. Користувач відкриває розділ "Допомога" або "FAQ" на сайті.
2. Користувач переглядає інформацію щодо користування функціями сайту в цьому розділі.

**Відповідь системи:** <br>
2.1 Система відображає інформацію, що включає в себе кроки по користуванню сайтом.

## Use Case #3

**Назва, опис:** Користувач звертається до гарячої лінії для отримання допомоги <br>
**Актори:** Користувач <br>
**Передумова:** Користувач має проблему з акаунтом або сервісом <br>
**Післяумова:** Користувач отримує допомогу вирішення проблеми від гарячої лінії

### Основний шлях
**Дії актора:**
1. Користувач знаходить на сайті розділ "Підтримка" або "Контакти".
2. Користувач обирає опцію для зв'язку з гарячою лінією (номер телефону, чат, тощо).
3. Користувач контактує з гарячою лінією та описує свою проблему.
4. Представник гарячої лінії надає допомогу вирішення проблеми користувача.

**Відповідь системи:** <br>
2.1 Система надає контактні дані гарячої лінії. <br>
4.1 Система забезпечує з'єднання користувача з представником гарячої лінії.

### Основний шлях 2
**Дії актора:**
1. Користувач використовує веб-чат або чат-бот для звернення до гарячої лінії.
2. Користувач описує свою проблему в чаті.

**Відповідь системи:** <br>
2.1 Система забезпечує доступ до гарячої лінії через веб-чат або чат-бот.

[Client: React + Vite]
 |-- UI / UX 
 |-- Форми логіну/реєстрації 
 |-- Пошук і фільтри 
 |-- Кошик, кнопки “Додати/Видалити” 
 |-- Відображення карток, фото, відгуків 
 | 
 | HTTP requests (GET/POST/PUT/DELETE) 
 v 
 [Backend: Node.js + Express] 
 |-- Auth / Users 
 | |-- зберігання користувачів, хешування паролів, JWT 
 | 
 |-- Search & Filter 
 | |-- обробка запитів до БД, повернення відфільтрованих результатів 
 | 
 |-- Shopping Cart / Orders 
 | |-- створення замовлень, перевірка наявності, історія покупок 
 | 
 |-- Payments 
 | |-- інтеграція з Stripe/PayPal, підтвердження оплати 
 | 
 |-- Reviews / Ratings 
 | |-- збереження оцінок і відгуків, обчислення середнього рейтингу 
 | 
 | SQL queries 
 v 
 [Database: MySQL] 
 |-- Таблиці: Products, Users, Orders, Reviews, Photos
1. # Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

   node index.js --action="list"
   посилання - https://ibb.co/zxK5vqW

2. Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.
   node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6
   посилання - https://ibb.co/sgKkT3L

3. Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту
   node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22
   посилання - https://ibb.co/TmbmQc5

4. Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.
   node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH
   посилання - https://ibb.co/CMN5yK7

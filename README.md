# Test-task-plugin

Для початку потрібно перенести папку з плагіном в каталог wp-content/plugins/
Далі в WP на сторінці встановлених плагінів з'явиться цей плагін, працювати він буде якщо перед цим був активован плагін Woocommerce.
Працює плагін як і було описано в завданні, тобто на сторінці "My account" в меню сторінок додаються 2 нові сторінки, Add product, My products. На сторінці "Add product" можна буде додати новий товар за заповненими полями,що були вказані в тестовому завданні, а на "My products" буде таблиця зі списком усіх наявних товарів, зі всіма потрібними полями з тестового завдання, включаючи кнопки "Edit", "Delete". Єдине, не встиг зробити нормальну пагінацію між сторінками товарів. Також при створені товару на пошту має приходити лист за шаблоном з тестового завдання, але цю фічу не тестував, так як працював на локальному сервері.


P.S. Якщо при активації плагіну при переході на нові сторінки "Add product", "My product", сайт не зможе розпізнати url сторінок і буде видавати помилку, що таких сторінок на сайті не існує, треба зайти в Налаштування ссилок в ВП та оновити їх.

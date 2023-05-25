# Microservice-ASP.NET-Core
Микросервис  с использованием ASP.NET Core 2.1 и Visual Studio 2017
Служба запускается через IIS Express, т. е. по умолчанию в Visual Studio.
Приложение будет запущено после запуска страницы браузера.
Поскольку ему нечего показывать, оно будет пустым, но сервис можно протестировать с помощью любого клиента тестирования API. 
Postman используется для тестирования конечных точек службы. Держите его открытым и работающим приложением.

Чтобы протестировать метод POST, выберите метод POST в Postman и укажите конечную точку,
то есть https://localhost:port/api/product, и в разделе Body добавьте JSON,
аналогичный свойствам модели продукта и нажмите Отправить.Аналогично можно протестировать другие методы GET,PUT,DELETE.

Пример
 Метод POST    http://localhost:port/api/product

body:
   {
        "name": "Iphone13",
        "description": "AppleMobile",
        "price": 80000.00,
        "categoryId": 1
    }

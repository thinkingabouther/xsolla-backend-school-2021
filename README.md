# Xsolla Summer School 2021. Backend

Привет! Это небольшое тестовое задание, которое не должно занять много твоего времени. 
Исходя из качества его выполнения мы сможем понять, будет ли наш поток достаточно продуктивным для тебя.

Задание состоит из двух частей: обязательной и дополнительной. 
Твоя задача - полностью выполнить обязательную часть и попробовать свои силы в заданиях дополнительной части. Скорее всего, для выполнения дополнительных заданий тебе потребуется самостоятельно ознакомиться с темами, важными для backend-разработчиков.

Желаем успехов!

## Обязательная часть

**Бриф**: Необходимо реализовать систему управления данными для площадки онлайн-коммерции. 

Потеницальный партнер, разработавший клиентскую часть онлайн-площадки для продажи внутриигровых товаров, хочет получить [RESTful API](https://ru.wikipedia.org/wiki/REST) для управления данными. Для этого ему понадобятся следующие методы:
- Методы для управления **товарами** ([CRUD операции](https://ru.wikipedia.org/wiki/CRUD)). Товар определяется уникальным идентификатором и обязательно должен иметь имя, тип и цену. Необходимо обязательно реализовать следующие [REST методы](https://restfulapi.net/http-methods):
  - **Создание товара**. При создании товара должен генерироваться и возвращаться уникальный идентификатор.
  - **Редактирование товара**. Необходима возможность изменения всех данных о товаре по его идентификатору.
  - **Удаление товара** по его идентификатору. 
  - **Получение информации о товаре** по его идентификатору.
  - **Получение каталога товаров**. Метод не имеет входных параметров, с его помощью можно получить список всех добавленных товаров. Товаров может очень много, необходимо обеспечить возможность выдачи товаров "по частям".
- [README](https://techrocks.ru/2019/04/16/good-readme-on-github/) для твоего репозитория с указанием последовательности действий для запуска и локального тестирования API. Так же можно отметить при помощи ссылок на файлы и строчки кода те места реализации, которые ты считаешь наиболее значимыми

Мы ждём от тебя ссылку на GitHub с реализацией поставленной задачи. Ты можешь использовать любой язык и фреймворк, 
но проверяющим будет приятно, если это будет PHP, GoLang, или Node.js (в Иксолле как раз пишут на этих языках).

## Дополнительная часть

Cписок возможных доработок решения, выполненного в рамках обязательной части:

- Возможность фильтрации товаров в методе получения каталога товаров.
- Метод приобретения единичного товара. В качестве входных данных принимает идентификатор приобретаемого товара и записывает факт приобретения.
- Метод получения списка наиболее продаваемых товаров на основе данных о приобретенных товарах.
- [OpenAPI (Swagger)](https://starkovden.github.io/introduction-openapi-and-swagger.html) спецификация для разработанного REST API.
- [Dockerfile](https://www.youtube.com/watch?v=QF4ZF857m44) для создания образа приложения.
- Docker-compose файл.
- Модульные и интеграционные тесты. 
- Развертывание приложения на любом публичном хостинге (можно посмотреть в сторону бесплатного [heroku](https://www.heroku.com/)).

Необязательно выполнять все пункты дополнительной части (на то она и дополнительная :). Выполнение любого из предложенных пунктов поможет выделить твою работу для проверяющего.

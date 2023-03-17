"# Фитнес студия"
#Функционал построен на взаимодествии сущностей "User" и "Product".
#В проекте использованы возможности фреймворка Spring Boot.
#Для функционирования приложения  использованы сервисы, необходимые для создания и управления сущностями: "User" и "Product" и другие для организации их взаимодествия.

#User
#/api/v1/users Добавление нового пользователя (GET)
#/api/v1/users Получить страницу пользователей (POST)
#/api/v1/users/{uuid} Получить информацию о пользователе (GET)
#/api/v1/users/{uuid}/dt_update/{dt_update} Редактировать информацию о пользователе (PUT)

#Product
#/api/v1/product Добавление нового продукта (POST)
#/api/v1/product Получить страницу продуктов (GET)
#/api/v1/product/{uuid}/dt_update/{dt_update} Редактировать информацию о продукте (PUT)
#/api/v1/recipe Добавление нового рецепта (POST)
#/api/v1/recipe Получить страницу рецептов (GET)
#/api/v1/recipe/{uuid}/dt_update/{dt_update} Редактировать информацию о рецепте (PUT)

#Реализация проекта в DOCKER
#Computed URL:http://localhost:8080
#Планируется, что в данном приложении будут использованы функционалы аудита и репорт сервисов. Срок реализации 15.04.2023.
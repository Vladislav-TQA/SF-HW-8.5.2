# SF-HW-8.5.2.
Сценарное тестирование REST API в рамках коллекции:
1. Пользователь получает ключ API.
2. Пользователь добавляет питомца. 
3. Пользователь проверяет, что питомец добавился.
4. Пользователь удаляет питомца.
5. Пользователь проверяет, что питомец удалён.
 
 Перечень переменных для коллекции:
auth_key;
base_url;
name;
age;
type;
petid.

![image](https://user-images.githubusercontent.com/110028579/184647922-68eca1a2-bb10-4b7a-8649-e67f185000a2.png)


 Шаги:
1. Настройки авторизации — через API Key в заголовках. Значение самого ключа будет подгружено из переменных, созданных в ходе теста.

![image](https://user-images.githubusercontent.com/110028579/184644669-b41e815c-f909-484a-af97-417e6245bd38.png)

2. Отправляем GET запрос на получение api key

![image](https://user-images.githubusercontent.com/110028579/184645220-979e26c5-bf23-49b4-a2d4-319454d7ebce.png)

3. Отправляем запрос POST, на добавление карточки питомца

![image](https://user-images.githubusercontent.com/110028579/184648999-d48b5da1-710c-46e5-a973-f7364a50e6c5.png)

4. GET запрос на проверку добавленной карточки

![image](https://user-images.githubusercontent.com/110028579/184649596-43f553f8-0aed-496d-9484-91d94bc2ad8d.png)

5. Запрос DELE на удаление добавленной карточки

![image](https://user-images.githubusercontent.com/110028579/184650807-31ee9294-2f34-4c9b-9a93-b9e3fdd1968b.png)

6. GET запрос на проверку, что карточка удалена

![image](https://user-images.githubusercontent.com/110028579/184651166-b6ad8a70-ca72-4219-b11b-a5ead4694eca.png)

Тесты:

1.

![image](https://user-images.githubusercontent.com/110028579/184652106-901295cb-5c74-4532-b7e7-b440806840b2.png)

2.

![image](https://user-images.githubusercontent.com/110028579/184652200-ef6c779d-bdd4-41b9-a259-c560930e3717.png)

3.

![image](https://user-images.githubusercontent.com/110028579/184652283-f9983f95-c9b8-496d-8892-91e159112a3e.png)

4.

![image](https://user-images.githubusercontent.com/110028579/184652393-e746e13a-50cf-495b-a56a-d51c47b384b5.png)

5.

![image](https://user-images.githubusercontent.com/110028579/184652510-729772c8-b424-4c35-8243-1fa1b2f64f25.png)






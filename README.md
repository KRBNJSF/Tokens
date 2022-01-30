# Tokens

npm i<br>
npm i jsonwebtoken bcryptjs<br>
npm init -y

Vytvořím nodemon.json k úschově přihlašovacích údajů k databázi

nodemon.json -> 
```
{
    "env": {
        "MONGODB_PW": "123admin",
        "TOKEN_KEY": "anoano"
    }
}
```
Příhlásím se na mongodb.com<br>
Vložím z <a href="https://cloud.mongodb.com/v2/61a5e823aeeee4739fac3010#security/database/users">MongoDB</a>

Do index.js :
```
mongodb+srv://rubes999:<password>@cluster0.jddan.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
```
![image](https://user-images.githubusercontent.com/90755554/150764722-1969a07f-af43-4a7b-bf4e-951d44c6418e.png)
Ověření funkčnosti přes postman
---
Zaregistruji se a nechám si vytvořit token:
![image](https://user-images.githubusercontent.com/90755554/150765261-78d4a928-3d02-4fdf-9efe-1450fea08670.png)
Token vložím do Key
![image](https://user-images.githubusercontent.com/90755554/150765311-026818eb-ca53-41da-9d93-9472d0ce257c.png)

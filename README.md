# Infinite-Scrolling
Infinite scrolling to load data from the backend as the scrollbar reaches the bottom of the web page, it will show "LOADING..." while fetching data from database.
## Tech Stack
- Front-end: HTML , CSS , JavaScript
- Back-end : NodeJS , ExpressJS
- DataBase : MySQL

## Setting Up
- Clone the project
  ```
    https://github.com/1simransaini/Infinite-Scrolling.git
  ```
- Install Dependencies
- Make a .env file, also make sure to add .env file in the root folder
- Template of .env file
```
  DB_PORT=<Here write your database port number>
  host=localhost
  database=<Write your Database name>
  user=<Write username>
  password=<password of user>
  SERVER_PORT=<Write Server Port Number>
```

- Run as:
  ```
    nodemon server/app.js
  ```
  OR
  ```
    node server/app.js
  ```

![Screenshot (14234)](https://github.com/1simransaini/Infinite-Scrolling/assets/91106038/6df979b9-d710-41bb-8ff2-5b7efd628e60)

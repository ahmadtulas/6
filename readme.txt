create a folder

npm init // to make the project intialization

npm install express --save // to install express.js dependency

npm install sequelize --save // sequelize for connection with database

npm install pg --save // driver for postgre

npm install sequelize-cli --save-dev // sequelize cli for comnand line operation

npx sequelize-cli init // for folder structure

// after set the proper configuration of db we can used sequelize-cli for database creation.

npx sequelize-cli db:create // it will create the database. 


node index.js // to start the server

//Now to generate a model using squelize-cli  we can used below mentioned command
npx sequelize-cli model:generate --name Todo --attributes title:string,dueDate:dateonly,completed:boolean

// now to create table using model we can used sequelize command
npx sequelize-cli db:migrate

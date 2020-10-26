#Delilah Resto

This project proposes the creation of an online ordering system for a restaurant. REST API that allows you to add, cancel, modify and obtain information about a data structure that a client could consume.

## Resources


- Node.js
- Nodemon
- Express
- JWT para autenticación via Token
- MySQL
- Sequelize
- Postman for endpoints testing
- Swagger to document API


## API Docs

Go to [Swagger](https://editor.swagger.io/) , then import `documentation.yaml`


### Installing and Starting the project

1 - Clonar proyecto
```
git clone https://github.com/SalgueroAgus/Delilah-resto
```
 2 - Instalación de dependencias
```
npm install
```
3 - Create DB 
```
- Open XAMPP on port  `3306`
- Start  MySQL service
- Generate a new database called `delilah_resto` from the control panel
- Open the file in `/ database / queries.sql` and inside the` control panel` of the           database execute the series of queries from the file or import it.
```
4 - Start server
```
cd to `/server` 
run `nodemon server.js` from console
```
5- Ready to use

Go to [Postman Collection](https://documenter.getpostman.com/view/12669841/TVYGax9u) to test endpoints.

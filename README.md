A aplicação permite que você se cadastre como cliente ou barbeiro. Como cliente, é possível marcar horários com os barbeiros cadstrados. Como barbeiro, você pode verificar os agendamentos do dia.

Foi utilizado: Docker com PostgreSQL, NodeJS, Nunjucks e estruturada no padrão MVC. 

Para utilizar é preciso utilizar: 
```
 docker run --name gonodemodulo2 -e POSTGRES_PASSWORD=docker -d postgres.
 ```
 Iniciar o container do Docker com docker start gonodemodulo2.

Após isso, instalar as dependencias com:
```
npm install
```


Executar as migrations: 
```
npx sequelize migration:create --name=create-users ```
```npx sequelize migration:create --name=create-appointments
 ```

Executar com 

```
npm start
```



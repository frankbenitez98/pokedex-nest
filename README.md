<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1.  Clonar el respositorio

2.  Ejecutar

```
yarn install
```

3.  Tener Nest CLI instalado

```
 npm i -g @nest/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. clonar el archivo **.env.example** y renombrarlo como **.env**

6. ejecutar la aplicacion con:

```
yarn start:dev
```

7. Rebuild the data base with the seed.

```
http://localhost:3000/api/seed
```

## Stack Usado

- mongoDB
- NestJS

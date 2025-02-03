```bash
nom init -y 
npm i -D typescript tsx @types/node
npx tsc --init

npm i express
npm i -D @types/express

npm i -D @swc/core @swc/cli

## descargar dependencia de prima 
npm i prisma @prisma/client

## inicializar prisma 
npm prisma 

## para encriptar las contraseñas
npm i bcrypt
npm i -D @types/bcrypt

## libreria JsonWebToken
npm i jsonwebtoken
npm i -D @types/jsonwebtoken

##SEGURIDAD
## limite de intentos en el login
npm i express-rate-limit
## protege de la mayoria de ataques conocidos
npm i helmet
## 
npm i compression

## para trabajar con cookies
npm i cookie-parser

## dependencia de cors
npm i cors
npm i --save-dev @types/cors

## para validar TODO 
npm i express-validator

# instalar ncu 
npm install -g npm-check-updates
## comprueba las dependencias que tienen nuevas versiones
npx npm-check-updates
## actualiza las dependencias
npx npm-check-updates -u
```


Ejercicio 1:
    Crear endpoint que liste todos los usuarios de la web
    A ese endpoint solo puede acceder el usuario role = admin
    Crear rutas, servicios, controllers, middleware 

Ejercicio 2:
    Valida mediante un middleware
    El formulario de registro:
        - comprueba que el email sea válido
        - comprueba que el password se de mínimo 4 letras

Ejercicio 3:
    Crea el fronted con Vite + tailwind 4.0 + react
# config-nest-prettier-eslint

This repository provides the necessary configuration files to set up **Prettier** and **ESLint** for **NestJS** projects. It also includes dependencies for **Swagger**, **JWT Authentication**, **TypeORM**, and **Config Module** to enhance your NestJS development environment.

## Dependencies

To install the required packages, run the following commands:

1. **ESLint & Prettier Configuration**: These tools ensure consistent code formatting and style across your NestJS project.
    ```bash
    npm install --save-dev eslint prettier eslint-plugin-prettier eslint-config-prettier
    ```

2. **Swagger for API Documentation**: Integrates **Swagger** into your NestJS project, allowing you to easily document your API endpoints.
    ```bash
    npm install @nestjs/swagger swagger-ui-express
    ```

3. **JWT Authentication**: These packages provide support for **JSON Web Tokens (JWT)**, allowing you to implement authentication and authorization in your NestJS app.
    ```bash
    npm install @nestjs/jwt passport passport-jwt
    ```

4. **TypeORM for Database Integration**: Install **TypeORM** and **PostgreSQL** driver to enable database interactions using **TypeORM** in your NestJS application.
    ```bash
    npm install @nestjs/typeorm typeorm pg
    ```

5. **NestJS Config Module**: This module allows you to manage configuration variables from `.env` files, enabling better environment management for different stages (development, production, etc.).
    ```bash
    npm install @nestjs/config
    ```
    
6. Configuring Prettier and ESLint**

To ensure consistent code formatting across your project, follow these steps to configure **Prettier** and **ESLint**:

1. **ESLint Configuration**: Add the following rule to the ESLint configuration file (`.eslintrc.js` or equivalent) to enforce automatic line endings:

   Add in extens
   ```bash
   'nestjs'

   Add in rules:
   ```bash
   'prettier/prettier': ['error', { 'endOfLine': 'auto' }]

1. **Pretier Configuration**: Add the following config in to the .prettierrc file (`.eslintrc.js` or equivalent) :

   ```bash
   {
   'singleQuote':true,
   'trailingComa':"all",
   'endOfLine': 'auto'
   }


This setup will help you maintain high-quality, well-documented, and scalable NestJS applications.

The simple Rest API application example build on [Symfony 4](https://symfony.com/) framework.

## Installation
### 1. Clone repository
```bash
git clone https://github.com/romfizz898/SF4REST
```
### 2. Dependencies installation
Install project dependencies with composer using the following command in the project folder
```bash
composer install
```
### 3. Configuration
Use this command to copy the environment variables settings file.
```bash
cp .env.dist .env
```
Then, open .env file and enter database credentials.

Run 
```bash
php bin/console doctrine:schema:create
```
 to create necessary database structure.



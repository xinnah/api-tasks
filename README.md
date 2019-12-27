
## Getting started

### Installing
```bash

- Clone Repository.
- Run composer install.

# Generate key
php artisan key:generate.

## Migration and DB seeder (after changing your DB settings in .env)

* If PHP Version is v7.2 or higher then you can run
# Migration and DB seeder and server run
php artisan wild:card

* Else
php artisan migrate --seed
php artisan serve

## System Login Info
- email - admin@gmail.com 
- password - 123456

* After successfully login you can copy then token. Because token are mandatory for access request.    


## API endpoint list

| HTTP method   | URI path      | Description |
| ------------- | ------------- | ------------- |
| POST | http://127.0.0.1:8080/api/login |   
| GET  | http://127.0.0.1:8080//api/tasks |  Get all the Tasks list of the store. |
| GET  | http://127.0.0.1:8080//api/tasks?tasks=1,2 |  Get one or more specific Tasks from the store. |
| POST | http://127.0.0.1:8080//api/tasks |  Save a task in the store. |
| PUT  | http://127.0.0.1:8080//api/tasks/1 | Update a task in the store. |


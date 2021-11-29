create the dockerfiles and run project:
- `docker-compose up -d --build`

containers port detail:
- **nginx** - `:8000`
- **mysql** - `:3306`
- **php** - `:9000`
- **redis** - `:6379`
- **phpmyadmin** - `:8080`

Composer, NPM, and Artisan commands Use the following command examples :

- `docker-compose run --rm composer install`
- `docker-compose run --rm artisan migrate`
- `docker-compose run --rm npm run dev`


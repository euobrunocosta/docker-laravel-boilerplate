# Docker Laravel Bolier Plate

- Create your laravel project

- Clone laradock on your project root directory

```shell
git submodule add https://github.com/Laradock/laradock.git
```

- Inside the `laradock` folder, copy the `env-example` to a `.env` file

```shell
cp ./laradock/env-example .env
```

- Edit the variables you want

- Run build and run the containers you want

```shell
sudo docker-compose up -d nginx mysql phpmyadmin  
```

- To enter the `workspace` container

```shell
sudo docker-compose exec --user=laradock workspace bash
```
# WordPress + MySQL + PMA Docker Compose

This is a simple Docker Compose example for setting up local WordPress with PMA and MySQL.

## Stack

- WordPress 6.4.3
- PMA (latest)
- MariaDB 10.6.4

## Setup

1. Clone the repository: `git clone https://github.com/recoskyler/wordpress-docker-compose && cd wordpress-docker-compose`
2. Create a `.env` file: `cp sample.env .env`
3. Create a directory named `ai1wm-backups` if it does not exist
4. Move your **All-in-one WP Migration** `.wpress` backup file(s) to the newly created `ai1wm-backups` directory
5. Run the containers: `docker compose up -d`
6. Open [the admin panel](http://localhost:8080)(<http://localhost:8080>) and install the **All-in-one WP Migration** plugin
7. Follow the steps [here](https://gist.github.com/giovanni-d/f9a05638e0b31467762b71585e8c3bfa) to allow backup restore

## About

By [recoskyler](https://github.com/recoskyler) - 2024


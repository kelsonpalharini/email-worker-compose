<h1 align="center">Email Worker</h1>

<p align="center"> A simple example using docker with docker-compose.
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Built Using](#built_using)

## 🧐 About <a name = "about"></a>

I created this example to deepen my comprehension of Docker with this course at Udemy:

[Docker: Ferramenta essencial para Desenvolvedores(Docker: Essential tool for developers)](https://www.udemy.com/course/curso-docker/)

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

- First install [Docker](https://docs.docker.com/install/);
- After install [Docker Compose](https://docs.docker.com/compose/install/);

- And last you have to clone this repo in your machine with:

```
git clone https://github.com/kelsonpalharini/email-worker-compose.git
```

### Running

Access the project folder and run:

```
docker-compose up -d
```

And if you want to see all logs run:

```
docker-compose logs -f -t
```

And if nothing wrong happens, you can access this project by [http://localhost:80](http://localhost:80).

## ⛏️ Built Using <a name = "built_using"></a>

- [Docker](https://www.docker.com/) - Containers
- [Redis](https://redis.io/) - Message Broker
- [Python](https://www.python.org/) - Development
- [PostgreSQL](https://www.postgresql.org/) - Database
- [NGINX](https://www.nginx.com/) - Web Server

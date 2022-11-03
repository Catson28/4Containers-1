# <p align="center"><a href="https://www.facebook.com/felicianofranciscocandieiro.catson" target="_blank">Contact System</a></p> 



<p align="center">
<a href="https://www.facebook.com/felicianofranciscocandieiro.catson"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://www.facebook.com/felicianofranciscocandieiro.catson"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://www.facebook.com/felicianofranciscocandieiro.catson"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://www.facebook.com/felicianofranciscocandieiro.catson"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

Um sistema que permite enviar emails a empresa e esta por sua vez receber e retornar uma resposta de forma automatica. 

## Tecnologias utilizadas

Para este trabalho simples utilizou-se

- **[Docker](https://www.docker.com/)**
- **[Django](https://www.djangoproject.com/)**
- **[Postgresql](https://www.postgresql.org/)**

o projecto esta parcialmente completo, mas fica para terefa estudar outras formas de implementar a dependencia smtplib que permite enviar emails

- ``docker-compose run app pip install --upgrade pip && pip install secure-smtplib``

## Instacacao

- ``git clone https://github.com/Catson28/Contact-System-_-Django-Postgrees-Docker.git``

- ``cd Contact-System-_-Django-Postgrees-Docker``
- ``docker-compose build``
- ``docker-compose up``

# Currency-Exchange
>App Conversao de Moeda, utilizando a api [Fixer.io](http://fixer.io/)

![ruby](https://img.shields.io/badge/Ruby-2.3-red.svg).
![rails](https://img.shields.io/badge/Rails-5.0.1-red.svg).
![docker](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg).

### [Acesse o app online](https://currency-exchange-one.herokuapp.com/)

Este e um app de Conversao de Moeda, que foi desenvolvido no curso Bootcamp Super Full Stack da One Bit Code [site](https://onebitcode.com).

![Currency-Echange](https://github.com/jorgemtoledo/currency_exchange/blob/master/public/image.png).

Nesse app de conversao de moeda, o usuario precisa escolher a moeda local ou de destino, quantidade e depois escolher para qual moeda vai precisar a converter.

## Requisitos
- SO (Windows, Mac OS ou Linux)
- Docker
- Clonar o projeto numa pasta em sua maquina

## Instalacao
```
docker-compose build
docker-compose run --rm website rails db:create db:migrate
docker-compose up
```
Acesso o app na url localhost:3000.

# Temii

[![Join the chat at https://gitter.im/DjangoQuilla/temii](https://badges.gitter.im/DjangoQuilla/temii.svg)](https://gitter.im/DjangoQuilla/temii?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/DjangoQuilla/temii.svg?branch=master)](https://travis-ci.org/DjangoQuilla/temii)

Aplicación para escoger los futuros temas y talleristas para las charlas de la comunidad Django Barranquilla.

## Requerimientos

 * [Python 2.7.x](https://www.python.org/)  
 * [PIP](https://pypi.python.org/pypi/pip)
 * [Virtualenv + VirtualenWrapper](https://pypi.python.org/pypi/virtualenv)
 * [Django 1.8.7](https://www.djangoproject.com/)
 * Editor de texto (Sublime Text, Atom, etc)

## Contribuciones

Necesitamos de tu ayuda para terminar este proyecto! **¿Cómo puedes contribuir?** Mira las normas que hemos redactado en el archivo [CONTRIBUTING.md] para organizarnos mejor en el desarrollo. Esperamos tus Pull Requests e Issues. Gracias por tu apoyo.

Agradecimientos a los [autores](AUTHORS.md) de temii

[CONTRIBUTING.md]: https://github.com/DjangoQuilla/temii/blob/master/CONTRIBUTING.md

## Instalación

### Instalar pyenv
[https://github.com/pyenv/pyenv/blob/master/README.md](https://github.com/pyenv/pyenv/blob/master/README.md)

### Crear virtualenv

```
pyenv virtualenv temii
pyenv activate temii
```

### Instalar dependencias

Para instalar las dependencias se manejan 3 entornos: local, test y producción

#### Entorno local (sqlite)

```
pip install -r requirements/local.txt
```

#### Entorno producción (postgresql)

```
pip install -r requirements/production.txt
```

#### Entorno testing

```
pip install -r requirements/test.txt
```

#### Meetup API
[Generar llave](https://secure.meetup.com/es-ES/meetup_api/oauth_consumers/create/)

Exporta tus llaves usando las siguientes variables de entorno

```
export SOCIAL_AUTH_MEETUP_KEY=
export SOCIAL_AUTH_MEETUP_SECRET=
```

##### Licencia

[Apache License 2.0](LICENSE)

# Awesome-Starlite

Curated List of Starlite Resources: A high performance ,secure, well architected , highly productive  python async web framework

## [Starlite](https://github.com/starlite-api/starlite/blob/main/README.md)

Starlite is a powerful, performant, flexible and opinionated ASGI framework,
offering first class typing support and a full [Pydantic](https://github.com/samuelcolvin/pydantic)
integration.

Check out the [documentation 📚](https://starlite-api.github.io/starlite/).## Starlite

### Installation

```shell
pip install starlite
```

### Quick Start

```python
from starlite import Starlite, get


@get("/")
def hello_world() -> dict[str, str]:
    """Keeping the tradition alive with hello world."""
    return {"hello": "world"}


```

## Starter Templates

### Easy Starters

* [starlite-halfstack-cookiecutter](https://github.com/v3ss0n/starlite-halfstack-cookiecutter)
  Simpilfied version of official pq starter [starlite-api/starlite-pg-redis-docker](https://github.com/starlite-api/starlite-pg-redis-docker/blob/main/static/starlite-banner.svg) , by using https://github.com/topsport-com-au/starlite-saqlalchemy lib

* [JeromeK13/starlite-minimal-starter](https://github.com/JeromeK13/starlite-minimal-starter)
  
  Bare minimal Cookie Cutter

### Full Stack

* [starlite-fullstack](https://github.com/cofin/starlite-full-stack-example)
  Full stack backend and Vue frontend  .

* [starlite-api/starlite-pg-redis-docker](https://github.com/starlite-api/starlite-pg-redis-docker/)

  Full featured  [Starlite](https://github.com/starlite-api/starlite) project using SQLAlchemy + Alembic + postgresql, Redis, SAQ and Docker.

* [starlite-piccolo](https://github.com/sinisaos/starlite-piccolo/tree/main/backend)

  Fullstack starter template for starlite with Piccolo ORM.

### Minimal


* [starlite-api/starlite-hello-world](https://github.com/starlite-api/starlite-hello-world)

  Minimal starter  template for starlite.


* [lesnik512/starlite-sqlalchemy-template](<https://github.com/lesnik512/starlite-sqlalchemy-template>)
  
  Docker ready Starlite template


## Examples

* [Starlite-Tile38](https://github.com/iwpnd/starlite-tile38)
  
  GPS/GIS exmaple using route38 and starlite

## User management and Auth

* [starlite-users](https://github.com/LonelyVikingMichael/starlite-users)
  
  User and Auth features for starlite with builtin support for :
  * Session, JWT and JWTCookie , Role based Guards
  * Routes For Authentication,Registration,Verification,Password reset, User CRUD , Role CRUD, Assignment/revocation of roles to/from users

## Utilities

* [starlite-saqlalchemy](https://github.com/topsport-com-au/starlite-saqlalchemy)
  
  Starlite API boilerplate abstraction and utilities.

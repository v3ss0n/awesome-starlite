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

### [Minimal CookieCutter](https://github.com/JeromeK13/starlite-minimal-starter)

Bare minimal Coockie Cutter

### [Starlite Template with Docker Builtin](https://github.com/lesnik512/starlite-sqlalchemy-template)

### [starlite-pg-redis-docker](https://github.com/starlite-api/starlite-pg-redis-docker/blob/main/static/starlite-banner.svg)

This is an example [Starlite](https://github.com/starlite-api/starlite) project using SQLAlchemy + Alembic + postgresql,
Redis, SAQ and Docker.

### [starlite-hello-world](https://github.com/starlite-api/starlite-hello-world)

Minimum starter template for starlite.

### [starlite-fullstack](https://github.com/cofin/starlite-full-stack-example)

Full stack both frontend and backend .
Frontend in Vue .

## Examples

[Starlite-Tile38](https://github.com/iwpnd/starlite-tile38)

[Strlite-Sqlalchemy](https://github.com/topsport-com-au/example-starlite-saqlalchemy)

## User Auth and CRUD

### [CRUD](https://github.com/topsport-com-au/starlite-saqlalchemy)

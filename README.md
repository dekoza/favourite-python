# favourite-python

My highly opinionated list of favourite Python libraries. In each case I'll do my best to provide a short comparison with alternatives. Inspired by [awesome-python](https://awesome-python.com/) and similar lists.

No particular order at the moment, this will probably change in future.

* [Django](https://djangoproject.com/) - current king of Python web frameworks.
* [FastAPI](https://fastapi.tiangolo.com/) - best microframework, hands down. I used Flask and Sanic in the past.
* [Typer](https://typer.tiangolo.com/) - [Click](https://click.palletsprojects.com/) but nicely wrapped.
* [Asyncer](https://asyncer.tiangolo.com/) - small wrapper for anyio.
* [Poetry](https://python-poetry.org/) - dependency management and packaging in elegant form.
* [PonyORM](https://ponyorm.org/) - the most pythonic ORM there is. You literally write queries by writing lambdas and generators. Produces incredibly optimized SQL. Cons: no migrations, no async.
* [Pendulum](https://pendulum.eustace.io/) - best transparent (drop-in) datetime replacement. I used Arrow before but it didn't handle DST correctly and wasn't transparent.
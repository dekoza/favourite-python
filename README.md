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
* [Strawberry](https://strawberry.rocks/) - the only code-first GraphQL library that is inspired by dataclasses and is async. Looks like perfect match for FastAPI. Other libs might be more popular but are schema-first and I dislike this approach as not DRY enough.
* [Saleor](https://saleor.io/) - GraphQL-based headless eCommerce platform.
* [Rich](https://rich.readthedocs.io/) - give your CLI a bit of colour.
* [Textual](https://github.com/Textualize/textual) - Text User Interface framework built around Rich.
* [PikePDF](https://github.com/pikepdf/pikepdf) - most feature-rich PDF manipulation library for Python.
* [Diagrams](https://diagrams.mingrammer.com/) - cloud architecture diagrams as code; clever use of bitshift operator 🤔
* [Pint](https://pint.readthedocs.io/en/stable/) - unit convertion made trivial
* [Mutatest](https://github.com/EvanKepner/mutatest) - mutation testing for Python

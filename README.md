```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Hasindu Senarathne"
    designation : str = "Data Scientist n Developer"
    company     : str = "Lazuno"
    base        : str = "Warakapola , Sri Lanka "
    blog        : str = "----------------------"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "Go", "Shell","rust","java","php","html","css","js")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL", "Mongo", "Redis")
    misc        : Tuple[str, ...] = ("Docker", "Celery")
    ongoing     : Tuple[str, ...] = ("Django", "GraphQL")


class Social(metaclass=Meta):
    twitter     : str = "Hasinduse"
    linkedin    : str = "Hasindu Senarathne"
```

⭐️ From [Hasindu](https://github.com/hasiya2004)

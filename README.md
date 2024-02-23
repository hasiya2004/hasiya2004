```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Hasindu Senarathna"
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
<!--tech stack icons-->
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,aws,bootstrap,c,cpp,css,discord,docker,dynamodb,express,figma,firebase,github,html,idea,java,js,kotlin,linux,md,materialui,mongodb,mysql,nextjs,nodejs,postman,py,react,redux,tailwind,ts,vscode&perline=14" />
  </a>
</p>

⭐️ From [Hasindu](https://github.com/hasiya2004)

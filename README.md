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
<!--icons and links-->
<p align="center">
<a href="https://www.linkedin.com/in/1010nishant/" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234979284-68c11d7f-1acc-4f0c-ac78-044e1037d7b0.png" alt="linkedin" height="50" width="50" /></a>
<a href="https://twitter.com/1010nishant" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234980676-61bfb021-ecc8-48f7-88e6-34c1b06c4a58.png" alt="twitter" height="50" width="50" /></a> 
<a href="https://www.instagram.com/nishant.jangir.1010/" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234981169-2dd1e58f-4b7e-468c-8213-034ba62156c3.png" alt="instagram" height="50" width="50" /></a>
<a href="https://1010nishant.hashnode.dev/" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234982196-562aea17-5532-4550-8c08-1c7cb994a541.png" alt="hashnode" height="50" width="50" /></a>
<a href="https://discord.gg/UjwKkJsXsf" target="blank"><img align="center" src="https://user-images.githubusercontent.com/88904952/234982627-019fd336-6248-453c-9b05-97c13fd1d207.png" alt="discord" height="50" width="50" /></a>
  
</p>

⭐️ From [Hasindu](https://github.com/hasiya2004)

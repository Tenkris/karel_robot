# Documentation

## Installation

- create virtual environment

```bash
virtualenv venv
```

- activate virtualenv

```bash
source venv/bin/activate
```

- install requirements

```bash
pip install -r requirements.txt
```

Follow the Karel tutorial on the
[Karel Reader!](https://compedu.stanford.edu/karel-reader/docs/python/en/intro.html)

## Running Karel

First, ensure that StanfordKarel is correctly installed using pip.
Any `.py` file can become a Karel program!

**Q1_First_karel.py**

```python
from karel.stanfordkarel import *

def main():
    pass

if __name__ == "__main__":
    run_karel_program("First_karel.w")


```

Save the file and run:

```
python Q1_First_karel.py
```

## Available Commands

| Karel Commands       |                        |                          |
| -------------------- | ---------------------- | ------------------------ |
| `move()`             | `right_is_clear()`     | `facing_east()`          |
| `turn_left()`        | `right_is_blocked()`   | `not_facing_east()`      |
| `put_beeper()`       | `beepers_present()`    | `facing_west()`          |
| `pick_beeper()`      | `no_beepers_present()` | `not_facing_west()`      |
| `front_is_clear()`   | `beepers_in_bag()`     | `facing_south()`         |
| `front_is_blocked()` | `no_beepers_in_bag()`  | `not_facing_south()`     |
| `left_is_clear()`    | `facing_north()`       | `paint_corner(color)`    |
| `left_is_blocked()`  | `not_facing_north()`   | `corner_color_is(color)` |

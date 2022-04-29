# A Better Wiki: Markdown+git
> plus the help of Mkdocs material give extra super powers

To see all that you can do with Mkdocs+material check out [here](https://squidfunk.github.io/mkdocs-material/reference/)

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## things...

Here is a code block of yaml with an annotation
```yaml
rejection_reasons
    - violates policy a
    - violates policy b # (1)
    - violates policy c
```

1. this is a markdown annotation that supports `markdown` __stuff__ :sunglasses:

Here is a python snippet, you can include/exclude line numbers and highlight certain lines

```py hl_lines="2 3"
def do_something():
    calculate_items()
    purchase_food()
    eat_food()
    validate_things()

```

you can even embed actual file snippets as code blocks:

``` py
--8<-- "example.py"
```
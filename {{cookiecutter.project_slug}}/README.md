# Render Engine `BasePageParser`

## Installation
You can install this using pip

```sh
pip install {{cookiecutter.project_slug}}
```
{% if frontmatter %}
## Using Frontmatter

[Frontmatter](https://github.com/eyeseast/python-frontmatter) is used to pull in attributes from a generated page.

Some pages will be looking for information that is provided in the frontmatter. All of the attributes defined can be used in the template (which itself can also be defined in the frontmatter or the class itself.

> **NOTE**
> These attributes **CANNOT** be used in the content itself, but you can use them in the template generation.

{% endif %}

## Parsing the Data

The base parser doesn't is a pass-thru parser meaning the content input will be passed through.

```md
# TODO: EXAMPLE OF HOW YOUR DATA IS PARSED
```

If you generate the page with the following template

```html
<div>
# TODO: EXAMPLE OF A TEMPLATE
</div>
```

it would generate.

```html
# TODO: EXAMPLE OF A GENERATED REPORT
```

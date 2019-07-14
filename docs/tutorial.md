# Tutorial

## Liquid

### Object

- location to output contnet    
- `{{page.title}}`

### Tags

- create control flow for templates

```ruby
{% if page.show_sidebar %}
{% endif %}
```

### Filters

- Change the output of liquid object
- `{{"hi" | capitalize }}

## Front Matter

- Snippet of YAML
- Set variables for the page
- Avaliable under `page`
S
```
---
var: 5
---
```

## Include Tag

- Allow you to include content from a file in an `_includes` folder

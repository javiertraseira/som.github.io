# Módulo de Sistemas Operativos Monopuesto (1º SMR)



# starter-slim

The new repository will generate with the same files and folders from [rundocs/starter-slim][repo], You can [preview the theme to see what it looks like][preview], or even [generate it today][generate].

## site.pages
 :bulb:
{% for item in site.pages %}
1. [{{ item.title | default: item.url }}]({{ site.baseurl | append: item.url }})
{%- endfor %}

## Roadmap
See the [open issues][issues] for a list of proposed features (and known issues).

## Documents
For full documentation, please refer to [https://rundocs.io](https://rundocs.io)

## The License
The theme is available as open source under the terms of the [MIT License][license].


[repo]: https://github.com/rundocs/starter-slim/
[preview]: https://rundocs.github.io/starter-slim/
[generate]: https://github.com/rundocs/starter-slim/generate
[issues]: https://github.com/rundocs/jekyll-rtd-theme/issues
[license]: https://github.com/rundocs/jekyll-rtd-theme/blob/master/LICENSE

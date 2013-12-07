---
layout: default
title: superbob GitHub public page
subtitle: This is my public activity on GitHub !
---

You can find here some information on my activity on GitHub.com and the projects I contribute to.

### My projects

{% for project in site.categories.projects %}

 * **[{{ project.title }}]({{ project.url }})** ({{ project.date | date_to_string }}) | [View On GitHub]({{ project.project-url }})

  > {{ project.excerpt }}

  [Read more]({{ project.url }}) | [View On GitHub]({{ project.project-url }})

{% endfor %}

### Narcicism

My name is Florian Morgan, you can find more information about me [here](http://about.me/florian.morgan).

### Credits

[GitHub](https://github.com/) for its first class git and web hosting.<br />
[Jekyll](http://jekyllrb.com/) for its really nice static website generator.<br />
[orderedlist](https://github.com/orderedlist) for his beautiful [Modernist](https://github.com/orderedlist/modernist) theme.

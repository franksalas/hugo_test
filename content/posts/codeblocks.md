---
title: "Codeblocks"
date: 2017-09-03T17:43:15Z
draft: false
---

# Codeblocks

#JS test
<iframe width="400" height="400" frameborder="0" scrolling="no" src="//plot.ly/~samsung.staines/21.embed"></iframe>

### html

```html
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
```

### python

```python
def my_func(name):
    out = "Hello {}".format(name)
    return out
```

## other stuff

### mathjax

$e=mc^2$





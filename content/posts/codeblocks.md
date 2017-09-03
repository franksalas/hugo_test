---
title: "Codeblocks"
date: 2017-09-03T17:43:15Z
draft: false
---

# Codeblocks

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

$$
v_\pi(s) = \sum_{a \in \mathcal{A}} \pi(a|s) q_\pi(s,a)
$$

---

$e=mc^2$

### graphviz


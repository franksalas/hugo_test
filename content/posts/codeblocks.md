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
`$ v_\pi(s) = \sum_{a \in \mathcal{A}} \pi(a|s) q_\pi(s,a)  $`

---

$e=mc^2$

### graphviz

```viz-dot
digraph g { 
node[shape="circle" , label="", width=0.2, height=0.2]
l1[xlabel="v\(s\)"]
l21[xlabel="a", width=0.1, height=0.1 , style=filled]
l22[width=0.1, height=0.1, style=filled]
l31[xlabel="v\(s'\)"]

l1 -> l21
l1 -> l22
l21 -> l31 [xlabel="r"]
l21 -> l32
l22 -> l33
l22 -> l34
}
```
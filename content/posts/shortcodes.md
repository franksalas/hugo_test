---
title: "Shortcodes"
date: 2017-09-03T16:54:46Z
draft: false
---

# Hugo's built in shortcodes 




## Highlight

{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}



## tweet

{{< tweet 877500564405444608 >}}


# vimeo

{{< vimeo 146022717 >}}


## youtube

{{< youtube w7Ft2ymGmfc >}}

---
title: "Third Entry"
date: 2020-09-05T08:39:02-04:00
publishdate: 2020-09-05
lastmod: 2020-09-05
tags: []
draft: false
---

To test `lastmod`.
I added `publishdate` and `lastmod` to the `archetypes`, 
also added 

```
{{ if gt .Lastmod .PublishDate }}, updated {{ .Lastmod.Format "2006-01-02" }}{{ end }}
```
to `single.html` in `layouts`.

The only downside is I need to manually update `lastmod` 
in the front matter.
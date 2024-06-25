---
Data: 2024-06-20
Hora: 16:10
tags:
  - Ferramentas
Ref: "[[Ferramentas]]"
---


javascript:(function(e,w){e.value = e.value.replace(/\!\[[^\]]+\]\(([^\)]+)\)/g,"<img src=\"$1\" width="+w+" />");})(document.querySelector('textarea.markdown-area'),300)
---
title: "{{ replace .Name "-" " " | title | lower}}"
date: {{ .Date }}
---

{{ dateFormat "2006-01-02" .Date }}
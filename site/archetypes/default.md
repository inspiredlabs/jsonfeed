---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
team:  "{{ replace .Params.team  "-" " " | team }}"
year:  "{{ replace .Params.year  "-" " " | year }}"
draft: true
---
---
title: {{ replace .Name "-" " " | title }}
description: Descrizione della {{ replace .Name "-" " " | title }}

date: {{ .Date }}
draft: true

tags: 
- tag1 
- tag2

prepTime: PT20M
cookTime: PT30M
totalTime: PT50M

rating:
  value: 2
  count: 5

# portate / numero di persone / dosi per
yield: 4 

ingredients:
- acqua
- sale
- pepe

instructions:
- name: <nome dello step 1>
  text: <descrizione step 1>

- name: <nome dello step 2>
  text: <descrizione step 2>

nutrition:
- calories: X kcal/porzione

# resources:
# - name: image-header
#   src: 
#   params: 
#     credits:
#       title: 
#       author: 
#       author_link: 
#       source:  
#       licence:  
#       licence_url: 

---


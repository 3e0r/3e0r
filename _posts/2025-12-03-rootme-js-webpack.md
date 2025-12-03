---
title: '[WEB] "Javascript - Webpack"'
date: 2025-12-03T15:21:00+03:00
categories:
  - Lab
  - RootMe
tags:
  - web
excerpt: " "
header:
  overlay_image: https://apprendre-avec-le-jeu.com/wp-content/uploads/2024/03/Root-me-Logo.png
  overlay_filter: 0.4
  actions:
    - label: "Lab Root-Me"
      url: "https://www.root-me.org/fr/Challenges/Web-Client/Javascript-Webpack"
---

**Найдите пароль.**
При переходе на страницу, сразу смотрю исходный код. Замечаю, что все js лежат в директории **/static/js**
<img width="1919" height="272" alt="image" src="https://github.com/user-attachments/assets/ccd20e03-072a-4409-a6d7-14c7afe1abf1" />  
Перехожу в эту директорию и вижу файлы с расширением **.js.map** скачиваю первый из них. 
<img width="1105" height="952" alt="image" src="https://github.com/user-attachments/assets/a898d088-8f8d-4f96-ae66-5b6da06025ac" />  
Загружаю его на сайт **https://evanw.github.io/source-map-visualization/** для более удобного просмотра. 
<img width="1919" height="991" alt="image" src="https://github.com/user-attachments/assets/14c02f7f-6ac9-4bc8-8638-79fabf883f96" />  
Сразу замечаю интересный webpack с названием **YouWillNotFindThisRouteBecauseItIsHidden.vue**  
И сразу видно комментарий с флагом, оставленный автором.  
<img width="1919" height="987" alt="image" src="https://github.com/user-attachments/assets/b77002ee-d462-4b74-8658-a7c6442c548e" />  
```Флаг: BecauseSourceMapsAreGreatForDebuggingButNotForProduction``` 

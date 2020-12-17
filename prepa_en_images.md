---
title: La prépa en images
cover-img: ["assets/img/philharmonie2016_test.jpg" : "Concert à la Philharmonie de Paris (2016)", "assets/img/parlement_strasbourg.JPG" : "Parlement Strasbourg", "assets/img/topchef/topchef1.JPG" : "Prépa top chef"]
initialisation1:
  - img: /assets/img/philharmonie1.JPG
    name: Concert à la Philharmonie de Paris (2016)
initialisation1:
  - img: assets/img/topchef/topchef1.JPG
    name: Prépa Top Chef (2017)
miniature1: 
  - img: /assets/img/philharmonie1.JPG
    mini: /assets/img/mini/philharmonie1_mini.jpg
    name: Concert à la Philharmonie de Paris (2016)
  - img: /assets/img/philharmonie2.JPG
    mini: /assets/img/mini/philharmonie2_mini.jpg
    name: Concert à la Philharmonie de Paris (2016)
  - img: /assets/img/philharmonie3.JPG
    mini: /assets/img/mini/philharmonie3_mini.jpg
    name: Concert à la Philharmonie de Paris (2016)
miniature2:
  - img: assets/img/topchef/topchef1.JPG
    mini: /assets/img/mini/topchef1_mini.jpg
    name: Prépa Top Chef (2017)
  - img: assets/img/topchef/topchef2.JPG
    mini: /assets/img/mini/topchef2_mini.jpg
    name: Prépa Top Chef (2017)
  - img: assets/img/topchef/topchef3.JPG
    mini: /assets/img/mini/topchef3_mini.jpg
    name: Prépa Top Chef (2017)
  - img: assets/img/topchef/topchef4.JPG
    mini: /assets/img/mini/topchef4_mini.jpg
    name: Prépa Top Chef (2017)
  - img: assets/img/topchef/topchef5.JPG
    mini: /assets/img/mini/topchef5_mini.jpg
    name: Prépa Top Chef (2017)
---

{% include visionneuse.html init=page.initialisation1  items=page.miniature1 %}

---

{% include visionneuse.html init=page.initialisation2  items=page.miniature2 %}

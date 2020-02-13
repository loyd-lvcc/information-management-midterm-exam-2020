# La Verdad Christian College
## Information Management
## Midterm Exam
### BSIS/ACT 2020

![alt text](http://s2.quickmeme.com/img/58/5805598d2b20354415f486061ac0698c978e2f288a64f6b734353bd2403b0edc.jpg "Exam")

Resource: https://docs.google.com/spreadsheets/d/1hMaHyj3PuAfAbne25WlL3-fihdjiSt-gp2FK_Qv71WY/edit?usp=sharing

* Create database store_lastname
* Create the following tables
  - users
    - id
    - email
    - password
    - firstname
    - lastname
    - created_at
    - updated_at
  - items
    - id
    - name
    - description
    - quantity
    - created_at
    - updated_at
  - carts
    - id
    - item_id
    - user_id
    - quantity
    - created_at
    - updated_at
* Insert the following users

| firstname | lastname | email | password |
| ------ | ------ | ------ | ------ |
| Tom | Fox | tom.fox@example.com | secret123 |
| Billy | Fisher | billy.fisher@example.com | password123 |
| Herbert | Rodriguez | herbert.rodriguez@example.com | 123456 |
| Anita | Terry | anita.terry@example.com | abc123 |
| Addison | Pena | addison.pena@example.com | qwerty |

* Insert the following items

| name | quantity | description |
| ------ | ------ | ------ |
| Assault Cuirass | 10 | Forged in the depths of the nether reaches, this hellish mail provides an army with increased armor and attack speed. |
| Hurricane Pike | 38 | A legendary pike once held as royal sigil of the ancient wyvern riders. |
| Manta Style | 39 | An axe made of reflective materials that causes confusion amongst enemy ranks. |
| Aeon Disk | 22 | A powerful artifact long ago smuggled out of the Ivory Incubarium. Or so many believe. |
| Vanguard | 19 | A powerful shield that defends its wielder from even the most vicious of attacks. |
| Hood of Defiance | 20 | A furred, magic resistant headpiece that is feared by wizards. |
| Shadow Blade | 15 | The blade of a fallen king, it allows you to move unseen and strike from the shadows. |
| Echo Sabre | 10 | A deceptively swift blade imbued with resonant magic. |
| Mekansm | 10 | A glowing jewel formed out of assorted parts that somehow fit together perfectly. |
| Arcane Boots | 26 | Magi equipped with these boots are valued in battle. |

* Perform query
1. Tom Fox added 3 Vanguard to cart
2. Herbert Rodriguez added 6 Aeon Disk to cart
3. Addison Pena added 10 Assault Cuirass to cart
4. Anita Terry added 11 Manta Style to cart
5. Billy Fisher added 17 Arcane Boots to cart
6. Herbert Rodriguez added 3 Hurricane Pike to cart
7. Anita Terry added 3 Mekansm to cart
8. Herbert Rodriguez added 8 Echo Sabre to cart
9. Billy Fisher added 5 Shadow Blade to cart
10. Tom Fox added 3 Hood of Defiance to cart
11. Who has the most items on the cart?
12. Who has the least items on the cart?
13. Which item has the highest quantity?
14. Which item has the lowest quantity?
15. Who has the most unique items?

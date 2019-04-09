title: Adoptez le "Swagger Driven Testing" pour tester vos APIs simplement
class: animation-fade
layout: true

<!-- This slide will serve as the base layout for all your slides -->
.bottom-bar[
  Swagger Driven Testing - @JBWatenberg - #DevoxxFR
]

---

class: impact

## {{title}}

.right[
[@JBWatenberg](https://twitter.com/JBWatenberg)
]

---

.col-4[
    ![](./images/me.png)
]
.col-8[
## Jean-Baptiste WATENBERG

.col-1[
.logo-small[
    ![](./images/logo_sg_muted.svg)<br/><br/><br/>
]
.logo-small[
    ![](./images/twitter.png)
]

.logo-small[
    ![](./images/GitHub-Mark-32px.png) 
]
]
.col-11[
    Développeur @Société Générale<br/><br/><br/><br/>
    [@JBWatenberg](https://twitter.com/JBWatenberg)  <br/><br/>
    [JeanBaptisteWATENBERG](https://github.com/JeanBaptisteWATENBERG)
]
]

---

# SG MARKETS - PLATEFORME DE SERVICES B TO B 360°
![](./images/SG_Market.jpg)

---

class: impact
# + 3500 APIs
____
![](./images/sg.png)

---

class: impact
# Documentation
____

# Qualité

---

# Documentation

## OpenAPI (AKA. SWAGGER)

<br/>
   - Une **spécification**
   - Des **outils**

---

# OpenAPI - Spécification
.condensed-code[
```yaml
/pet:
  post:
    tags:
      - "pet"
    summary: "Add a new pet to the store"
    operationId: "addPet"
    consumes:
      - "application/json"
    produces:
      - "application/json"
    parameters:
      - in: "body"
        description: "Pet object that needs to be added to the store"
        required: true
        schema:
          $ref: "#/definitions/Pet"
    responses:
      201:
        description: "Pet has been successfully added to the store"
    security:
    - petstore_auth: ["write:pets", "read:pets"]
```
]

---

# OpenAPI - Outils

   - Générateurs de code
   - Documentation interactive
   - Ecosystème de composants (validation, aide à la rédaction, etc...) 

---

class: impact
# Comment s'assurer de la qualité de ses APIs ?
---

class: impact, full, middle, center
background-image: url(./images/code.png)
# Les développeurs, avec du code 
<br/>
<br/>
<br/>
.right[
.x-small[
Photo by Markus Spiske on Unsplash
]
]

---
.col-6[
.full[
    <br/>
![](./images/frisby-test.png)
]
]
.col-6[
.full[
![](./images/test-pyramid.png)
]
]
---
class: impact, full, middle, center
background-image: url(./images/qa.png)
# Les QA/BA, avec Postman/ Insomnia/SOAP UI 
<br/>
<br/>
<br/>
.right[
.x-small[
Photo by bonneval sebastien on Unsplash
]
]
---
.col-8[
.full[
![](./images/postman.png)
]
]
--
.col-4[
.full[
![](./images/lost.gif)
]
]
.right[
.x-small[
Photo by Lidl Voyages on Giphy
]
]
---
class: impact, full, middle, center
background-image: url(./images/user.png)
# Les utilisateurs, avec Swagger UI 
<br/>
<br/>
<br/>
.right[
.x-small[
Photo by Campaign Creators on Unsplash
]
]
---
.full[
![](./images/swagger-ui-1.png)
]
---
.col-8[
.full[
![](./images/swagger-ui-2.png)
]
]
--
.col-4[
.full[
![](./images/lost.gif)
]
]
.right[
.x-small[
Photo by Lidl Voyages on Giphy
]
]
---
class: impact, full, middle, center
background-image: url(./images/idea.png)
# Swagger Driven Testing 

--

## Demo !
<br/>
<br/>
<br/>
.right[
.x-small[
Photo by Kristopher Roller on Unsplash
]
]
---

class: impact
# Et la suite ?

---

# CI/CD

![](./images/ci.png)

---

# Open Source


![](./images/react-jsonpath-editor.png)
[https://github.com/JeanBaptisteWATENBERG/react-jsonpath-editor](https://github.com/JeanBaptisteWATENBERG/react-jsonpath-editor)

---

class: impact
# Merci !!

.alt[
Questions ?
]

[@JBWatenberg](https://twitter.com/JBWatenberg)
.logo-small[
    ![](./images/GitHub-Mark-32px.png) [JeanBaptisteWATENBERG](https://github.com/JeanBaptisteWATENBERG)
]

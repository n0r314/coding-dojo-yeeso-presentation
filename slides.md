---
theme: slidev-theme-yeeso
title: Coding Dojo by Yeeso
info: |
  ## Coding Dojo by Yeeso
  Présentation des Coding Dojo

  Plus d'info sur Yeeso sur [le site de l'association](https://yeeso.org)
class: text-center
drawings:
  persist: false
transition: slide-left
comark: true
duration: 15min
layout: cover
---

# Coding Dojo

En <span class="highlight">non-mixité choisie</span>

---
layout: intro
---

**Anne-Laure Gros**

- Développeuse Java/Kotlin reconvertie depuis 2022
- Aime : les <span class="highlight">forum ouverts</span>, la tisane, l'habitat participatif
- Déteste : quand c'est pas clair, obéir sans comprendre, <span class="highlight">cuisiner</span>
- Débute en animation de mob

<!-- ---
layout: intro
---

**Manon Carbonnel**

- Développeuse et intégratrice web
- Facilitatrice Agile
- Experte en animation de mob -->


---
layout: intro
---

**Salomé Jarnouen**

- Développeuse web full stack 
- Aime : le craft(wo)manship, les arts du fil, le <span class="highlight">café</span> 
- Déteste : le code spaghetti, les solutions « magiques », <span class="highlight">Jenkins</span>



---
layout: default
---

# Au programme

- 🧊 Ice breaker
- 👩‍🏫 Kata, mob, TDD...
- 👩‍🏫 Sécurité psychologique
- 👩‍🏫 Présentation du kata et choix du langage
- 👩‍🏫 Rôles dans le mob
- 🖥️ C'est parti !
- 👍👎 Petite pause rétro
- 🖥️ On y retourne
- 👍👎 Feedback sur la séance


---
layout : three-cols-header
---

# Ice breaker : Le câble

🧊 Prendre un câble (de téléphone ou autre) et lui donner visuellement une forme qui représente votre état d'esprit pour ce dojo.

**Tour de table** de 30s par personne

::left::
## Qui es-tu ?

Ton prénom, et tes pronoms si tu le souhaites

::center::
## Ton rapport au code

Débutant·e, confirmé·e, curieux·se, en reconversion…

::right::
## Ton câble

Explication de la forme choisie et état d'esprit pour ce dojo

---
layout: image-right
image: https://thumb.wikimedia.org/wikipedia/commons/thumb/4/48/Emmanuelle-Fumonde-en-d%C3%A9monstration.jpg/960px-Emmanuelle-Fumonde-en-d%C3%A9monstration.jpg?utm_source=fr.wikipedia.org&utm_campaign=imageinfo&utm_content=thumbnail
---

# Coding Dojo/Kata

- Parallèle avec les arts martiaux japonais
- Exercice ritualisé qui peut paraitre "artificiel"
- L'objectif n'est pas de finir, mais de <span class="highlight">s'entraîner</span>


---

# Mob Programming

Mob = ensemble programming = software teaming = <span class="highlight">**programmer ensemble**</span>

Rassembler <span class="highlight">toutes les personnes</span> nécessaires
au succès d'<span class="highlight">une tâche</span>
autour d'<span class="highlight">un seul poste de travail</span>.

Mob **"strong style"** : une personne au clavier, une personne qui guide, le reste qui réfléchit.


---
layout: quote
---

Pour qu'une idée arrive dans le code, elle doit passer par le cerveau de quelqu'un d'autre.

Llewellyn Falco


---

# TDD (Test Driven Developpement)

Progression par <span class="highlight">petites itérations</span>

Cycles de 3 étapes : 
 - **Rouge** : test simple qui échoue
 - **Green** : code le plus simple possible qui fait passer le test au vert
 - **Refactor** : améliorer le code sans ajouter de fonctionnalité, en laissant le test vert

 On fait 3 exemples avant de généraliser


---
layout : default
--- 

# Sécurité psychologique

- <span class="highlight">safe place</span>
- droit à l'erreur
- favoriser les personnes moins privilégiées ou plus discrètes
- entraide <span class="highlight">bienveillante</span>
- écoute active


---
layout: quote
---

Les personnes présentes sont 

les bonnes personnes.

Ce qui arrive est la seule chose 

qui pouvait arriver.

Forum ouvert

---

# Disclaimer
On vous aura prévenu...

- On ne <span class="highlight">finira pas</span> le kata
- On ne codera pas comme vous l'auriez imaginé
- Vous allez <span class="highlight">apprendre</span> quelque chose


---
layout : image-left
image : https://s.abcnews.com/images/Sports/iga-swiatek-usa-jt-220909_1662739774318_hpMain.jpg
---

# Tennis kata

Refactorer l'implémentation du score d'un jeu au tennis.

 <span class="highlight">**Règles**</span>

- Le score d'un joueur est de 0, 15, 30 ou 40 pour 0, 1, 2, 3 points marqués
- Lorsque les deux joueurs ont marqué 3 points (40 - 40), le score est noté “Égalité”
- Celui qui marque le point suivant obtient un “Avantage”
- Si un joueur qui a l’avantage marque, il gagne le jeu 
- Si l'autre joueur marque, on revient à “Égalité”

---
layout : default
---

# Tennis kata

 <span class="highlight">**Scénario**</span>

Imaginez que l'un de vos collègues malade a fini l'implémentation et que tous les tests passent avec succès.

Votre responsable vous demande de prendre le relais pour travailler sur les 1,5h restant à facturer. Elle vous demande de  <span class="highlight">nettoyer un peu le code</span> et de préparer un retour à votre collègue sur ses choix de conception.

La suite de tests fournie est complète et rapide à exécuter. Vous ne devriez pas avoir besoin de modifier les tests, mais seulement de les exécuter fréquemment au fur et à mesure de votre refactorisation.


---
layout : two-cols-header
---

# Choix du langage


::left::
## Java

Maven, JUnit, AssertJ

➡️ Voter ☝️

::right::
## Typescript

Vitest

➡️ Voter ✌️


---
layout: three-cols-header
---

# Rôles (tourne toutes les 3 minutes)

::left::
## Au clavier 
**Driver (pilote) ou traducteurice**

Implémente du mieux qu'iel peut ce qu'on lui indique sans initiative

💡Peut poser des questions

::center::
## Guide 

**Navigator (navigateurice) ou co-pilote**

Modère le groupe et indique quoi faire à la personne au clavier

💡Guider au plus "haut" niveau possible et précise si besoin

::right::
## Le groupe

**Mobbers ou co-équipier·ères**

Propose des idées et suggestions pour avancer

💡Lâcher prise pour aller au bout d'une idée


---

# Feedback

```md {monaco}
Comment vous sentez-vous ?

- 
- 
- 
-

Que pourrait-on changer pour que ça se passe encore mieux ?

- 
- 
- 

```

---
layout: section
index: "+"
---

# Bonus

Des petits liens cool

---
layout: two-cols
---

## <span lang="en">Ensemble Toolbox</span>

Facilitez vos sessions de travail en équipe

<Youtube id="c_oW0yJWveQ" width="100%" height="250px" />

::right::

## Ça vaut le coût !

Combien coûte vraiment « ce truc là » ?

<Youtube id="JXs7wNMq5dk" width="100%" height="250px" />

---
layout: iframe-right
url: https://mobtime.hadrienmp.fr/
iframeTitle: "Application Mob Time"
---

# <span lang="en">Mob Time</span>

Gérer le chrono et la rotation des rôles facilement

<a target="_blank" href="https://mobtime.hadrienmp.fr/" title="Appli Mob Time - lien externe">mobtime.hadrienmp.fr</a>

<small>Une application développée par
  <a target="_blank" href="https://www.linkedin.com/in/hadrien-mens-pellen-39071231" title="Profil LinkedIn de Hadrien Mens Pellen - lien externe">Hadrien Mens Pellen</a> 🐙
</small>

---
layout: end
# qrCode: /qrcode-openfeedback.webp
# qrCodeLabel: "Votre avis sur OpenFeedback"
# qrCodeAlt: "QR code vers le formulaire de feedback OpenFeedback"
---

**Vous étiez au top !**


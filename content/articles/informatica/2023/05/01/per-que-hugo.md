+++
title = "Per què Hugo"
date = 2023-05-01T20:03:45+02:00
draft = false
+++

![La paraula "HUGO", en majúscules, amb cada lletra dins d'un hexàgon arrodonit, amb les arestes amb un color més intens. La H és rosa, la U és blava, la G és verda i la O és groga](/img/hugo-logo.svg)

Els que em coneguin de fa temps potser recordaran que aquesta no és la meva primera pàgina. En particular, aquesta serà la tercera versió que publico. I és un retorn als orígens, ja que la primera també va ser feta en Hugo. Una decisió que a priori pot semblar estranya, però que és fruit d'una reflexió.

## Què és Hugo?
Jo podria intentar definir-lo, però crec que és més fàcil agafar el que diu a [la web d'Hugo](https://gohugo.io/)

> Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again.

Hugo és un programa escrit en Go, tal com deixa entreveure el nom, que serveix per crear webs estàtiques a partir dels següents elements:

* Layouts
* Fulls d'estil
* Markdown

En el moment de crear la web simplement cal triar un tema dels múltiples que existeixen, que ja inclou els *layouts* i els *fulls d'estil*, i començar a redactar les pàgines utilitzant [Markdown](https://www.markdownguide.org/), el llenguatge de marcat més simple que conec. Això permet, un cop tens ben definida la configuració de la pàgina, poder afegir contingut amb moltíssima facilitat. Jo, després de provar alternatives, he acabat tornant-hi.

## Les alternatives
### Django
En un moment donat se'm va acudir utilitzar Django per crear la meva pàgina. Això, com sabrà qualsevol que l'hagi utilitzat, és una mala idea: és com *matar mosques a canonades*. Em semblava interessant, ja que estava aprenent-lo, però de seguida vaig veure que era problemàtic. Em sentia com si reinventés la roda, i no vaig arribar a publicar aquesta versió, de manera que queda en local i ja.

### Wordpress
Veient que Django no era la millor opció, se'm va acudir anar al que jo pensava que seria l'opció més fàcil: Wordpress. Lliure, molt utilitzat, i amb molt suport online, em semblava una opció bona. Vaig instal·lar-lo, i vaig crear una nova web, que aquesta sí que va acabar publicada. 

Quin va ser el problema? 

* Sistema de comentaris: jo realment mai he tingut necessitat de posar un sistema de comentaris, ja que tampoc els miraria. Però contínuament arribava merda de bots, que quedaven sota moderació, però no m'agradava veure-ho per allà. 
* WYSIWYG: actualment gairebé tothom redacta utilitzant sistemes *What You See Is What You Get*, que són aquells on mentre redactes veus l'aspecte del resultat. No és un mètode que m'agradi, ja que contínuament estic distraient-me veient com es mou una imatge, com una línia no es divideix bé... No és una cosa que m'agradi. Per això vaig fer el meu TFG en LaTeX, faré el TFM també així, el meu CV... És cert que en Wordpress pots redactar en HTML, però no és com està pensat

## La reflexió
El sistema que tenia jo anteriorment per publicar era:
1. Redactar i revisar en local
2. Penjar a github
3. Baixar els canvis des del servidor
4. Compilar a HTML

El gran problema era que passava a veure's malament gairebé sempre. No tenia la mateixa versió d'Hugo, i era difícil de tenir-la ja que eren distribucions GNU/Linux diferents i per tant les fonts des d'on s'instal·laven les coses eren també diferents. 

Però realment tot partia d'un mal enfocament: per què compilar-ho al servidor, quan es pot compilar en local i penjar-ho directament? Aquesta reflexió em va venir al cap quan em van parlar d'una altra pàgina feta també amb Hugo i els seus avantatges. I vaig arribar a la conclusió que les pegues que tenia realment no eren pegues reals, sinó que era jo fent-ho malament. I Hugo cada cop va semblar-me més bona idea de nou

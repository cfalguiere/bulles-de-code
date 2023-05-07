---
layout: single
title: "Un nouveau cycle commence"
categories:
  - Blog
tags:
  -
excerpt: Le blog se poursuit sur ce nouveau support
classes: wide
assets_folder: /assets/
header:
  image: /assets/images/landpage-header.png
---

{% assign author = site.data.authors[page.author] %}
{% assign wp_url = author.url_wordpress %}
Ce site prend la suite de mon ancien site [Claude au pays des 4J]({{ wp_url }}).

<header>
<h3>Pourquoi Bulles de Code ?</h3>
</header>

Un nouveau blog, avec de nouveaux sujets correspondant à mes activités du moment. Toujours du code, moins Java, plus Python, plus de Machine Learning, une point de DevOps/MLOps, des réflexions sur les pratiques.

Du code, avec un peu de légèreté. Plus de dessins et d'illustrations, et si j'ai le temps quelques bulles de BD.

J'espère aussi que les gens y trouveront des choses à apprendre, des chioses utiles comme sur l'ancien.

<header>
<h3>Pourquoi recommencer ailleurs ?</h3>
</header>

Pourquoi pas ? j'avais déjà migré de Blogger vers Wordpress.

Je voulais un support plus simple à gérer pour moi. Pouvoir travailler avec les outils dont j'ai l'habitude, en gestion de configuration sur GitHub, garder tous les assets ensemble, pouvoir plus simplement intégrer du code, avoir plus de liberté avec les templates.

Le site précédent était géré sous Wordpress et hosté par Wordpress.com.

Je n'ai pas de gros reproches à faire à Wordpress. C'est un outil pratique pour faire un site sans savoir programmer. Il a une bonne exposition.

Je sais que j'aurais pu contourner plusieurs des points cités plus haut avec des plugins. Mais pour moi faire marcher ces plugins pour faire du no-code était plus compliqué que coder.

Donc au revoir Wordpress et bonjour [Jekyll](https://jekyllrb.com/) .

<header>
<h3>Jekyll & Minimal Mistakes</h3>
</header>

[Jekyll](https://jekyllrb.com/) est un générateur de site statique, assez mature, donc pas tout jeune :-). C'est en fait la base des GitHub pages.   

J'utilise le thème [Minimal Mistakes](https://mmistakes.github.io/minimal-mistake). Ce thème est bien plus complet et esthétique que les thèmes Github. Github Pages accepte tout site en Jekyll et le site peut être servi par Github directement. Il existe d'autres options simples comme le copier en site statique sur S3 pour le faire servir par AWS.

Le site est un repo GitHub [bulles-de-code](https://github.com/cfalguiere/bulles-de-code). C'est flexible, facile à paramétrer, extensible si besoin. Le thème [Minimal Mistakes](https://mmistakes.github.io/minimal-mistake) est bien organisé et documenté.

Bien sûr il y a quelques inconvénients
- pas de Wysiwyg, il faut installer Jekyll et utiliser Jekyll serve pour faire le rendu en développement
- il faut compléter avec des utilitaires de l'éditeur de texte pour la correction des fautes d'orthographe
- la mise à jour du template est moins "en un click" que sur Wordpress

C'est la solution qui me convient pour le moment.

<header>
<h3>Le programme à venir</h3>
</header>

En attendant du contenu nouveau, le site recense [diverses présentations](presentations/) faites depuis 2014.

Avec le temps je reprendrai aussi certains articles de mon ancien site [Claude au pays des 4J]({{ wp_url }}) sous Wordpress.

En route !

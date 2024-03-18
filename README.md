# Comment créer un package laravel avec composer et le deployer

# Plan
- <a href="#installer-composer" > Installer Composer <a/>

# Installer composer

**Introduction**

Composer est un outil de gestion des dépendances en PHP. Il vous permet de déclarer les bibliothèques dont votre projet dépend et il les gérera (installation/mise à jour) pour vous.

**Gestion des dépendances**

Composer n'est pas un gestionnaire de paquets dans le même sens que Yum ou Apt. Oui, il s'occupe de "paquets" ou de bibliothèques, mais il les gère par projet, en les installant dans un répertoire (par exemple vendor) à l'intérieur de votre projet. Par défaut, il n'installe rien globalement. Il s'agit donc d'un gestionnaire de dépendances. Il supporte cependant un projet "global" par commodité via la commande global.

Cette idée n'est pas nouvelle et Composer est fortement inspiré par <a href="https://www.npmjs.com/" target="_blank">npm<a/> de node et <a href="https://bundler.io/" target="_blank">bundler<a/> de ruby.

<a href="https://getcomposer.org/doc/00-intro.md">La documentation officielle de Composer<a/>
 
<a href="https://getcomposer.org/download/">Le lien de téléchargement de Composer<a/> 

# Créer le package

**Initialisation du package**

Avant de commencer cette étape, il faut d'abord s'assurer que votre composer est installé et est à jour.


    composer init

Cette commande lancera une série de questions (prompts) qui permettront une configuration rapide et facile de notre package.
Certaines questions seront obligatoires (*) et d'autres seront optionnelles :

1. Package name (*)
   
   Ce paramètre est pris sous format <vendor>/<name>

   C'est un paramètre important parce qu'il servira de namespace aux futurs utilisateurs du package.

   Tâchez donc de bien entrer ces paramètres. Généralement, <vendor> correspond au nom de l'entité qui a développé le package et <name> le service du package

   ex: orange/orangemoney
   



# Tester le package en local
# Tester le package en production

   
Install composer

composer init

[
  remplir les informations de la création
]


Installation du package en local

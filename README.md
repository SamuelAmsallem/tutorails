# 1. La différence entre un site statique et un site dynamique
## a) Site statique

Les pages d'un site statique affiché dans le navigateur sont identiques au code HTML & CSS saisie. Les pages peuvent afficher toutes formes de contenu comme du texte, des images, des vidéos etc... Les pages d'un stites statiques sont directement stockées sur un serveur et prêtent à l'emploi.

Exemple :

Prenons l'exemple du site vitrine d'un professionel de la santé. Comme son nom l'indique, le site vitrine à pour mission de communiquer sur l'activité du professionnel. C'est une profession dont la fréquence de mise à jour n'est pas élevé. Ainsi un site statique lui suffira pour afficher des informations essentiellles comme (l'adresse du cabinet, le snuméro de téléphone, les horaires, le prix des consultations,etc..)

## b) site dynamique

Les sites dynamiques permettent d'afficher l'information de manière différente en fonction de l'interaction avec l'utilisateur. L'application exploite ainsi une base de données qui permet de mettre à jour le contenu du site en temps réel.

Exemple :

Un site de e-commerce est par essence, un site dynamique car il est utilisé par de nombreux internaute et chaque usage et différent. Ainsi le site dynamique va uniquement exploiter les informations dont il a besoin commme les informations de l'utilisateur (Nom, prénom, adresse, numéro carte bancaire, etc..) et les informations de l'application comme (les produits en stocks, caractériques des produits, etc...)

# 2. Le MVC
## a) Modèle

C'est un schéma recensant les cas de figures possible du comportement de l'application et de l'utilisateur

## b) Vues

La vue se sert du modèle. Une vue contient des éléments visuels ainsi que la logique nécessaire pour afficher les données provenant du modèle. Dans une application web une vue contient des balises HTML.

## c) Contrôleur

Module qui traite les actions de l'utilisateur, modifie les données du modèle et par conséquent de la vue.

**Exemple :** 

Pour une application de bancaire, le modèle représente des entités comme des comptes, des clients, ainsi que les opérations telles que dépôt et retraits, et vérifie que les retraits ne dépassent pas la limite de crédit.

# 3. Les routes
chaque requete implique une hemin précis.

# 4. Les Bases de Données


# 5. GET / POST
graphikart recup donné + post afficher les donnée


# 6. Le concept de migration

Permet d'avoir un projet plus facilement maintenable et améliore le travail en équipe en vous évitant d'avoir à manipuler directement la base de données


# 7. Les relations entre les models des BDD

graphikart


# 8. Les fonctions du CRUD
CRUD est un accronyme qui signifie en anglais : (Create, Read, Update, Delete)

**Exemple :**

Un service de gestion de contact doit permettre à l'utilisateur les choses suivantes : Création de contacts, consultation de contact, mise à jour de contact, et supression de contact.

Si l'une ou l'autre de ces opérations fondamentales manque, le logiciel sera considéré comme incomplet.

migrations = modifie bdd
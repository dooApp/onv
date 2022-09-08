# FAQ Administrateurs

## FAQ à destination des adminstrateurs de l'Observatoire National Ventilation.

* [2022-1 Que faire si un utilisateur a perdu le mail d'activation de son compte?](#faq2022-1)
* [2022-2 Que faire si un éditeur de logiciel n'a plus accès a sa clé de sécurité](#faq2022-2)

## 2022-1 Que faire si un utilisateur a perdu le mail d'activation de son compte? <a name="faq2022-1"></a>

Il est possible de demander l'envoi d'un nouveau mail d'activation pour un compte qui n'a pas encore été activé depuis l'interface d'adminstration de l'Observatoire.

Cette opération nécessite un accès Adminstrateur à la plateforme.

Se rendre dans le menu Administration > Gestion des utilisateurs puis cliquer sur le bouton "Ré-envoyer le mail d'activation" au niveau du compte concerné.

## 2022-2 Que faire si un éditeur de logiciel n'a plus accès a sa clé de sécurité <a name="faq2022-2"></a>

Il n'est pas possible de récupérer la clé de sécurité d'un éditeur depuis l'Observatoire. Si un éditeur a perdu sa clé de sécurité, il est nécessaire de supprimer la clé actuelle et d'en créer une nouvelle.

**Attention** : en suivant cette procédure, la clé actuelle de sécurité de l'éditeur sera supprimée et son logiciel ne pourra plus communiquer avec l'Observatoire National Ventilation avec cette clé.

Cette opération peut-être effectuée par un adminstrateur de la plateforme :

* se rendre dans le menu Entités > Software
* cliquer sur le bouton "Editer" du logiciel concerné
* effacer la clé de sécurité dans le formulaire d'édition et enregistrer

L'éditeur peut alors suivre [la procédure initiale](https://dooapp.github.io/onv/access-editor/#2-api-reference-) pour obtenir une nouvelle clé de sécurité.

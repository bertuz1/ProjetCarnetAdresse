#**Cahier de recette**

##Scénarios à recetter et valider

#### Lancement de l’application
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Lancer l’application     |  | L’application s’est exécutée sans problème |


#### Création de notes 
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Créer une note sans thème    | Titre, contenu  | La note doit apparaître dans la liste des notes |
| Créer une note avec une importance (étoile cochée) et sans thème   | Titre, contenu, étoile cochée    |La note doit apparaître dans la liste des notes « Importantes » |
| Créer une note avec thème     | Titre, contenu, thème | La note doit apparaître dans le dossier correspondant à son thème |
| Créer une note avec une importance (étoile cochée) et avec thème     | Titre, contenu, thème, étoile cochée | La note doit apparaitre dans la liste des notes « Importantes » et dans le dossier correspondant à son thème|

#### Enregistrement de notes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Enregistrer automatiquement une note     || La note est enregistrée automatiquement lors de la fermeture de l’application|

#### Suppression de notes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Supprimer une note     | | La note est supprimée de toutes les listes |

#### Consultation de notes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Consulter une note     |  | L’utilisateur doit pouvoir consulter le contenu de la dernière version de sa note même si l’application a été fermée.|

#### Modification de notes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Modifier une note    | Titre, contenu  | La modification du titre et du contenu a été effectuée |
| Modifier le degré d’importance d’une note  | Titre, importance, contenu  | Lors de la modification d’une note, celle-ci doit apparaître dans la liste des notes « Importantes » |
| Modifier le thème d’une note    | Titre, thème, contenu  | La note devra être archivée dans le dossier correspondant au nouveau thème |


#### Création de thèmes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Créer un thème     | Thème | Lors de la création d’un thème via l’interface graphique, ce dernier apparaîtra dans la liste des thèmes. |


#### Tri des notes
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Tri et affichage par défaut par date de dernière modification     |  |Les notes seront affichées, par défaut, par date de dernière modification|
| Tri par thème    |  | Lors de la sélection du tri par thème, les notes seront ordonnées par ordre alphabétique des titres |
| Tri par degré d’importance    |  | Pour le tri par degré d’importance, les notes seront également rangées par ordre alphabétique des titres|

#### Envoi de notifications
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Envoi d’une notification     |  | Lorsque l’utilisateur ouvrira son application, une notification de ses notes « Importantes » du jour lui est envoyée |
| Envoi d’une notification par mail     |  | L’application enverra un mail tous les jours à 00:00 lui informant les notes « Importantes » de la liste|

#### Changement des couleurs de fond
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Changer les couleurs de fond des notes     |  | Les couleurs de fond des notes ont été modifiées |


#### Grisage des notes cochées
| Démarches        | Données          | Résultats  |
| :-------------:    |:-------------:   | :-----:|
| Griser les check-box de la note     |  |Dans le cas d’une liste de cases à cocher, lorsque l’utilisateur cochera une case, celle-ci grisera la case et le texte |
| Dégriser les check-box de la note    |  |Lorsque l’utilisateur décoche une case grisée, celle-ci laissera apparaître le texte.|



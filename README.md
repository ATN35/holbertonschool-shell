Project: Shell, basics

cd : Cette commande permet de changer de répertoire. Par exemple, cd dossier vous déplace dans le dossier spécifié.

ls : Utilisée pour afficher le contenu d'un répertoire. Par défaut, elle affiche les fichiers et dossiers dans le répertoire actuel.

pwd : Cette commande affiche le chemin absolu du répertoire actuel (répertoire de travail).

less : Utilisé pour afficher le contenu d'un fichier page par page de manière interactive. Par exemple, less fichier vous permet de parcourir le contenu du fichier.

file : Cette commande permet de déterminer le type de fichier. Par exemple, file fichier affiche des informations sur le type de fichier.

ln : Utilisée pour créer des liens (symboliques ou physiques) entre les fichiers. Par exemple, ln -s fichier lien crée un lien symbolique vers le fichier.

cp : Utilisée pour copier des fichiers et des répertoires. Par exemple, cp fichier destination copie le fichier vers la destination spécifiée.

mv : Cette commande permet de déplacer ou de renommer des fichiers et des répertoires. Par exemple, mv fichier destination déplace le fichier vers la destination spécifiée.

rm : Utilisée pour supprimer des fichiers et des répertoires. Par exemple, rm fichier supprime le fichier spécifié.

mkdir : Cette commande permet de créer des répertoires. Par exemple, mkdir dossier crée un nouveau dossier avec le nom spécifié.

type : Utilisée pour afficher comment une commande serait interprétée si elle était exécutée. Par exemple, type commande affiche le type de la commande (alias, fonction, binaire, etc.).

which : Cette commande permet de localiser l'emplacement d'une commande exécutable. Par exemple, which commande affiche le chemin vers l'exécutable de la commande.

help : Utilisée pour afficher l'aide intégrée pour les commandes du shell. Par exemple, help commande affiche l'aide spécifique à la commande.

man : Cette commande permet d'afficher les pages de manuel pour les commandes. Par exemple, man commande affiche le manuel de la commande spécifiée.

Ces commandes sont couramment utilisées dans les systèmes Unix/Linux pour effectuer diverses tâches liées à la navigation, à la manipulation de fichiers et aux opérations de base du système.


Project: Shell, permissions

chmod : Utilisé pour modifier les permissions d'accès (lecture, écriture, exécution) d'un fichier ou d'un répertoire.

sudo : Permet à un utilisateur d'exécuter une commande avec les privilèges d'administration (superutilisateur) sur un système Linux.

su : Permet à un utilisateur de passer à un autre utilisateur (généralement root) en se connectant avec le mot de passe de cet utilisateur.

chown : Change le propriétaire d'un fichier ou d'un répertoire. Par exemple, "chown user fichier" changera le propriétaire du fichier en "user".

chgrp : Change le groupe propriétaire d'un fichier ou d'un répertoire. Par exemple, "chgrp group fichier" changera le groupe propriétaire du fichier en "group".

id : Affiche l'identifiant de l'utilisateur actuel, y compris son nom d'utilisateur, son identifiant utilisateur (UID) et les groupes auxquels il appartient.

groups : Affiche les groupes auxquels l'utilisateur actuel appartient.

whoami : Affiche le nom d'utilisateur de l'utilisateur actuel.

adduser : Commande interactive pour ajouter un nouvel utilisateur sur le système, avec la possibilité de spécifier des informations supplémentaires.

useradd : Commande non interactive pour ajouter un nouvel utilisateur sur le système, généralement utilisée dans des scripts ou des tâches automatisées.

addgroup : Commande pour ajouter un nouveau groupe sur le système.

Ces commandes sont couramment utilisées pour gérer les utilisateurs, les groupes et les autorisations sur les systèmes Linux.


Project: Shell, I/O Redirections and filters

echo : Affiche un message ou une variable sur la sortie standard.

cat : Concatène et affiche le contenu d'un ou plusieurs fichiers.

head : Affiche les premières lignes d'un fichier. Par défaut, les 10 premières lignes sont affichées.

tail : Affiche les dernières lignes d'un fichier. Par défaut, les 10 dernières lignes sont affichées.

find : Recherche des fichiers ou des répertoires dans une hiérarchie de fichiers.

wc : Compte le nombre de lignes, de mots et d'octets dans un fichier donné.

sort : Trie les lignes d'un fichier selon un ordre spécifié.

uniq : Supprime les lignes en double consécutives dans un fichier.

grep : Recherche les lignes correspondant à un motif (expression régulière) dans un fichier ou une sortie de commande.

tr : Effectue une translittération de caractères (remplacement de caractères) sur une entrée.

rev : Inverse l'ordre des caractères sur chaque ligne d'un fichier.

cut : Coupe des sections (colonnes) d'un fichier en utilisant un délimiteur spécifié.

passwd (5) : Affiche le contenu du fichier de configuration /etc/passwd (format passwd) contenant les informations sur les utilisateurs.

Ces commandes sont largement utilisées dans les tâches d'administration système, le traitement de fichiers et la manipulation des données en ligne de commande sous Linux.


Project: Shell, init files, variables and expansions

printenv : Affiche les valeurs des variables d'environnement.

set : Affiche les variables d'environnement ainsi que d'autres variables, y compris les variables locales.

unset : Supprime une variable d'environnement ou une variable locale.

export : Définit une variable d'environnement et la rend accessible aux processus enfants.

alias : Crée un alias pour une commande. Permet de définir un raccourci pour une commande ou une séquence de commandes.

unalias : Supprime un alias défini précédemment.

. : (point) Exécute un script dans le contexte de l'environnement courant. Équivalent à la commande "source".

source : Exécute les commandes d'un fichier de script dans le contexte de l'environnement courant.

printf : Affiche du texte formaté selon une chaîne de format spécifiée.

Ces commandes sont utilisées pour gérer les variables d'environnement, définir des alias pour des commandes et effectuer des opérations liées aux variables dans l'environnement de la ligne de commande.

Project:

Shell, basics
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

Shell, permissions
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

Shell, I/O Redirections and filters
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

Shell, init files, variables and expansions
gcc : Le compilateur GNU C (gcc) est utilisé pour compiler des programmes en langage C. Il transforme le code source C en code exécutable.

printf (3) : La fonction printf() est utilisée pour afficher du texte formaté sur la sortie standard (généralement l'écran). Elle permet d'afficher des variables, des chaînes de caractères et d'autres éléments en utilisant un format spécifié.

puts : La fonction puts() est utilisée pour afficher une chaîne de caractères sur la sortie standard, suivie d'un saut de ligne. Elle est utilisée pour afficher des messages simples.

putchar : La fonction putchar() est utilisée pour afficher un seul caractère sur la sortie standard. Elle prend un seul argument, le caractère à afficher.

Ces commandes et fonctions sont utilisées couramment lors de la programmation en langage C. Elles permettent d'afficher des messages à l'utilisateur, d'afficher du texte formaté et de compiler des programmes en langage C.

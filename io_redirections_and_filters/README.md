# Shell, I/O Redirections and Filters

Ce projet regroupe une série de scripts Bash conçus pour manipuler le système de fichiers, filtrer des données et transformer du texte dans un environnement Linux (Ubuntu 20.04).

## 📝 Liste des Scripts et Fonctions

| Fichier | Description |
| :--- | :--- |
| `0-hello_world` | Affiche un message de bienvenue ou une chaîne de caractères spécifique. |
| `1-confused_smiley` | Affiche un smiley complexe utilisant des caractères spéciaux (ex: `"(Ôo)'`). |
| `2-hellofile` | Affiche le contenu du fichier `/etc/passwd`. |
| `3-twofiles` | Affiche le contenu de deux fichiers spécifiques. |
| `4-lastlines` | Affiche les 10 dernières lignes d'un fichier. |
| `5-firstlines` | Affiche les 10 premières lignes d'un fichier. |
| `6-third_line` | Affiche uniquement la troisième ligne d'un fichier texte. |
| `7-file` | Crée un fichier avec un nom spécifique contenant un texte précis. |
| `8-cwd_state` | Écrit le résultat de `ls -la` dans un fichier nommé `ls_cwd_content`. |
| `9-duplicate_last_line` | Duplique la dernière ligne d'un fichier. |
| `10-no_more_js` | Supprime récursivement tous les fichiers se terminant par `.js` dans le répertoire courant et ses sous-dossiers. |
| `11-directories` | Compte le nombre de répertoires et sous-répertoires dans le dossier actuel. |
| `12-newest_files` | Affiche les 10 fichiers les plus récents du répertoire, triés par date. |
| `13-unique` | Prend une liste de mots en entrée et n'affiche que ceux qui apparaissent exactement une fois. |
| `14-findthatword` | Extrait toutes les lignes contenant le mot "root" dans le fichier `/etc/passwd`. |
| `15-countthatword` | Compte le nombre de lignes contenant le mot "bin" dans `/etc/passwd`. |
| `16-whatsnext` | Affiche les lignes contenant "root" ainsi que les 3 lignes suivantes dans `/etc/passwd`. |
| `17-hidethisword` | Affiche toutes les lignes du fichier `/etc/passwd` qui ne contiennent **pas** le mot "bin". |
| `18-letteronly` | Affiche toutes les lignes du fichier `/etc/ssh/sshd_config` qui commencent par une lettre. |
| `19-AZ` | Remplace toutes les occurrences des caractères `A` par `Z` et `c` par `e`. |
| `20-hiago` | Supprime tous les caractères `c` et `C` d'une entrée texte. |
| `21-reverse` | Inverse l'ordre des caractères de l'entrée (miroir). |
| `22-users_and_homes` | Affiche les utilisateurs et leurs répertoires personnels à partir de `/etc/passwd`, triés par nom d'utilisateur. 
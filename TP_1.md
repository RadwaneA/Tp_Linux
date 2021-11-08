# Tp_linux 

Casser une vm tout en s'amusant

```
* et un GRAND MERCI à 
`exo-open --launch TerminalEmulator`
 qui nous a permis de pouvoir lancer ces jolies commandes au lancement d'un terminal !!
```
---
## tp1 

`rm -rf /`

 * supprime absolument tout les fichiers qu'il peut trouver dans la vm !!
>Violent celui-là..
---
## tp 2

`cp /dev/zero /dev/mem`


* Celui là crée des terminales infini dans la vm !
>J'ai déjà la tête qui tourne <(O_O)>

---
## tp 3

`:(){:|:&};:` 

* **fork bomb** est une **fonction shell** qui crée de nouvelle copie de sois même et qui rempli toute la mémoire de la vm !
>Multiclonage !!!
---
## tp 4
`dd if=/dev/random of=/dev/sda`

Celui-là **écrira brutalement** des données aléatoires sur le disque dur sans se soucier des choses stupides comme les systèmes de fichiers ou les partitions
>Le disque dur en pls~
---
## tp 5
`mv / /dev/null`

'/dev/null' est un **emplacement spécial** sur le disque dur qui peut être considéré comme un trou noir et mv envoie absolument tout dedans
`rm -rf /boot`

Cela **supprime** le repértoire de démarrage ce qui veut dire qu'il ne pourra effectuer aucun démarrage du système et ainsi cela fera planter la vm.
Et mon préféré `rm -f /usr/bin/sudo;rm -f /bin/su`

Il **révoque** l'accès superutilisateur sur root et ne pourra donc pas exécuter de commande de privilèges root!
>Comboo !



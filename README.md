# TCP-Backdoor
Un backdoor (ou porte dérobée) avec TCP

Il s'agit d'une implémentation de Reverse TCP Backdoor écrite en Python3. 
Il fonctionne sur Windows ainsi que sur le système d'exploitation Linux. 
Cette porte dérobée a les fonctionnalités suivantes : Accès en ligne de commande à la machine cible. 
Récupérez n'importe quel fichier de la machine cible. 
Transférez n'importe quel fichier de l'attaquant à la machine cible. 
Placez n'importe quel fichier dans le répertoire de démarrage de Target exécutant le système d'exploitation Windows.

## UTILISATION : 
1) saisissez [nom du fichier] : pour copier un fichier de la machine cible vers la machine de l'attaquant. 
2) cd [DIR] : Pour changer de répertoire. 
3) transfer [Filename] : pour transférer un fichier de la machine de l'attaquant vers la machine cible. 
4) startup [filename] : pour placer un fichier dans le registre de démarrage de la machine cible (uniquement Windows). 
5) terminate : pour mettre fin à l'exploit aux deux extrémités.

- Les commandes CMD et Terminal fonctionnent également selon le système d'exploitation cible.

## REMARQUE : 
Cette porte dérobée sert à comprendre les connexions TCP entre ordinateurs. 
L'utilisation de ces scripts pour des activités illégales n'est pas autorisée. 
REMARQUE : Utilisez ce programme à vos risques et périls. 
Je ne serai pas responsable de toute activité illégale effectuée à l'aide de ce programme.

PROFITEZ
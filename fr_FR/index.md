Description
===========
- **Jeedouino v1.06**  

   Ce plugin vous permet de contrôler de différentes manières les pins entrées/sorties des cartes suivantes :

   * Arduinos (différents modèles) branchés en USB sur *Raspberry PI*.
   * Arduinos (différents modèles) branchés avec un shield Ethernet (W5100, W5500, ENC28J60) sur votre réseau.
   * les ESP8266 (wifi) ex:  
     NodeMCU , Wemos, etc.  
     SONOFF 4CH & POW, ELECTRODRAGON 2CH.  
   * les GPIO du *Raspberry PI*.
   * les cartes PiFace (piRack) sur *Raspberry PI*.
   * les cartes IO PiPlus et les MCP23017 sur *Raspberry PI*.


   Il fonctionne en local (sur Jeedom) ou en déporté (seul : option JeedouinoExt) sur votre réseau.

   Il est compatible avec le fonctionnement du plugin Jeedom-Link de Jeedom.

Installation et mise à jour du plugin
====================================

> **[IMPORTANT]**
>
> Une installation ou une mise à jour du plugin, sur un système un peu ancien, peut prendre du temps pour la mise à jour de celui-ci.  
> Un reboot peut même être nécéssaire dans certains cas.  
> Il suffit de suivre les logs des dépendances pour surveiller la progression.   

Installation du plugin
---

























Description 
===
MyModbus.
Plugin servant à communiquer en protcole Modbus via plusieurs type de Liaison . 

- Liaison modbus Ethernet 
- Liaison Série Mode RTU ( A venir ) 




Création d'un équipement  .
===

1) Configuration du plugin

Après téléchargement du plugin, il vous suffit juste d’activer et d’installer les dépendances Mymodbus (clic sur le bouton Installer/Mettre à jour)




Avant de démarrer le demon , il faut commencer par créer un équipement modbus  :

-  Photos etc.... 



2) Configuration des équipements

Vous retrouvez ici toute la configuration de votre équipement :

    Nom de l’équipement Mymodbus : nom de votre équipement Mymodbus,

    Objet parent : indique l’objet parent auquel appartient l’équipement,

    Catégorie : les catégories de l’équipement (il peut appartenir à plusieurs catégories),

    Activer : permet de rendre votre équipement actif,

    Visible : rend votre équipement visible sur le dashboard,

    Note

    Les autres options :
![image101](../images/blea_icon.png)

    Notes:
![mymodbus](../images/mymodbus_exemple_crouzet_cmd.png)

En-dessous vous retrouvez la liste des commandes :

    Nom : le nom affiché sur le dashboard,

    Afficher : permet d’afficher la donnée sur le dashboard,

    Tester : permet de tester la commande

    Note
	
-   Une fois cliqué sur sauvegarder le démon va démarer automatique etc ;....  : 	

    Jeedom recherche toutes les jours à 00h30 s'il y a un automate à mettre à l'heure , si oui il le fait .

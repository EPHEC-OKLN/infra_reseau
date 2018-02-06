# Tâches réalisées


-Distinction des vlans 

-Changement de l'infrastrucutre physique et logique suite aux remarques de Monsieur Schalkjiwk 

-Adressage des ip  (voir schéma physique)

-Mettre en place les scripts de lancement de l'infrastrucure réseau ( ca arrive ) 

-OSPF

-VTP

-Table d'adressage, table d'atttribution des vlans et des ports.


# Problèmes rencontrés (énnoncé du problème + solution)

-Rajout d'un switch L3, pour avoir une solution de secour en cas de panne du réseau 

-Rajout d'un switch L2 après le retour car nous n'avions pas assez d'interfaces

-Se mettre d'accord si on mets tous les vlans dans un L3 ou on repartit ces derniers dans les 2 L3. Nous avons fait le choix de mettre tous dans le même L3 pour pouvoir basculer dans le second en cas de fail.

-Comment définir le chemin priotaire -> HSRP

-Choix de mettre la tz et la dmz au niveau du firewall pour avoir plus de sécu

-Protocole de routage  OSPF,VTP

-> trunking au niveau des L3 distribution et des L2 de la couche acces vers les L3 de la couche distribution

-> mode acces au niveau de la couche d'acces



# Motivations des technologies/infrastructures utilisées


# Remarques éventuelles

# Sources (Important !)

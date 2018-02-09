# Tâches réalisées

-Schéma logique et physique.

-Le site principal contient les services administration, formation, comptabilité, IT et marketing et le secondaire administration,
formation et vente.

-Le trafic a été séparé en 4 vlan : service, guest, user et management.

-Plan d'adressage.

Les services ayant été implémenté sont :

-un point d’accès wifi sur le réseau interne, les invités externe peuvent en bénéficier.

-La sécurisation/ redondance optimisée pour les serveurs, les services et les périphérique réseau.

-ssh On a utilisé des clés de 2048 bits.

-VTP pruning qui permet de diminuer la bande passante.

-DNS.

-STP a été implémenté pour éviter les collisions sur le réseau.

-2 Switchs L3 qui permettent de ne pas avoir de SPOF au niveau des L3, on a utilisé HSRP qui a permis de choisir le prioritaire 
de ces 2 L3.

-Etherchannel permet d’économiser de la bande passante entre les 2 L3. Ca permet aux 2 liens de n’en former qu’un seul.

-OSPF est configuré pour le routage.


# Problèmes rencontrés (énnoncé du problème + solution)

Les difficultées principales pendant la semaine ont été :

-La première difficultée a été d’avoir un bon plan d’adressage.

-On a dû beaucoup revoir les schémas logique et physique vu que beaucoup de changements ont été fait les 2 premiers jours.

-Les 2 premiers jours, les switchs qui étaient à notre disposition ne nous permettaient pas d’implémenter tout ce que nous
souhaitions mais ce problème a été résolu le 3ème  jour grâce à du nouveau matériel.


# Motivations des technologies/infrastructures utilisées

# Remarques éventuelles

On aurait du mettre des access-list mais pour ne pas bloquer tout ceux occupé avec le réseau, on n’a pas eu l’occasion de le mettre.

On souhaitait ajouter un deuxième access-point qui aurait permis de séparer les guests et les users.

Wi-Fi  ssid:  Groupe-B                   mot de passe wifi :   oklnGroupeB2018


# Sources (Important !)

# Conclusion du groupe : 

Au niveau de l'ensemble de la partie infra, ce fût intéressant car nous avons pu tester sur du vrai matériel
ce qui se rapproche assez fortement par rapport aux cours habituels.

On a eu beaucoup de stress car l'infra devait être dispo au plus vite car les autres groupes dépendaient de nous surout que nous 
avons du changer plusieurs fois les schémas.

Il y a eu une bonne ambiance dans le groupe et un bon rythme de travail.


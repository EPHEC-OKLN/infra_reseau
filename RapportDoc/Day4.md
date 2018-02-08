# Tâches réalisées

-Réinitialisation de la stack.

-Configuration de base sur les switchs pour avoir quelque chose de fonctionnel, une fois que la configuration était fonctionnelle, on rajoute HSRP ce qui a permis de finaliser l'infrastructure.

-Ajout d'une access-List

-Ajout d'etherchannel

# Problèmes rencontrés (énnoncé du problème + solution)

-Problèmes de câblage physique => nouveaux cables.

-Erreurs lors de l'attribution des numéros de ports aux switchs.

-Les PC's n'arrivaient pas à pinguer autre chose que les switchs à cause de problèmes de routage et de firewall. HSRP a résolu ce problème grâce à la préemption en donnant des prioritées différentes aux switchs layer 3.

-Erreur double IP sur les switchs layer 3 à cause de mauvaises adresses IP entrées.

# Motivations des technologies/infrastructures utilisées

# Remarques éventuelles

Pour désactiver la fonctionnalité de stacking, il faut utiliser les commandes :

switch(config)# switch 2 renumber 1  //Renuméroté le switch 2 en switch 1.
switch(config)# no switch 2 provision   // Supprime le switch 2 de la configuration.


# Sources (Important !)

https://www.cisco.com/c/fr_ca/support/docs/ip/hot-standby-router-protocol-hsrp/9234-hsrpguidetoc.html#preemption

https://www.cisco.com/c/fr_ca/support/docs/ip/hot-standby-router-protocol-hsrp/13780-6.pdf

https://learningnetwork.cisco.com/thread/30859

https://www.ciscomadesimple.be/2009/09/23/cisco-configuration-de-base-dun-etherchannel-entre-deux-switch/

Ouvrage : Cisco  Routage et communication, Laurent Schalkwijk et André Vaucamps.

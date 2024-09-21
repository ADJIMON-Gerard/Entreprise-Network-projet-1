# Entreprise-Network-projet-1

Étude de cas et Exigences

Dans le cadre de votre projet de réseautage de fin d'année, vous devez concevoir et mettre en œuvre Vic Réseau Hôtel moderne. L'hôtel dispose de trois étages; 
au premier étage il y a trois départements (Réception, magasin et Logistique), 
au deuxième étage il y a trois départements (Finance, RH et Sales/Marketing), 
tandis que le troisième étage héberge les services IT et Admin. Par conséquent, les éléments suivants font partie des considérations lors de la conception et de la mise en œuvre;

-Il devrait y avoir trois routeurs reliant chaque étage (tous placés dans la salle des serveurs dans le département IT).

-Tous les routeurs doivent être connectés les uns aux autres à l'aide d'un câble DCE série.

-Le réseau entre les routeurs doit être 10.10.10.0/30,10.10.10.4/30 et 10.10.10.8/30.

-Chaque étage devrait avoir un interrupteur (placé dans le plancher respectif).

-Chaque étage devrait avoir des réseaux WIFI connectés aux ordinateurs portables et aux téléphones.

-Chaque département devrait avoir une imprimante.

-Chaque département devrait être dans un VLAN différent avec les détails suivants; 


**- 1er Étage;**

- Reception-VLAN 80, Réseau de 192.168.80.0/24
- Store-VLAN 70, Réseau de 192.168.70.0/24
- Logistics-VLAN 60, Réseau de 192.168.60.0/24
 
**- 2ème Étage;** 

- Finance-VLAN 50, Réseau de 192.168.50.0/24
- HR-VLAN 40, Réseau de 192.168.40.0/24
- Sales-VLAN 30, Réseau de 192.168.30.0/24
  
**- 3ème Étage;**

- Admin-VLAN 20, Réseau de 192.168.20.0/24
- IT-VLAN 10, Réseau de 192.168.10.0/24 

-Utilisez OSPF comme protocole de routage pour annoncer les routes.

-Tous les périphériques du réseau sont censés obtenir une adresse IP dynamiquement avec leur routeur respectif configuré comme serveur DHCP. 

-Tous les périphériques du réseau sont censés communiquer entre eux. 

-Configurer SSH dans tous les routeurs pour la connexion à distance. 

-Dans le département IT, ajoutez un PC appelé Test-PC pour porter fa0/1 et utilisez-le pour tester la connexion à distance. 

Configurez la sécurité du port sur le commutateur IT-dept pour autoriser uniquement Test-PC à accéder au port fa0/1 (utilisez la méthode collante pour obtenir l'adresse mac avec le mode de violation de l'arrêt.)


**Technologies Implémentées**

1 Création d'une topologie réseau à l'aide de Cisco Packet Tracer.

2 Conception Réseau Hiérarchique.

3 Connexion de périphériques de mise en réseau avec un câblage correct.

4 Création de VLAN et attribution de ports numéros de VLAN.

5 Sous-réseau et adresse IP.

6 Configuration du Routage Inter-VLAN (Router sur un stick).

7 Configuration du serveur DHCP (Router en tant que serveur DHCP).

8 Configuration de SSH pour un accès distant sécurisé.

9 Configuration de la sécurité des ports de commutation ou de la sécurité des ports sur les commutateurs.

10 Configuration du réseau WLAN ou sans fil (Cisco Access Point).

11 Configuration de l'appareil Hôte.

12 Tester et Vérifier la Communication Réseau.

![Capture d'écran 2024-09-12 082035](https://github.com/user-attachments/assets/3ea505f6-1688-4c5d-892a-5d9ab7e6f21c)


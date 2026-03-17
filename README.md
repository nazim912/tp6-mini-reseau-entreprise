# tp6-mini-reseau-entreprise
faire un petit reseau comme en entreprise

j'ai mis un routeur un switch et 4 pc

j'ai cree vlan 10 rh
et vlan 20 it

pc0 pc1 dans vlan 10
pc2 pc3 dans vlan 20

port fa0 24 en trunk vers routeur

sur le routeur

ip 192.168.10.1 pour vlan 10
ip 192.168.20.1 pour vlan 20

jai cree dhcp pour les 2 reseaux

les pc ont pris ip automatique

test ping entre tous les pc

ca marche

le routeur fait passer les vlan

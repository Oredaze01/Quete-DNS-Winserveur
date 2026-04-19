# Quete-DNS-Winserveur




### 1. Configuration de la zone directe du serveur

Config IP de la carte réseau avec le serveur DNS entré manuellement

![[Pasted image 20260419174245.png]](Ressources/Config-DNSserver-1.png)


Zone directe du serveur

![[Pasted image 20260419174521.png]](


### 2. Configuration de la zone indirecte

![[Pasted image 20260419174732.png]](


### 3. Ping depuis le client Ubuntu vers les 2 noms DNS du serveur

avec 
````
ping server-dns.wilder.lan
`````

![[Pasted image 20260419183910.png]](


Puis 

````
ping alias.wilders.lan
`````




![[Pasted image 20260419185105.png]](



### 4.  Commande nslookup du client au serveur DNS

````
nslookup server-dns.wilders.lan
````



![[Pasted image 20260419185539.png]](


![canvas](https://user-images.githubusercontent.com/34917424/157109870-7dfb9307-6a99-452d-be7a-db92de50488e.png)

### Limitations températures

Tout comme dans le firmware des cartes mères j'ai défini les limites à 120 et 260°C.

### La page Tools/More...  

![canvas](https://user-images.githubusercontent.com/34917424/157110682-badb1699-8f6d-4e4a-90e8-a40095de744b.png)

#### Clean

![canvas](https://user-images.githubusercontent.com/34917424/157110778-dba61505-67d1-48ac-9e17-298beb92dc9d.png)

Pour nettoyer la buse j'effectuais cette séquence :
- Lever la tête vers Z200 (une vingtaine d'appuis sur Z+) et au milieu en X à la main.
- Chauffer au maximum (26 appuis sur le bouton + à +10°)
- Une fois la température max atteinte éteindre la chauffe
- Frotter la buse en immobilisant la tête pendant que sa température descend jusqu'à 170 ou 160°, température à laquelle le plastique ne s'écoule plus.  

Le cycle de nettoyage permet de faire les opérations machines par un seul appui.  
La machine positionne la tête à mi hauteur et au milieu du portique et chauffe la buse jusqu'à 260°.  
Puis la chauffe s'arrête et la LED s'allume en bleu vert pour signaler la période propice au nettoyage.
Une fois que la température de la buse a baissé à 170° la LED passe en blanc pour 2 secondes puis la tête va à l'origine X gauche.  
La LED s'éteint pour signaler la fin du cycle de nettoyage.  
Durée : Prévoir 4 minutes  

#### Front Bed
![canvas](https://user-images.githubusercontent.com/34917424/157111113-3b030914-3090-4efe-95bc-8349777e232f.png)

Quand on tire sur le plateau pour le ramener en avant le moteur de l'axe Y génère du courant et peut endommager le contrôleur.  
Avec ce bouton la machine effectue un G28 Y puis un G0 jusqu'au max en Y pour présenter le plateau à l'avant de l'imprimante.  

#### Z-Max  

![canvas](https://user-images.githubusercontent.com/34917424/157110936-50e12d07-15f2-4aa1-aab5-21a510976ac5.png)

Cette commande effectue un G28 Z puis un G0 jusqu'au Z max.  
Ces mouvements sont utiles pour l'entretien des vis sans fin.


# Présentation Arduino Uno

L’Arduino Uno est un petit ordinateur qui permet de recueillir des informations sur le monde qui nous entoure à l’aide de capteurs comme : le capteur de présence, de température et de distance. Il peut aussi contrôler des composants comme les moteurs, les relais et les Leds. Tout cela est possible grâce à la possibilité de connecter divers appareils et composants à l’Arduino pour réaliser les projets souhaités.
L’Arduino Uno est une carte électronique beaucoup utilisée aussi bien par des ingénieurs que des passionnés d’électronique et de robotique. 


## À quoi ressemble un Arduino Uno ? 

La carte Arduino Uno est représentée sur la figure ci-dessous :

<img width="280" height="280" alt="4" src="https://github.com/user-attachments/assets/ac55bbeb-3d12-4b93-b1ef-2ecf02cb2f61" />

## Les différentes parties d’un Arduino Uno

### 1. Le microcontrôleur 
C’est le cerveau de notre carte. Il reçoit le programme que nous allons créer et le stock dans sa mémoire. C’est lui qui fait faire à l’Arduino Uno les différentes instructions écrites dans le code. Le plus souvent les microcontrôleurs retrouvés sur l’Arduino sont soit des Atmega 128p ou des SMD (Surface Mounted Device, soit composants montés en surface).

### 2. Les broches Numériques 
L’Arduino UNO dispose de 14 broches numériques étiquetées de 0 à 13. Elles sont appelées broches numériques car elles ne peuvent lire et envoyer que 2 types de valeurs : 0v ou 5v.
Elles peuvent être configurées comme entrées ou sorties :
* **Entrées** : Lorsqu’elles sont définies comme entrées, ces broches peuvent lire la tension et distinguer deux états : HIGH (5v) ou LOW (0v).
* **Sorties** : Lorsqu’elles sont définies comme sorties, ces brochent peuvent appliquer une tension de 5v (HIGH) ou Ov (LOW).

### 3. Les broches PWM (Pulse Width Modulation / Modulation de Largeur D’Impulsion)
Certaines broches numériques (11, 10, 9, 6, 5 et 3) sont marquées d’un `~` et supportent la modulation de largeur d’impulsion (PWM). Le PWM permet aux broches numériques de produire des tensions analogiques (variables) en sorties. Elles permettent de pouvoir contrôler des caractéristiques de certains composants électroniques comme la luminosité d’une Led ou la vitesse d’un moteur. Vous en apprendrez plus sur le PWM plus tard.

### 4. Les broches Analogiques
Ce sont des Broches capable de mesurer une tension variable, c’est-à-dire une valeur qui peut changer progressivement entre 0 V et 5 V, contrairement aux broches numériques. Elles sont dites analogiques car elles sont capables de pouvoir lire des valeurs continues comme un faible/forte lumière ou une faible/forte température. Ce type de valeurs ne sont pas juste HIGH ou LOW donc uniquement les broches analogiques peuvent les recevoir et les analysées. Nous irons plus en profondeur sur ses broches au fur et à mesure que nous évoluerons.

### 5. Le bouton Reset
Le bouton Reset permet de pouvoir relancer le code téléversé sur l’arduino. 

### 6. Les broches TX et RX
Les broches numériques 0 et 1 sont utilisées pour la communication série (Il s’agit du moyen de communication dont se sert l’Arduino pour pouvoir communiquer avec l’ordinateur).
* **TX (Transmettre)** : Utilisée pour envoyer des données.
* **RX (Recevoir)** : Utilisée pour recevoir des données.
* **Usage** : L’Arduino utilise ces broches pour communiquer avec d’autres appareils électroniques ainsi que lors du téléversement de nouveau code depuis l’ordinateur. 

> **NB** : Évitez d’utiliser ces broches pour d’autres tâches que la communication série, sauf si nécessaire.

### 7. Les broches 3.3v, 5v et GND
Il s’agit des broches utilisées pour l’alimentation des différents capteurs qui seront reliés à l’Arduino Uno. Les broches GND agissent ici comme des masses.

### 8 & 9. Les ports d’alimentation de l’Arduino
L’Arduino possède 2 ports d’alimentation : Un port USB qui permet d’alimenter et de téléverser des codes sur l’Arduino. Et un port jack qui permet d’alimenter l’arduino avec des piles de 9 volts. 

> **NB** : Si vous alimenter votre Arduino par le port USB, n’utiliser pas un courant supérieur à 5v pour alimenter la carte. Ce dernier risque de griller. Avec la prise jack, l’Arduino peut supporter une tension allant de 7 à 12v. Il existe une autre façon d’alimenter l’Arduino que nous verrons dans la suite. 

---

## Le logiciel Arduino IDE

Le logiciel Arduino IDE fonctionne sur Mac, Windows et Linux. C’est grâce à ce logiciel que nous allons créer, tester et envoyer les programmes sur l’Arduino.
L’IDE est téléchargeable à l’adresse suivante : [https://www.arduino.cc/en/software/](https://www.arduino.cc/en/software/).
Nous allons utiliser la version : Arduino IDE 2.3.7.

![Interface Arduino IDE](images/ide-interface.png)

Pour avoir ce rendu noir vous pouvez mettre votre IDE en mode sombre.

**Etapes :**

1. Aller sur **Fichier** :
   ![Menu Fichier](images/ide-menu.png)
2. Cliquer sur **Préférences** :
   ![Menu Préférences](images/ide-preferences.png)
3. Vous verrez une petite fenêtre où vous pourrez changer votre mode d’éclairage :
   ![Changement de thème](images/ide-theme.png)

Voilà votre IDE est en mode sombre. 

---

## Chap 2 : Ecrire tes premiers codes
*(À venir)*

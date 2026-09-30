# smartcities

# TP Smart Cities — MicroPython

Ce dépôt contient le code et les exercices réalisés dans le cadre du cours de Smart Cities. L'ensemble des programmes tourne en MicroPython sur une carte Raspberry Pi Pico W.

---

## Matériel nécessaire

- Une carte **Raspberry Pi Pico W** (v1)
- Un câble Micro-USB (assurez-vous qu'il gère les données et pas uniquement la charge)
- Une breadboard et les composants requis selon les exercices

## Logiciels requis

- Le firmware **MicroPython** pour Pico W (au format `.uf2`)
- L'éditeur **Thonny IDE**

---

## Mise en route

### 1. Flasher la Pico W
1. Récupérez le fichier `.uf2` de MicroPython pour Pico W sur le site officiel.
2. Maintenez le bouton **BOOTSEL** de la carte appuyé et branchez-la en USB à l'ordinateur.
3. Un lecteur nommé `RPI-RP2` apparaît. Glissez-déposez le fichier `.uf2` dedans.
4. La carte redémarre toute seule : MicroPython est prêt.

### 2. Configurer Thonny
1. Ouvrez **Thonny**.
2. Allez dans `Outils` > `Options` > onglet `Interpréteur`.
3. Choisissez **MicroPython (Raspberry Pi Pico)**.
4. Sélectionnez le port série associé à la carte (ou laissez sur détection automatique).
5. Cliquez sur **OK**. La console en bas doit afficher l'invite `>>>`.

## Exercice 1
Pour pouvoir utiliser le programme de l'exercice 1, il faut respecter le branchement suivant :
PIN 16 : Brancher une led ainsi qu'une résistance d'environ 300ohm (selon la couleur de la led utilisé) en série vers le GND.
PIN 18 : Brancher un bouton poussoir muni d'un pull down.
<img width="842" height="595" alt="image" src="https://github.com/user-attachments/assets/280d8e86-efc8-49c2-bd44-b3e5fef18fd5" />


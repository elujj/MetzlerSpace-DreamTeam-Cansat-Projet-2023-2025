# MetzlerSpace-DreamTeam-Cansat-Projet-2023-2025
Le metzlerspace est la suite de l'équipe Dreamteam qui a participé à cansat en 2024 et 2025
Nos composants électroniques: (KC= Kit Cansat)

Rasberry pi classique avec CIRCUITPYTHON pas MICROPYTHON (KC)
2*RFM69(KC)
BMP280(KC)
Battery lipo 1000mA(KC)
Powerboost 1000 charger(KC)
Sandisk 8GB (attention à la taille données corompues)
Adafruit Micro SD SPI or SDIO Card Breakout Board
gyroscope adafruit LSM9DS1
optionnel: switch on/off
PCB(KC)
FPC-Ruban-40-P0.5-100mm(KC) si il casse trouvable sur amazon dans les Ruban pr appareils photo

Soudures :
La majorité des infos sur ces sites si vous voulez faire en micropython :
https://wiki.mchobby.be/index.php?title=ENG-CANSAT-PICO-BELGIUM
https://www.esero.lu/wp-content/uploads/2023/10/CanSat-Raspberry-Pi-Pico-Workbook-FR-v11.pdf

Apres si vous etes des goats modo du ms20 prenez circuitpython et réinitialisez votre prico :

-réinitialiser son pico (p37)
-installer circuitpython : https://circuitpython.org/board/raspberry_pi_pico/
-insaller les librairies voir github
-c'est bon t'es un dissiple du J

Soudures du lsm et Sd adaptater dur le 2e pcb :
les composants suivants sont a souder sur le 2e pcb

lsm : 
LSM / PCB
VIN = 3V
GND = G
SCL = scl
SDA = sda

SD card :
3V = 3V
GND = G
CLK = sck
so = mi
CS =  g27 (pi27) sur 2epcb

souder le powerboost :
![image](https://github.com/user-attachments/assets/fcdf2db7-6afd-4a1a-81a4-bfe06116770c)








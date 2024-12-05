************************************************************************
                         WiFi_Scan_PIO
************************************************************************

Le projet WiFi_Scan_PIO est un programme développé sur PlateformIO (PIO) 
dans l'environnement Visual Studio Code (VSCode)

Auteur : chahit (avec la collaboration de plusieurs YouTubeurs que je remercie sans les nommer)

Réalisé le 4 décembre 2024.

La réponse à ce programme est dans le terminal, sous la forme :

     ° Scan start (démarrage du scan)
     ° 
     ° un nombre (= le nombre de réseaux trouvés)
     ° chaque réseau est lors présenté dans l'ordre d'importance en db 
        * n° d'ordre
        * le SSID du réseau (Service Set IDentifier)
        * valeur du RSSI (Received Signal Strenght Indicator). Pour rappel, le nombre est négatif
                          et plus il est proche de 0 plus il est puissant)
        * Si une indication 'code demandé' apparaît c'est qu'il nécessite un mot de passe 

Le scaning se répète toutes les 20 secondes et ce délais peut être modifié.

Pour les informations complémentaires, voir dans le code.

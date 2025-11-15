# reTerminalE1001_Meteo-France

Fichiers de configuration Home Assistant et ESPHome utilisées dans mon tutoriel **Afficher les données Météo-France sur un reTerminal E1001 avec ESPHome** disponible sur mon blog https://tutoduino.fr/reterminal-e1001-meteo-esphome/

![Station météo sur reTerminal E1001](https://tutoduino.fr/ookoorsa/2025/11/Tutoduino-reTerminalE1001-1080x540.jpg)

J'utilise le fichier de configuration reterminal-e1001-greenhouse.yaml pour afficher la température de ma serre. Je remplace donc l'affichage de l'humidité extérieure (donnée météo-france) par l'affichage des données d'un capteur externe de température configuré dans Home Assistant. Deux capteurs basés sur l'intégration "statistics" indiquent la valeur minimale et maximale de ce capteur dans les 48 dernières heures.

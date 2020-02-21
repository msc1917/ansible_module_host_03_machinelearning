# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "machinelearning"
Einrichten der Hosts für Machinelearning-Tools (Google Coral, Intel NCS und nvidia Jetpack)

## Verzeichnis "tasks"
Playbook-Tasks, welche in der Rolle durchgeführt werden

## Files:
* main.yml:
* setup_coral.yml: Setup für Google Coral
* setup_ncs.yml: Setup für Intel Neural Compute Stick
* setup_jetpack.yml: Setup für nVidia Jetpack
* setup_default.yml: Standard-Einrichtungen für Machine-Learning

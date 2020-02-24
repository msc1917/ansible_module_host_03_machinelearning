# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "host_03_machinelearning"
Einrichten der Hosts für Machinelearning-Tools (Google Coral, Intel NCS und nvidia Jetpack)

## Verzeichnis "defaults"
Standard-Variablen für die Rolle (werden von anderen Variabledefinitionen übersteuert)

## Definition der Parameter
Die unten angegebenen Parameter in Listen stellen die Parameter dar, die in den Rollen interpretiert werden.

### Settings für Machine-Learning-Engines:
	ml_engines:
	  - ncs
	  - coral
	  - jetpack

### Andere Parameter:
	do_mount_filesystems
	do_software_upgrade
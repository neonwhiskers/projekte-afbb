# Projektplan - LF 10b:
 
Mithilfe von Nixos soll ein Backup- und einen Monitoring-Service eingerichtet werden.
Ziel ist es ein Proof of Concept zu ertellen, welches später als Grundlage für die Monitoring und Backup Operationen der DD-IX e.V. Infrastruktur dienen soll. Hierbei soll die IT-Sicherheit nicht aus den Augen gelassen werden und natürlich muss es sowohl fürDD-IX als auch für LF10b eine Dokumentation geben. Da nicht die nötigen Ressourcen vorhanden sind wird das Backup erstmal lokal auf der selben Maschine gespeichert werden, davon ist in einer Produktivumgebung ausdrücklich abzuraten.

## Ziele:

Ziele Nico:

-
-
-
-
-
-
-
-
-
-

Ziele Sofia:

-
-
-
-
-
-
-
-
-
-

## Welche Dienste sollen als Teil des Projektes integriert werden?

- Backup: restic 
- Monitoring: Prometheus + Grafana
- Dokumentation: mdbook

Monitored werden sollen typische Servereigenschaften wie: 

- Hardware utilazitaion
- Logs
- Erreichbarkeit der Services
- Status der systemd units

Monitoringdienst soll bei Überschreitung von Grenzwerten infromationen per Mail und Push-notification bereitstellen.


# Projektdoku - LF 10b



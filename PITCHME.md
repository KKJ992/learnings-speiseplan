---?image=assets/img/globus_bg.jpg
@snap[midpoint]
## learnings speiseplan-portlet
@snapend

---
@snap[north-west]
#### ist-zustand
@snapend

@snap[east]
@img[anmeldung](assets/img/anmeldung.png)
@snapend

@snap[west span-70 text-left text-07]
@ul[](false)
- Das USU Speiseplan-Portlet besteht aus 3 einzelnen Portlets: Anmeldung, Verwaltung, Auswertung
- Das Auswertungs-Portlet stellt eine .txt Datei zum Download zur Verfügung
- Die .txt Datei ist für das Peras-System gedacht und dient zur Abrechnung der Bewirtungen
- Diese Funktion wird in der Praxis noch nicht verwendet
@ulend
@snapend

---
@snap[north-west]
#### feststellung
@snapend

@snap[west span-90 text-left text-07]
@ul[](false)
- Für die Abrechnungen der Bewirtungen wird Peras gar nicht verwendet
- Eine Tabelle wird vom Empfang monatlich per Hand ausgefüllt
- Tabelle wird an Buchhaltung weiter gegeben
@ulend
@snapend

---
@snap[north-west]
#### soll-zustand
@snapend

@snap[west span-90 text-left text-07]
@ul[](false)
- Die Tabelle soll in Form einer Exceldatei generiert werden
- Am Ende jeden Monats soll diese Datei automatisch an die Buchhaltung gesendet werden
- Dieser Prozess soll auch manuell angestoßen werden können
- Man soll sich die Exceldatei auch direkt herunterladen können
- All diese Funktionen sollen nicht für jeden zugänglich sein
@ulend
@snapend

---
@snap[north-west]
#### schwierigkeit
@snapend

@snap[west span-90 text-left text-07]
@ul[](false)
- Das Projekt lokal zum laufen bringen
- Manche Funktionen sind von bestimmten Einträgen in der Datenbank abhängig
@ulend
<br>
@ul[](false)
- Das Projekt ist sehr umfangreich trotz weniger Funktionen
- Änderungen an bestehendem Code sehr schwierig
- Keine richtige Dokumentation
@ulend
@snapend

---
@snap[north-west]
#### Verwendete Software / frameworks
@snapend

@snap[west span-50 text-left text-07]
@ul[](false)
- Liferay 6.2
- Liferay Developer Studio (Eclipse)
- MySQL Workbench
- Apache Directory Studio (LDAP)
@ulend
@snapend

@snap[east span-50 text-left text-07]
@ul[](false)
- Java Server Faces (PrimeFaces)
- Quartz Job Scheduler (CronTrigger)
- Apache POI (für MS Documents)
- Spring
- Liferay MailService
- Liferay Permissions (Checker)
@ulend
@snapend

---
@snap[north-west]
#### ergebnis
@snapend

@snap[west span-40 text-left text-06]
@ul[](false)
- Auswahl des Monats unter „Abrechnung für“
- Direkter Download einer Exceldatei über Download-Button
- Send Email Button sendet Abrechnung an Buchhaltung (+ Quartz Job)
@ulend
@snapend

@snap[east]
@img[auswertung](assets/img/auswertung.png)
@snapend

@snap[south fragment]
@img[abrechnung](assets/img/abrechnung.png)
@snapend

---
@snap[north-west]
#### sonstiges
@snapend

@snap[west span-90 text-left text-07]
@ul[](false)
- Anleitung „Lokale Testumgebung aufsetzen“ geschrieben
- Alle Änderungen dokumentiert
- Tests für neue Funktionen geschrieben
- Kommunikation + Dokumentation
@ulend
@snapend

---
@snap[north-west]
#### ausblick
@snapend

@snap[west span-50 text-left text-07]
Mögliche neue Funktionen:
@ul[](false)
- Auswahl für vegetarische Gerichte
- Interface zum Bearbeiten von Produkten und Preisen (Liferay Commerce?)
@ulend
@snapend

@snap[east span-50 text-left text-07]
@ul[](false)
- Ist das Projekt noch Wartbar / Erweiterbar?
- Sollte das ganze Projekt neu aufgesetzt werden?
@ulend
@snapend

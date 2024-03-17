# Krepper_E_UC_Template

## Beschreibung von UC 1.03 Alarm bei zu hoher Herzfrequenz in Use Case Template

### Name und Identifikationsnnummer 
UC 1.03 - Alarm bei zu hoher Herzfrequenz während der Leistungsdiagnostik am Fahrradergometer

### Beschreibung Anwendungsfall
Es werden verschiedene Leistungslevel stufenweise mit definierter Dauer durchlaufen. Nach einer durchlaufenen Leistungsstufe wird die Belastung kontrolliert gesteigert (z.B. um eine vorher definierte Watt-Zahl). Meist wird dies bei der Leistungsdiagnostik bis zur Ausbelastung des Athleten/der Athetin fortgeführt.

### Beteiligte Akteure
Athlet/Athletin, Diagnostiker:in (evtl. Sportmediziner:in), evtl. Trainer:in des Athleten/der Athletin

### Status
in Arbeit

### Verwendete Anwendungsfälle

Vorbedingungen
Im Anamnesegespräch wird aufgrund der maximalen Herzfrequenz des Athleten/der Athletin ein Grenzwert festgelegt (von Diagnostiker:in, u.U. in Absprache mit Trainer:in) bei dem der Alarm ertönen soll. Falls die maximale HF nicht bekannt ist, wird diese z.B. durch die grobe Faustformel Maximale HF = 220 - Lebensalter angenommen. Erste Warnung bei z.B. 90% der max. HF. Falls HF den zuvor besprochenen maximalen HF-Wert übersteigt, sollen Vitalparameter von Proband:in genauer gecheckt werden. 

### Auslöser
Vorher definierten "Grenzwert" von zu hoher HF wird überschritten. Alarm ertönt - weitere Schritte werden eingeleitet (Vitalparameter checken, bei Bedarf - Abbruch)


### Invarianten
Die Daten müssen gespeichert werden, auch wenn die Leistungsdiagnostik vorzeitig abgebrochen wird (falls es Vitalparamter erfordern)

### Nachbedingung/Ergebnis:
Überprüfen durch Arzt/Ärztin: Liegt "nur" eine große Anstrengung (bis zur Ausbelastung) vor - geht es Proband:in ansonsten gut? --> Leistungstest kann fortgesetzt werden trotz Alarm.
Wurde die maximale HF zu niedrig angenommen oder veranlassen andere Vitalparameter (z.B. drastischer Abfall des Blutdruckes) einen Abbruch der Leistungsdiagnose um die Patientensicherheit zu gewährleisten? 

### Standardablauf:
Athlet:in absolviert Leistungstest, durchläuft so viele Leistungsstufen bis Ausbelastung erreicht wird und sie/er die geforderte Leistung (in  Watt) erbringen und einhalten kann. Test zu Ende, Daten werden gespeichert und von Mediziner:in ausgewertet und mit Proband:in und ggf. Trainer:in besprochen. Alarm wird nicht benötigt.

### Alternative Ablaufschritte
Evtl. Abfrage nach Ertönen von Alarm - soll Test fortgesetzt werden oder abgebrochen werden. Bei Abbruch entweder Abfrage ob Daten gespeichert werden sollen oder automatisches Speichern.


### Hinweise
Geeignete genaue Messmethode für HF-Messung wählen (z.B. im Zuge von EKG oder zumindest mittels Brustgurt)


### Änderungsgeschichte
0.01; 17.01.2024, Elisabeth Krepper


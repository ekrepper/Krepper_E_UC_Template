# Krepper_E_UC_Template

Beschreibung von UC 1.03 Alarm bei zu hoher Herzfrequenz in Use Case Template

Name und Identifikationsnnummer: UC 1.03 - Alarm bei zu hoher Herzfrequenz während der Leistungsdiagnostik am Fahrradergometer

Beschreibung Anwendungsfall: Es werden verschiedene Leistungslevel stufenweise mit definierter Dauer durchlaufen. Nach einer durchlaufenen Leistungsstufe wird die Belastung kontrolliert gesteigert (z.B. um eine vorher definierte Watt-Zahl). Meist wird dies bei der Leistungsdiagnostik bis zur Ausbelastung des Athleten/der Athetin fortgeführt.

Beteiligte Akteure:
Athlet/Athletin, Diagnostiker:in (evtl. Sportmediziner:in), evtl. Trainer:in des Athleten/der Athletin

Status:
in Arbeit

Verwendete Anwendungsfälle:

Vorbedingungen:
Im Anamnesegespräch wird aufgrund der maximalen Herzfrequenz des Athleten/der Athletin ein Grenzwert festgelegt (von Diagnostiker:in, u.U. in Absprache mit Trainer:in) bei dem der Alarm ertönen soll. Falls die maximale HF nicht bekannt ist, wird diese durch die grobe Faustformel Maximale HF = 220 - Lebensalter angenommen. Erste Warnung bei z.B. 90% der max. HF und falls HF den zuvor besprochenen maximalen HF-Wert übersteigt, sollen Vitalparameter von Proband:in genauer gecheckt werden. 

Auslöser
Vorher definierten "Grenzwert" von zu hoher HF wird überschritten. Alarm ertönt - weitere Schritte werden eingeleitet (Vitalparameter checken, bei Bedarf - Abbruch)


Invarianten:
Die Daten müssen gespeichert werden, auch wenn die Leistungsdiagnostik vorzeitig abgebrochen wird, falls es Vitalparamter erfordern. 

Nachbedingung/Ergebnis:
Überprüfen durch Arzt/Ärztin: Liegt "nur" eine große Anstrengung (bis zur Ausbelastung) vor - geht es Proband:in ansonsten gut?  
Wurde die maximale HF zu niedrig angenommen oder veranlassen andere Vitalparameter (z.B. drastischer Abfall des Blutdruckes) einen Abbruch der Leistungsdiagnose um die Patientensicherheit zu gewährleisten? 

Standardablauf:
Athlet:in absolviert Leistungstest, durchläuft so viele Leistungsstufen bis Ausbelastung erreicht wird und sie/er die geforderte Leistung (in  Watt) erbringen und einhalten kann. Test zu Ende, Daten werden gespeichert und von Mediziner:in ausgewertet und mit Proband:in und ggf. Trainer:in besprochen.

Alternative Ablaufschritte:


Hinweise:

Änderungsgeschichte:


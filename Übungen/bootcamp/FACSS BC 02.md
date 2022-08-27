# BootCamp PM und BWL - die ersten KAF

Die nachstehenden Aufgaben zu den Themen **Projektmanagement, Budgetierung/Projektkostenrechnung und Projektführung** stammen alle aus der **eidg. Schlussprüfung 2021** der verschiedenen Fachrichtungen. Es kann daher sein, dass bei einzelnen Grafiken noch ein Ausschnitt eines Wasserzeichens "Prüfungseinsicht" sichtbar ist, das von ICTBB dem Ausdruck hinterlegt wurde.  
  
Für die **KAFs** in den Abschnitten 1 bis 2 hast du **30 Minuten** Zeit **- danach Besprechung**

[FACSS BC 02 - BootCamp PM und BWL - die ersten KAF (office.com)](https://forms.office.com/pages/responsepage.aspx?id=KD8PHtdlokW6B_SGKKJ1dH4d0fqCZT1LhCGBv9QciOtUOUk0MEFXM0JSQVA2UTFJMFdWRVdVUDU3NS4u)

## KAF1 - Investitions- und Betriebskosten für einen Service berechnen

### Ausgangslage
Ein Unternehmen plant die Entwicklung einer Fachapplikation, welche den Kunden als Cloud- Service zur Verfügung gestellt werden soll. Für die Entwicklung der Applikation wird mit Vollzeitäquivalenten (FTE) an Softwareentwicklern und einer Entwicklungszeit von 14 Monaten kalkuliert. Die Vollkosten eines Softwareentwicklers belaufen sich auf CHF 112'800.- pro Jahr. Für den Aufbau einer Entwicklungs- und Testumgebung wird mit CHF 35'000.- gerechnet. Die Fachapplikation soll bereits vor der Markteinführung beworben werden, wozu ein Budget von CHF 50'000.- für die Marketingkampagne durch eine externe Agentur bereitgestellt wurde.   
  
Die gesamten Investitionskosten sollen durch einen Bankkredit mit einem festen Kapitalzins von 5% Zins und einer Laufzeit von 3 Jahren ohne Tilgung finanziert werden. Die produktive Applikation wird als PaaS auf der Infrastruktur eines externen Service-Providers betrieben, wobei mit durchschnittlichen Kosten von CHF 800.-- pro Monat für das hochverfügbare Hosting gerechnet wird. Während der ersten 2 Jahre nach der Markteinführung sind keine umfangreichen Weiterentwicklungen der Applikation geplant weshalb für die Wartung der produktiven Applikation vorerst mit 0.5 FTE eines Softwareentwicklers kalkuliert wird. Die Applikation soll auch nach der Markteinführung kontinuierlich beworben werden, wozu ein monatliches Budget von CHF 3'000.-- für die externe Werbeagentur vorgesehen ist.

#### Aufgabe 1
**Berechnen Sie mit den Angaben aus der Ausgangslage die Investitionskosten für die Fachapplikation ohne Fremdkapitalzinsen. Stellen Sie Ihre Berechnung nachvollziehbar dar.**  
(5 Points)

##### Antwort Aufgabe 1
**Total der Investitionskosten** (OHNE Kosten nach Markteinführung!!!): `CHF 216’600.00` 

<span style="color:orange">Entwicklungsphase (14 Monate)</span>
- Kosten Softwareentwickler: CHF 112'800 / 12 * 14 = CHF 131’600.00
- Kosten Aufbau Dev & Test Umgebung: CHF 35’000.00
- Kosten Marketingkampagne: CHF 50’000.00

##### Musterlösung
![[Pasted image 20220827151418.png]]

#### Aufgabe 2
**Berechnen Sie mit den Angaben aus der Ausgangslage die jährlichen Betriebskosten der Fachapplikation nach der Markteinführung. Ordnen Sie dazu die einzelnen Teilkosten der vorgegebenen Kostenarten zu und stellen Sie Ihre Berechnung nachvollziehbar dar. Gehen Sie bei Ihren Berechnungen von Investitionskosten von CHF 700'000.-- aus, um Folgefehler aus der Aufgabe 1 zu vermeiden.**  (10 Points)

**Kostenarten**
F1: Personalkosten, F2: Materialkosten, F3: Raumkosten, F4: Kapitalkosten, F5: Dienstleistungskosten, F6: kalkulatorische Kosten, F7: Betriebskosten pro Jahr

##### Antwort Aufgabe 2
**Jährliche Betriebskosten nach Markteinführung**: `CHF 370’333.33

F1: Personalkosten: CHF 56'400.00
F2: Materialkosten: CHF 0.00
F3: Raumkosten: CHF 9’600.00
F4: Kapitalkosten: CHF 35'000.00
F5: Dienstleistungskosten: CHF 36'000.00
F6: kalkulatorische Kosten *(Investitionskosten durch 3 Jahre)*: CHF 233’333.33
F7: Betriebskosten pro Jahr: CHF 370’333.33 

##### Musterlösung
![[Pasted image 20220827151546.png]]

Excel File
![[KAF1_Investitions_und_Betriebskosten.xlsx]]

## KAF2 - Mängel in Projektplanung ermitteln

### Ausgangslage
  
Im Rahmen eines Projekts soll eine einfache Applikation entwickelt werden. Für das Projekt wurden folgende Tasks, Abhängigkeiten und Aufwände identifiziert und geschätzt. Für die Planung und Abwicklung des Projekts wurden folgende Rahmenbedingungen festgelegt:

- Projektstart: 7. Juli 2021
- Für die gesamte Projektdauer stehen 2 Mitarbeitende zu 100% zur Verfügung.
- Das Projekt soll zeitoptimiert und mit der kürzest möglichen Dauer geplant werden, ohne dass Überzeitgeleistet wird.
- Ein Personentag beträgt 8 Stunden.
- An Wochenenden wird nicht gearbeitet.

![[Pasted image 20220729175921.png]]

#### Aufgabe 3
Ein Teammitglied hat bereits folgenden Projektplan erstellt. (Dieses Balkendiagramm finden Sie auch zwecks besserer Lesbarkeit als PDF Dokument in der Aufgabenkarte im Teams; Kanal Allgemein.)  
  
**Identifizieren Sie unter Berücksichtigung der Rahmenbedingungen in der Ausgangslage genau 6 Mängel im vorgegebenen Projektplan. Referenzieren Sie die relevanten Tasks T-xx und beschreiben Sie jeden Mangel:**  (12 Points)

![[Pasted image 20220729180145.png]]

##### Antwort Aufgabe 3
- Mangel 1
  T-03: dieser Task kann nicht vor Abschluss von T-02 gestartet werden
- Mangel 2
  T-07: dieser Task ist abhängig vom Abschluss des T-05 und kann daher frühestens am 25. August gestartet werden
- Mangel 3
  T-08: Startet am 30. August und an den Tagen vom 25./26./27.8. wurden keine Tasks zugewiesen
- Mangel 4
  T-09: dieser Task wurde vergessen im Balkendiagramm einzutragen
- Mangel 5
  T-13: dieser Task kann 2 Tage früher, zur gleichen Zeit wie der T-12 gestartet werden
- Mangel 6
  T-14: ein dritter task kann nicht noch am 12./13./16.8. bearbeitet werden, weil nur zwei 100% verfügbar sind

##### Musterlösung
![[Pasted image 20220827151738.png]]

#### Aufgabe 4
**Ermitteln Sie, wie viele Personentage eingespart werden können, wenn die vorgegebene Projektplanung unter Berücksichtigung der Anforderungen in der Ausgangslage vollständig zeitoptimiert wird. Begründen Sie Ihr Resultat in Stichworten.** (3 Points)

##### Antwort Aufgabe 4
Es können `5 Personentage` eingespart werden. 3 Tage gewinnen wir mit der Vorverlegung vom T-08 und zwei Tage werden mit dem gleichzeitigem Start von T-12 und T-13 eingespart.

Richtige Antwort zu Aufgabe

##### Musterlösung
![[Pasted image 20220827151910.png]]


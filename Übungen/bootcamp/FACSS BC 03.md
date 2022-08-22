# Aufgaben PRMA zu EV Methode

Mit diesen Beispielaufgaben kann die EV-Methode noch etwas geübt werden.
Zeitbedarf maximal 35 Minuten.

https://forms.office.com/pages/responsepage.aspx?id=KD8PHtdlokW6B_SGKKJ1dH4d0fqCZT1LhCGBv9QciOtUNE8yWTJRN0ZTTThMVTVSMFEwVDBUWFJGRy4u

## 1
In einem Projekt ist der Aufwand zur Bearbeitung des Arbeitspakets 4.3 mit 1.000 CHF abgeschätzt worden. Zum Stichtag sollte es komplett abgeschlossen sein. Die Kosten für dieses Arbeitspaket belaufen sich aber bereits auf 1.200 CHF, obwohl die Fertigstellung erst zu 80 % erreicht wurde. (8 Points)

### Fragen
Fragestellungen: 
- Wie hoch ist der derzeitige Fertigstellungswert (EV)?
- Wie hoch ist dann der Gesamtaufwand?
- Wie lautet der CPI?

Bitte so eingeben: PV = 0000.--

#### Meine Antworten
```
EV = 800.--
EAC = 1492.--
CPI = 0.67
```

##### Berechnungen
```
EV = 1000 * 0.8 = 800
EAC = 1200 / 0.67 = 1492
CPI = 800 / 1200 = 0.67
```

#### Musterlösung
`EV = 800.--`
`EAC = 1200.-- + (1000.-- - 800.--) = CHF 1400.--`
`CPI = 66.67%`
`PV = 1000.--`
`AC = 1200.--`
`PC = FG = 80%`

## 2
Ihr Projekt besteht darin, einen Zaun mit vier Seiten um ein quadratisches Grundstück zu errichten. Die Errichtung einer Seite benötigt einen Tag und soll 1'000 CHF kosten. Es soll eine Seite nach der anderen erstellt werden. Heute ist Ende des dritten Tages (= rote Linie). Kalkulieren Sie die wichtigsten Größen des Earned-Value-Ansatzes (24 Points):

### Fragen
- **PC** = Percent Complete (Fertigstellungsgrad)
- **BAC** = Budget at Completion (Gesamtbudget)
- **PV** = Planned Value (Planwert zum gegenwärtigen Zeitpunkt; auch BCWS genannt)
- **AC** = Actual Cost (am Stichtag angefallene Kosten)
- **EV** = Earned Value (Wert der geleisteten Arbeit)
- **CV** = Cost Variance (Differenz zwischen dem tatsächlichen Fertigstellungswert und den tatsächlich angefallenen Kosten. Negativ: über Budget; Positiv: unter Budget)
- **SV** = Schedule Variance (Differenz zwischen dem tatsächlichen Fertigstellungswert und den geplanten Kosten. Negativ: über Budget; Positiv: unter Budget)
- **CPI** = Cost Performance Index (Indikator für die Kosteneffizienz. Kleiner 1: negativ Größer 1: positiv)
- **SPI** = Schedule Performance Index (Indikator für die Termineffizienz Kleiner 1: negativ Größer 1: positiv)

![[Pasted image 20220729160159.png]]

#### Meine Antworten
```
PC = 0.625
BAC = 4000.--
PV = 3000.--
AC = 2800.--
EV = 2500.--
CV = -300.--
SV = -500.--
CPI = 0.89
SPI = 0.83

EAC = 4'494.40
ETC = 2031.46
```

##### Berechnungen
```
PC = (25% + 25% + 12.5%) / 100 = 0.625
BAC = 4 * 1000
PV = 3 * 1000
AC = 1000 + 1200 + 600 = 2800
EV = 4000 * 0.625 = 2500
CV = EV - AC = 2500 - 2800 = -300
SV = EV - PV = 2500 - 3000 = -500
CPI = EV / AC = 2500 / 2800 = 0.89
SPI = EV / PV = 2500 / 3000 = 0.83

EAC = AC + (BAC - EV) = 2800 + (4000 - 2500) = 4300
ETC = EAC - AC = 4300 - 2800 = 1500
```

#### Musterlösung
`PC = FG = 2500.-- / 4000.-- = 62.5% `  MACHT DIES SINN?
`BAC = 4 * 1000.-- = 4000.--`
`PV = 3 * 1000.-- = 3000.--`
`AC = 1000.-- + 1200.-- + 600.-- = 2'800.--`
`EV = 4000.-- * 0.625 = 2500.--`
`CV = 2500.-- - 2800.-- = -300.-- = über Budget`
`SV = 2500.-- - 3000.-- = -500.-- = hinter dem Zeitplan`
`CPI = 2500.-- / 2800.-- = 0.893 = über Budget`
`SPI = 2500.-- / 3000.-- = 0.833 = hinter dem Zeitplan`

## 3
Nachstehende sogenannte "Zielscheibengrafik" zeigt die "Zustände" eines Projekts nach 10 Projektstatus-Meetings mit einer Linie verbunden. Diese Meetings finden monatlich ein Mal statt. Interpretieren Sie diese Linie im Hinblick auf den Projektverlauf und formulieren Sie ihre Interpretation in ganzen Sätzen. (12 Points)

![[Pasted image 20220729160226.png]]

#### Meine Antwort
```
Am ersten Projektmeeting (PM) war der Status gut, mit einer kleinen Zeitabweichung. Der Projektverlauf verschlechtert sich bis zum 4. Meeting auf den tiefsten Punkt, mit einem SV von -15% und einer kleinen Kostenabweichung von -5%. Die ursprüngliche Zeitabweichung konnte aber bis zum Meeting 9 und 10 sogar in eine positive Bilanz gebracht werden und auch die Kosten haben sich zum Schluss hin, wieder normalisiert.
```

#### Musterlösung
```
Das Projekt startete beinahe budget- und termingerecht, geriet ab Zeitabschnitt "2" aber rasch in Schieflage. Sowohl das Budget drohte überschritten zu werden wie auch der Zeitplan schien aus dem Ruder zu laufen. Nach dem Zeitabschnitt "4" konnte zeitlich Boden gut gemach werden. Mit dem Zeitabschnitt "9" scheint das Projekt auch Budget mässig wieder ins Lot zu kommen.
```
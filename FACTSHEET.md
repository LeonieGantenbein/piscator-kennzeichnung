# Factsheet: PISCATOR auf einen Blick

Das Factsheet fasst alle Kürzel und Regeln auf einer Seite zusammen. Sie können es zum Nachschlagen nutzen oder einem Sprachmodell übergeben, damit es eine PISCATOR-Angabe für ein Forschungsprojekt vorschlägt.

## Notation

```
PISCATOR (Rolle): P(…)?, I(…)?, S(…)?, C?, A: Modelle, Sprachen, Zeitraum, T(…), O(…)?, R(…)?
```

- Zusätze stehen wie bei CLEAR vor der Zahl: P(s, n)3, I(CH)2, S(p)2, O(or, sy)0, R(v)2.
- Bei P, I, S, C und R steht die höchste erreichte Stufe; bei T und den Formen von O stehen alle zutreffenden Kürzel.
- X heisst: kommt in dieser Forschung nicht vor (SX, PX, IX, TX, OX).
- Unterscheiden sich Arbeitsschritte stark, erhält jeder eine eigene Zeile: «PISCATOR (Projektteam, Training)».

## Kürzel

| Kürzel | Bedeutung |
|---|---|
| **P** | **Privacy – Personenbezug der Daten, die eine KI verarbeitet hat** |
| P0 | Kein Personenbezug. |
| P1 | Anonymisiert. |
| P2 | Pseudonymisiert: über einen Schlüssel zuzuordnen, auch wenn ihn Dritte halten. |
| P3 | Identifizierbar (Klardaten). |
| (s) | Besonders schützenswerte Daten (*sensitive*), nach Art. 5 lit. c DSG und Art. 9 DSGVO. |
| (p) | Daten veröffentlicht, offen zugänglich. |
| (r) | Daten eingeschränkt zugänglich: auf Anfrage oder mit kontrolliertem Zugang. |
| (e) | Veröffentlichung geplant, etwa nach einer Sperrfrist. |
| (n) | Daten nicht veröffentlicht. |
| **I** | **Infrastructure – wo die KI lief, die Zugriff auf die Daten hatte** |
| I0 | Lokal, auf dem eigenen Rechner. |
| I1 | Geschützte Infrastruktur der eigenen Institution. |
| I2 | Externer Dienst mit Auftragsbearbeitungsvertrag. |
| I3 | Externer Dienst nur mit allgemeinen Nutzungsbedingungen. |
| (CH) … | Land des Serverstandorts, etwa (CH), (DE), (EU), (US). |
| **S** | **Script – KI beim Programmieren** |
| S0 | Ohne KI. |
| S1 | Hilfe: Vervollständigung, Fehlersuche, Erklärung. |
| S2 | Teile generiert. |
| S3 | Weitgehend generiert, vom Menschen gelesen und überarbeitet. |
| S4 | Vollständig generiert, ohne dass ein Mensch den Code gelesen hat. |
| (p) (r) (e) (n) | Zugänglichkeit von Code und Prompts, wie bei P. |
| **C** | **Conception – Fragestellung, Hypothesen, Design, Instrumente** |
| C0 | Ausschliesslich menschlich. |
| C1 | KI als Gesprächspartnerin. |
| C2 | Einzelne Teile von der KI ausgearbeitet. |
| C3 | Umfassend von der KI erzeugt. |
| **A** | **Attribution – Ausweisung:** Modelle und Werkzeuge mit Version, Anbieter und Art der Nutzung (angewendet, angepasst, trainiert), Programmiersprachen, Zeitraum. |
| **T** | **Transformation – was die KI mit den Daten getan hat** |
| T0 | Erhebung und Aufbereitung ohne KI. |
| (co) | Erhebung: Interviews, Befragungen, Datensammlung durch KI. |
| (ts) | Transkription. |
| (oc) | Text- und Handschriftenerkennung. |
| (t) | Übersetzung, wie L(t) bei CLEAR. |
| (ps) | Pseudonymisierung: Namen und Merkmale ersetzt oder entfernt. |
| (cl) | Bereinigung. |
| (im) | Imputation fehlender Werte. |
| (li) | Verknüpfung von Datensätzen. |
| (ex) | Extraktion von Angaben aus Dokumenten. |
| (su) | Zusammenfassung, mit der weitergearbeitet wird. |
| (an) | Kodierung, Klassifikation, Annotation. |
| (mo) | Modellierung: Die KI erzeugt selbst Befunde. |
| **O** | **Origin – Herkunft und Form der Daten** |
| O0 | Nur selbst erhoben oder erzeugt. |
| O1 | Selbst erhoben und nachgenutzt. |
| O2 | Nur nachgenutzt. |
| (or) | Original. |
| (sc) | Scrambled: Werte vertauscht, maskiert oder verrauscht. |
| (ag) | Aggregiert. |
| (sy) | Synthetisch. |
| (si) | Simuliert oder modellgeneriert. |
| (au) | Augmentiert. |
| **R** | **Responsibility – Rechenschaft** |
| R1 | Vollständig geprüft und vom Menschen verantwortet. |
| R2 | Stichprobenartig geprüft. |
| R3 | Ungeprüft verwendet, mit dem Risiko, es trotzdem verantworten zu müssen. |
| (v) | Systematisch validiert, Verfahren und Kennzahlen dokumentiert. |

## Prompt für die Selbstauskunft eines Sprachmodells

Ein Sprachmodell kann eine PISCATOR-Angabe vorschlagen. Kopieren Sie dazu den folgenden Text in den Chat, in dem Sie am Projekt gearbeitet haben. Das Modell schlägt vor, was es aus dem Verlauf ableiten kann, und fragt nach dem Rest. R setzen immer Sie.

```
Bitte kennzeichne nach PISCATOR, wie KI an diesem Forschungsprojekt beteiligt war. Stütze dich auf unseren bisherigen Chatverlauf. Was du daraus nicht sicher ableiten kannst, erfragst du bei mir, statt zu raten. Das gilt vor allem für P, I und O.

Gib für jede Achse die zutreffende Angabe an und begründe sie in einem Satz. X heisst: kommt in diesem Projekt nicht vor.

P – Privacy (Personenbezug der Daten, die eine KI verarbeitet hat): P0 kein Personenbezug · P1 anonymisiert · P2 pseudonymisiert · P3 identifizierbar; Zusätze (s) besonders schützenswert · (p) veröffentlicht · (r) eingeschränkt zugänglich · (e) Veröffentlichung geplant · (n) nicht veröffentlicht
I – Infrastructure (wo die KI mit Zugriff auf die Daten lief): I0 lokal · I1 geschützte Infrastruktur der Institution · I2 externer Dienst mit Auftragsbearbeitungsvertrag · I3 externer Dienst nur mit allgemeinen Nutzungsbedingungen; Zusatz: Land des Serverstandorts, etwa (CH)
S – Script (KI beim Programmieren): S0 ohne KI · S1 Hilfe · S2 Teile generiert · S3 weitgehend generiert, vom Menschen gelesen · S4 vollständig generiert, ohne den Code zu lesen; Zusätze (p) (r) (e) (n) für Code und Prompts
C – Conception (Fragestellung, Hypothesen, Design, Instrumente): C0 ausschliesslich menschlich · C1 KI als Gesprächspartnerin · C2 einzelne Teile von der KI ausgearbeitet · C3 umfassend von der KI erzeugt
A – Attribution: Modelle und Werkzeuge mit Version, Anbieter und Art der Nutzung (angewendet, angepasst, trainiert), Programmiersprachen, Zeitraum
T – Transformation (was die KI mit den Daten tat): (co) Erhebung · (ts) Transkription · (oc) Texterkennung · (t) Übersetzung · (ps) Pseudonymisierung · (cl) Bereinigung · (im) Imputation · (li) Verknüpfung · (ex) Extraktion · (su) Zusammenfassung · (an) Kodierung · (mo) Modellierung; T0 ohne KI
O – Origin: O0 nur selbst erhoben · O1 selbst erhoben und nachgenutzt · O2 nur nachgenutzt; Formen (or) original · (sc) scrambled · (ag) aggregiert · (sy) synthetisch · (si) simuliert · (au) augmentiert
R – Responsibility: Lass R offen. Diese Angabe kann nur der Mensch machen.

Format: PISCATOR (Rolle): P(…)?, I(…)?, S(…)?, C?, A: …, T(…), O(…)?, R?
Zusätze stehen vor der Zahl, etwa P(s, n)3 oder O(or, sy)0. Unterscheiden sich Arbeitsschritte stark in Personenbezug oder Infrastruktur, schlage je Schritt eine eigene Zeile vor.
```

## Grenzen der Selbstauskunft

Ein Modell kann nur beurteilen, was es gesehen hat. Bei PISCATOR ist das noch weniger als bei CLEAR: Wo Daten gespeichert sind, ob sie pseudonymisiert wurden und welche Verträge bestehen, steht selten im Chat. Das Modell soll deshalb nachfragen, und die Antworten kommen von Ihnen.

Ein Forschungsprojekt läuft zudem selten in einem einzigen Chat. Haben Sie mehrere Chats, Werkzeuge oder Modelle verwendet, kann das Modell nur einen Teil beurteilen. Nehmen Sie die Einstufung dann selbst vor.

Auch im besten Fall bleibt die Angabe des Modells ein Vorschlag, den Sie prüfen und, wo nötig, korrigieren. Die Rechenschaft (R) kann nur ein Mensch übernehmen.

---

[Zurück zur Übersicht](README.md) · [Spezifikation](SPEZIFIKATION.md) · [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) · English: [FACTSHEET.en.md](FACTSHEET.en.md)

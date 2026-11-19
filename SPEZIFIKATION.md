# Spezifikation v1.0

## Ausgangslage

In der empirischen Forschung arbeitet KI an Daten, lange bevor ein Text entsteht: Sie transkribiert, kodiert, pseudonymisiert, schreibt Auswertungscode, erzeugt synthetische Daten oder ist selbst die Methode. [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) kennzeichnet, wie KI an einem Text beteiligt war. Über diese Arbeit an den Daten sagt CLEAR wenig. PISCATOR schliesst diese Lücke mit acht kurzen Angaben.

## Geltungsbereich

PISCATOR richtet sich an empirische Forschung, die Daten erhebt, aufbereitet, kodiert oder mit Code auswertet, quantitativ wie qualitativ: Interviewstudien und Befragungen, Experimente und Messreihen, Korpus- und Archivarbeit, Modellierungen und Simulationen. Arbeiten ohne eigene Datenverarbeitung, etwa theoretische, historische oder hermeneutische, kennzeichnen ihren Text mit CLEAR. Eine PISCATOR-Angabe ist dort nicht nötig.

Wer wissenschaftlich publiziert, gibt beide Angaben an: PISCATOR für den Forschungsprozess, CLEAR für den Text, sofern KI-Tools auch bei der Herstellung und Bearbeitung des Textes genutzt wurden.

## Die acht Achsen

### P – Privacy (Personenbezug)

Die Achse P erfasst, wie leicht sich die Daten, die eine KI verarbeitet hat, auf Personen zurückführen lassen.

- **P0** – Die Daten haben keinen Personenbezug, etwa Messwerte aus Seen.
- **P1** – Die Daten sind anonymisiert. Sie lassen sich nicht mehr mit vertretbarem Aufwand einer Person zuordnen.
- **P2** – Die Daten sind pseudonymisiert. Namen und andere direkte Merkmale sind ersetzt, über einen Schlüssel lassen sie sich aber wieder zuordnen.
- **P3** – Die Daten sind identifizierbar (Klardaten).

Rechtlich sind pseudonymisierte Daten weiterhin Personendaten, anonymisierte nicht mehr. Der Ausdruck «personenbezogen» ist deshalb mehrdeutig. PISCATOR spricht für die unveränderte Form von «identifizierbar».

**Zusatz (s) – besonders schützenswert.** Gemeint sind Daten über religiöse, weltanschauliche, politische oder gewerkschaftliche Ansichten und Tätigkeiten, über Gesundheit, Intimsphäre und ethnische Herkunft, genetische Daten, biometrische Daten, die eine Person eindeutig identifizieren, Daten über verwaltungs- und strafrechtliche Verfolgungen und Sanktionen sowie über Massnahmen der sozialen Hilfe (Art. 5 lit. c DSG; vgl. Art. 9 DSGVO). Im Englischen steht (s) für *sensitive*.

**Zusätze zur Zugänglichkeit.** Sie sagen, ob die Daten hinter den Ergebnissen für andere zugänglich sind. (p) und (n) bedeuten dasselbe wie bei CLEAR.

- **(p)** – veröffentlicht, offen zugänglich
- **(r)** – eingeschränkt zugänglich: auf Anfrage oder in einem Repositorium mit kontrolliertem Zugang
- **(e)** – Veröffentlichung geplant, etwa nach einer Sperrfrist (Embargo)
- **(n)** – nicht veröffentlicht

Gibt es mehrere Fassungen, stehen mehrere Zusätze, etwa P(p, r)2: eine synthetische Fassung offen, die Originaldaten auf Anfrage. Welche Fassung wo liegt, steht in der Angabe zur Datenverfügbarkeit. Der Zusatz zur Zugänglichkeit ist verpflichtend, sobald es Daten gibt.

**Hinweise zur Einstufung**

- Massgebend ist die Form, die sich am leichtesten auf Personen zurückführen lässt und die eine KI verarbeitet hat.
- P2 gilt, sobald irgendwo ein Schlüssel existiert, auch wenn ihn eine Treuhandstelle hält und die Forschenden ihn nicht kennen.
- P beschreibt, ob sich Daten Personen zuordnen lassen, nicht den Rechtsstatus. Daten über verstorbene Personen sind rechtlich meist keine Personendaten mehr; wer darin identifizierbar ist, ist trotzdem P3.
- Öffentlich heisst nicht anonym. Öffentlich zugängliche Social-Media-Beiträge mit Namen oder Profilen sind P3.
- Synthetisch heisst nicht automatisch anonym. Ein Generator kann sich seltene echte Fälle merken. Ob synthetische Daten als P1 gelten, muss eigens geprüft werden.

### I – Infrastructure (Infrastruktur)

Die Achse I erfasst, wo die KI lief, die Zugriff auf die Daten hatte.

- **I0** – lokal, auf dem eigenen Rechner. Die Daten verlassen das Gerät nicht.
- **I1** – auf geschützter Infrastruktur der eigenen Institution: Server, virtuelle Maschine, Rechencluster, geschützte Forschungsumgebung.
- **I2** – bei einem externen Dienst mit Auftragsbearbeitungsvertrag.
- **I3** – bei einem externen Dienst nur mit allgemeinen Nutzungsbedingungen, etwa über ein Gratis- oder Privatkonto.

**Zusatz: Land des Serverstandorts**, als Länderkürzel: I(CH)2, I(DE)2, I(US)3. Ist nur die Region bekannt, steht (EU). Bei I0 entfällt der Zusatz, bei I1 ist er freiwillig.

**Zum Vertrag.** Wer einen Dienst nutzt, akzeptiert immer Nutzungsbedingungen, also einen Vertrag. Entscheidend ist, ob der Anbieter als Auftragsbearbeiter gebunden ist: Er darf die Daten dann nur nach Weisung bearbeiten, muss sie sichern und darf sie nicht für eigene Zwecke nutzen. In der Schweiz heisst diese Vereinbarung Auftragsbearbeitungsvertrag (Art. 9 DSG), in der EU Auftragsverarbeitungsvertrag (Art. 28 DSGVO), auf Englisch *data processing agreement*. Bei Gratis- und Privatkonten fehlt sie, und je nach Bedingungen darf der Anbieter Eingaben auch zum Training verwenden. Personendaten (P2, P3) gehören deshalb grundsätzlich nicht in I3.

**Hinweise zur Einstufung**

- Massgebend ist, wo das Modell tatsächlich läuft, nicht wo ein Programm installiert ist. Manche lokal installierten Programme schicken Daten für ihre KI-Funktionen an fremde Server. Das ist I2 oder I3, nicht I0.
- Zu I zählt jede KI mit Zugriff auf die Daten, auch ein Codeassistent, der Datendateien lesen kann. Ein Codeassistent ohne Zugriff auf die Daten zählt nicht.
- Ein heruntergeladenes Modell, das auf dem eigenen Rechner läuft, ist I0, auch wenn es von einer externen Plattform stammt.
- Rechenzentren ausserhalb der eigenen Institution, auch akademische, sind I2, sofern ein Auftragsbearbeitungsvertrag besteht.
- Bei mehreren Diensten gilt der am wenigsten geschützte. Den Anbieter nennt A.

Die rechtlichen Hinweise sind eine Orientierung. Sie ersetzen keine Rechtsberatung und keine Abklärung mit der Datenschutzstelle der eigenen Institution.

### S – Script (Code)

Die Achse S erfasst, wie weit KI am Code beteiligt war: an Auswertungsskripten, Erhebungsprogrammen, Notebooks und Werkzeugen.

- **S0** – Der Code ist ohne KI geschrieben.
- **S1** – Hilfe: Die KI hat vervollständigt, Fehler gesucht oder Code erklärt.
- **S2** – Teile generiert: Einzelne Funktionen oder Abschnitte stammen von der KI und wurden vom Menschen eingebaut.
- **S3** – Weitgehend generiert: Der Code stammt grösstenteils von der KI; der Mensch hat ihn gelesen, gesteuert und überarbeitet.
- **S4** – Vollständig generiert: Der Mensch hat beschrieben, was der Code tun soll, und das Ergebnis geprüft, den Code aber nicht gelesen. Das ist Vibecoding oder die Arbeit mit Agenten.

Die Grenze zwischen S3 und S4 liegt beim Lesen: Wer den Code kennt, ist bei S3; wer nur sein Verhalten kennt, bei S4.

**Zusätze zur Zugänglichkeit** wie bei P: (p), (r), (e), (n), hier für Code und Prompts. S(p)2 heisst: Teile des Codes sind generiert, Code und Prompts sind veröffentlicht.

**Hinweis zur Einstufung.** Lädt jemand Daten in einen Chat, der die Auswertung selbst rechnet, entsteht Code, den niemand liest. Das ist S4, und I richtet sich nach dem Dienst.

### C – Conception (Konzeption)

Die Achse C hat dieselbe Bedeutung wie bei CLEAR. Sie bezieht sich auf Fragestellung, Hypothesen, Design und Erhebungsinstrumente wie Fragebogen und Interviewleitfaden.

- **C0** – Fragestellung, Hypothesen, Design und Instrumente sind ausschliesslich menschlich entwickelt.
- **C1** – Die KI diente bei der Konzeption als Gesprächspartnerin.
- **C2** – Einzelne Teile wurden von der KI ausgearbeitet, etwa ein Fragebogen oder ein Interviewleitfaden.
- **C3** – Die Konzeption wurde umfassend von der KI erzeugt.

### A – Attribution (Ausweisung)

Die Achse A hat dieselbe Bedeutung wie bei CLEAR. Sie nennt:

- die Modelle und Werkzeuge mit genauer Version. Modelle ändern sich unter gleichem Namen; deshalb gehören Versionsbezeichnung oder Datum dazu.
- bei externen Diensten den Anbieter, etwa «GPT-4o (Microsoft Azure, angewendet)».
- die Art der Nutzung: angewendet, angepasst (etwa durch Fine-Tuning) oder trainiert. Bei eigenen Modellen stehen die Trainingsdaten in Klammern: «eigenes Modell (trainiert auf synthetischen Daten)».
- die Programmiersprachen.
- den Zeitraum.

Prompts, Parameter und Pakete gehören ins Repository, nicht in die Zeile.

### T – Transformation (Erhebung und Aufbereitung)

Die Achse T erfasst, was die KI mit den Daten getan hat. Sie ist eine Auswahl, keine Stufenleiter: Es stehen alle zutreffenden Kürzel, etwa T(ts, ps, an). T0 heisst: Die Daten wurden ohne KI erhoben und aufbereitet.

| Schritt | Kürzel | Was die KI tut | Beispiel |
|---|---|---|---|
| Erhebung | **(co)** Erhebung | Sie führt Interviews oder Befragungen durch, sammelt oder erfasst Daten. | Ein Chatbot führt Leitfadeninterviews. |
| Umwandlung | **(ts)** Transkription | Sie wandelt gesprochene Sprache in Text um. | Interviewaufnahmen werden verschriftet. |
| | **(oc)** Text- und Handschriftenerkennung | Sie macht gedruckten oder handschriftlichen Text maschinenlesbar. | Briefe aus einem Archiv werden erkannt. |
| | **(t)** Übersetzung | Sie übersetzt Daten in eine andere Sprache. Das Kürzel entspricht L(t) bei CLEAR. | Interviews auf Portugiesisch werden ins Deutsche übersetzt. |
| Aufbereitung | **(ps)** Pseudonymisierung | Sie erkennt Namen, Orte, Arbeitgeber und ähnliche Angaben und ersetzt oder entfernt sie. Das gilt auch, wenn das Ergebnis anonym ist. | In 40 Transkripten werden alle Personennamen durch Kürzel ersetzt. |
| | **(cl)** Bereinigung | Sie korrigiert Fehler, entfernt Doppelte und vereinheitlicht Schreibweisen. | «Zürich», «Zuerich» und «ZH» werden zu einem Wert. |
| | **(im)** Imputation | Sie schätzt fehlende Werte. | In einer Befragung fehlt bei 8 % das Einkommen; ein Modell ergänzt es. |
| | **(li)** Verknüpfung | Sie ordnet Einträge aus verschiedenen Datensätzen derselben Person oder demselben Fall zu. | Befragungsdaten werden mit Registerdaten zusammengeführt. |
| Strukturierung | **(ex)** Extraktion | Sie zieht Angaben aus Dokumenten, Bildern oder Texten heraus. | Aus 300 Studien werden Stichprobengrössen und Effekte ausgelesen. |
| | **(su)** Zusammenfassung | Sie fasst Material zusammen, mit dem weitergearbeitet wird. | Transkripte werden auf je eine Seite verdichtet. |
| | **(an)** Kodierung, Klassifikation, Annotation | Sie ordnet Daten Kategorien zu oder versieht sie mit Merkmalen. | Offene Antworten werden einem Kategoriensystem zugeordnet. |
| Auswertung | **(mo)** Modellierung | Sie erzeugt selbst Befunde, etwa durch Vorhersage, Clustering oder Themenmodelle. | Ein Modell sagt Studienabbrüche vorher. |

Einige Kürzel verdienen besondere Aufmerksamkeit:

- **(ps)** wirkt direkt auf P. Übersieht die KI einen Namen, sind die Daten nicht pseudonymisiert, obwohl P2 dasteht.
- **(im)** erzeugt Werte, die nicht erhoben wurden.
- **(su)** ersetzt Material durch eine Verdichtung. Was dort fehlt, fehlt auch in der Auswertung, wie bei E2 in CLEAR.
- **(li)** erhöht das Risiko, dass Personen wieder erkennbar werden.
- Bei **(mo)** ist die KI die Methode selbst.

**Abgrenzung zu O.** T sagt, was die KI mit den Daten getan hat; O sagt, was für Daten es sind, egal wer sie so gemacht hat. Erzeugt eine KI neue Datensätze, entsteht eine neue Art von Daten: Das gehört zu O, etwa (sy) oder (au), und A nennt das Modell. Verändert sie Werte in bestehenden Einträgen, gehört das zu T. Ein Datensatz mit imputierten Werten bleibt ein Originaldatensatz; deshalb steht die Imputation bei T.

Die Deutung der Ergebnisse wird bei CLEAR ausgewiesen (E3, E4).

### O – Origin (Herkunft und Form)

Die Achse O erfasst, woher die Daten stammen und in welcher Form mit ihnen gearbeitet wurde. Die Zahl sagt, wie weit die Daten nachgenutzt sind:

- **O0** – nur selbst erhoben oder erzeugt
- **O1** – selbst erhoben und nachgenutzt
- **O2** – nur nachgenutzt: aus Repositorien, Registern, Archiven oder dem Web

Die Formen stehen als Kürzel vor der Zahl, wie der Zusatz bei CLEAR:

- **(or)** – original: die Daten, wie sie erhoben oder übernommen wurden
- **(sc)** – scrambled: echte Werte vertauscht, maskiert oder verrauscht. Jede Zeile geht weiterhin auf einen echten Fall zurück; solche Daten sind oft nicht anonym.
- **(ag)** – aggregiert: nur zusammengefasste Werte, etwa Tabellen
- **(sy)** – synthetisch: neu erzeugte Datensätze, die die statistischen Eigenschaften echter Daten nachbilden. Keine Zeile entspricht einem echten Fall.
- **(si)** – simuliert oder modellgeneriert: ohne echte Vorlage erzeugt, etwa durch eine Simulation, durch ein Sprachmodell, das Befragte simuliert, oder als KI-Texte, die selbst Forschungsgegenstand sind
- **(au)** – augmentiert: echte Daten, ergänzt um künstlich erzeugte Varianten

Genannt werden die Form, in der die Daten vorlagen, und jede Form, die daraus entstanden ist:

| Fall | Angabe |
|---|---|
| eigene Interviews | O(or)0 |
| Daten nachgenutzt und selbst synthetisiert | O(or, sy)2 |
| einen fertigen synthetischen Datensatz nachgenutzt | O(sy)2 |
| eigene Befragung und Zahlen aus der amtlichen Statistik | O(or, ag)1 |
| eigene Simulation | O(si)0 |

Ob synthetische Daten selbst erzeugt oder übernommen wurden, zeigt sich daran, ob (or) mitsteht.

### R – Responsibility (Rechenschaft)

Die Achse R hat dieselbe Bedeutung wie bei CLEAR. Sie macht sichtbar, ob ein Mensch die Ergebnisse der KI geprüft hat. Verantwortlich für ein Ergebnis bleibt immer, wer es veröffentlicht, nicht die KI.

- **R1** – Die Ergebnisse der KI wurden vollständig geprüft und werden vom Menschen verantwortet.
- **R2** – Sie wurden stichprobenartig geprüft und werden daher nicht vollständig verantwortet.
- **R3** – Sie wurden ungeprüft verwendet, mit dem Risiko, sie trotzdem verantworten zu müssen.

**Zusatz (v) – validiert.** Die Ergebnisse wurden nicht nur angesehen, sondern nach einem festen Verfahren geprüft, und die Kennzahlen sind dokumentiert. Zum Beispiel:

- 10 % der KI-Kodierungen werden von Hand nachkodiert und die Übereinstimmung berechnet.
- Ein Modell wird an Testdaten geprüft, die es nicht kannte, und die Trefferquote wird festgehalten.
- Code wird mit automatischen Tests geprüft.

R(v)2 heisst: stichprobenartig, aber systematisch validiert. In der Forschung ist das häufig der realistische und gute Fall, wenn eine KI tausende Einträge verarbeitet hat.

## X: nicht zutreffend

Was in einer Forschung nicht vorkommt, wird mit X markiert:

- **SX** – Es gibt keinen Code.
- **PX, TX, OX** – Es gibt keine Daten.
- **IX** – Keine KI hatte Zugriff auf die Daten.

SX ist etwas anderes als S0: Bei S0 gibt es Code, aber er wurde ohne KI geschrieben. X ist keine Lücke, sondern eine Auskunft. C, A und R kommen in jeder Forschung vor und brauchen kein X.

## Notation

```
PISCATOR (Rolle): P(…)?, I(…)?, S(…)?, C?, A: Modelle, Sprachen, Zeitraum, T(…), O(…)?, R(…)?
```

- Zusätze stehen wie bei CLEAR vor der Zahl: P(s, n)3, I(CH)2, S(p)2, O(or, sy)0, R(v)2.
- Bei P, I, S, C und R steht die höchste erreichte Stufe.
- Bei T und bei den Formen von O stehen alle zutreffenden Kürzel.
- In Klammern hinter PISCATOR steht, wer die Angabe macht und verantwortet: eine Person, ein Projektteam oder ein Labor.

## Mehrere Arbeitsschritte

Unterscheiden sich Arbeitsschritte stark in Personenbezug oder Infrastruktur, erhält jeder Schritt eine eigene Zeile. Die Klammer nennt dann Rolle und Schritt: «PISCATOR (Projektteam, Training)». So entsteht nicht der Eindruck, identifizierbare Daten seien bei einem externen Dienst gewesen, wenn dort nur synthetische oder pseudonymisierte lagen.

## Wo die Kennzeichnung steht

- Artikel und Buch: im Methodenteil oder bei den Angaben zur Datenverfügbarkeit
- Daten- und Code-Repository: im README
- Abschlussarbeit: neben der Selbständigkeitserklärung
- Datenmanagementplan und Forschungsantrag: als geplante Nutzung

Die CLEAR-Zeile steht wie gewohnt am Schluss des Textes oder im Impressum.

## Beispiele

**Interviewstudie.** Eine Soziologin führt zwanzig Interviews zum Leben mit einer chronischen Erkrankung. Sie transkribiert die Aufnahmen mit noScribe auf dem eigenen Rechner und prüft jedes Transkript gegen die Aufnahme. Kodiert wird von Hand, Skripte gibt es keine. Die Daten werden nicht veröffentlicht.

Identifizierbare Gesundheitsdaten, nicht veröffentlicht (P(s, n)3), aber nur lokal verarbeitet (I0). Code gibt es keinen (SX). Die KI hat ausschliesslich transkribiert (T(ts)), und zwar selbst erhobene Originaldaten (O(or)0). Jedes Transkript wurde geprüft (R1).

```
PISCATOR (Autorin): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, angewendet), 03–09/2026, T(ts), O(or)0, R1
```

**Befragung mit synthetischer Fassung.** Ein Projektteam wertet eine eigene Befragung aus. Die pseudonymisierten Daten liegen auf einem Server der Hochschule. Dort kodiert ein Sprachmodell die offenen Antworten; 10 % werden von Hand nachkodiert und die Übereinstimmung berechnet. Die Hypothesen hat das Team mit einer KI diskutiert. Teile des Auswertungscodes schreibt ein Codeassistent, der keinen Zugriff auf die Daten hat. Ein auf den Befragungsdaten trainiertes Modell erzeugt eine synthetische Fassung, die veröffentlicht wird; die Originaldaten gibt es auf Anfrage.

Pseudonymisierte Daten (P2), synthetisch offen und im Original auf Anfrage zugänglich (p, r). Alles lief auf der Infrastruktur der Hochschule (I1); der Codeassistent zählt bei I nicht, weil er die Daten nie gesehen hat. Teile des Codes sind generiert, Code und Prompts veröffentlicht (S(p)2). Das Sprachmodell hat kodiert (T(an)), systematisch validiert an einer Stichprobe (R(v)2). Aus selbst erhobenen Originaldaten entstand eine synthetische Fassung (O(or, sy)0).

```
PISCATOR (Projektteam): P(p, r)2, I1, S(p)2, C1, A: Llama 3.3 70B (angewendet), SDV CTGAN (trainiert auf den Befragungsdaten), Claude Code (Anthropic), Python 3.13, 02–07/2026, T(an), O(or, sy)0, R(v)2
```

**Training und Anwendung in zwei Schritten.** Ein Team trainiert ein Klassifikationsmodell auf der Infrastruktur der Hochschule mit synthetischen Daten, die es zuvor ohne KI erzeugt und veröffentlicht hat. Danach wendet es das Modell lokal auf sensible, identifizierbare Daten an.

Beim Training hat das Modell nur synthetische, als anonym beurteilte Daten gesehen (P1); bei der Anwendung lief es lokal (I0) auf Daten, die nicht veröffentlicht werden (P(s, n)3). Hätte eine KI die synthetischen Daten aus echten Daten erzeugt, käme eine dritte Zeile hinzu.

```
PISCATOR (Projektteam, Training): P(p)1, I1, S(p)2, C1, A: eigenes Klassifikationsmodell (trainiert auf synthetischen Daten), Python 3.13, 03–05/2026, T0, O(sy)0, R(v)2
PISCATOR (Projektteam, Anwendung): P(s, n)3, I0, S(p)2, C1, A: eigenes Klassifikationsmodell (angewendet), Python 3.13, 06–08/2026, T(an), O(or)0, R(v)2
```

**Statistik im Chat.** Eine Ökonomin lädt Tabellen der amtlichen Statistik in einen Chat, der die Auswertung selbst rechnet. Sie nutzt ein privates Konto und rechnet drei Ergebnisse von Hand nach.

Die Daten haben keinen Personenbezug und sind veröffentlicht (P(p)0). Deshalb ist ein Dienst ohne Auftragsbearbeitungsvertrag hier unproblematisch (I(US)3). Der Code entstand unsichtbar im Chat (S4). Mit Personendaten wäre dieselbe Zeile ein Warnsignal.

```
PISCATOR (Autorin): P(p)0, I(US)3, S4, C0, A: ChatGPT (GPT-5, OpenAI, angewendet), 05/2026, T0, O(ag)2, R2
```

## Verhältnis zu CLEAR

PISCATOR übernimmt von CLEAR die Logik und drei Buchstaben: C, A und R bedeuten in beiden dasselbe. Bei CLEAR bezieht sich C auf den Gedankengang eines Textes, bei PISCATOR auf Fragestellung und Design der Forschung. Auch die Zusätze (p), (n) und (t) haben in beiden dieselbe Bedeutung. Die Achsen L und E kommen in PISCATOR nicht vor, damit nichts verwechselt wird.

CLEAR sagt, wie ein Text entstanden ist; PISCATOR sagt genauer, was mit den Daten geschah. Hat eine KI etwa Interviews transkribiert, steht bei CLEAR E(n)1 und bei PISCATOR T(ts).

## Bewusst nicht aufgenommen

Ob die Einwilligung der Teilnehmenden die KI-Verarbeitung abdeckt, ob besonders verletzliche Gruppen wie Minderjährige beteiligt sind und wie viel Rechenaufwand und Energie eine Auswertung brauchte, gehört in Ethikantrag und Datenmanagementplan. PISCATOR zeigt aber, wo sich Nachfragen lohnen, etwa bei P(s)3 zusammen mit I2.

## Grenzen

PISCATOR ist in der Forschungspraxis noch nicht erprobt und sicher unvollständig. Die Kennzeichnung ist eine Selbstauskunft und beweist nichts. Sie sagt nicht, ob ein Ergebnis richtig ist, sondern macht sichtbar, wo KI am Forschungsprozess beteiligt war.

---

[Zurück zur Übersicht](README.md) · [Factsheet](FACTSHEET.md) · [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) · English: [SPECIFICATION.md](SPECIFICATION.md)

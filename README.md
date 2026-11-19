# PISCATOR

**Kennzeichnung von KI-Beteiligung in der Forschung**

*Privacy · Infrastructure · Script · Conception · Attribution · Transformation · Origin · Responsibility*

Leonie Gantenbein · Version 1.0 · 2026

© 2026 Leonie Gantenbein · Lizenz: [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar unter Namensnennung der Urheberin.<br>
URL: https://github.com/LeonieGantenbein/piscator-kennzeichnung

English version: [README.en.md](README.en.md)

---

Die Nutzung von Künstlicher Intelligenz (KI) und die damit verbundenen Schnittstellen, Tools und Software sind längst in der Forschungspraxis angekommen. Sie transkribieren Interviews, kodieren offene Antworten, schreiben Auswertungscode, analysieren grosse Datensätze, clustern oder erzeugen synthetische Daten. Manchmal, und bestenfalls lokal unter sicheren Bedingungen, werden sie auch mit sensiblen Forschungsdaten trainiert. KI-Tools laufen auf dem eigenen Rechner, auf Servern der Hochschule oder bei kommerziellen Anbietern im Ausland.

Die verbreitete Nutzung von KI in der wissenschaftlichen Datenverarbeitung und beim Verfassen wissenschaftlicher Publikationen korreliert nicht mit der Deklaration eben dieser Nutzung. Im Methodenteil und letztlich in den Publikationen finden sich noch immer wenig Informationen darüber, wie KI tatsächlich eingesetzt wurde: welche Modelle wann und wie verwendet wurden, welche Daten damit bearbeitet wurden oder wie ein Text mit KI verbessert oder mitgeneriert wurde. Beim heutigen Stand sind wir bei Deklarationssätzen wie «Die Transkription erfolgte KI-gestützt» angekommen. Mit welchem Werkzeug, auf welchem Server und unter welcher Kontrolle das geschah, erfährt man nicht.

Wenn wir Forschung – ja überhaupt die Integrität von Wissenschaft und ihrer Praxis – künftig sicherstellen und beurteilen wollen, muss der Einsatz von KI-Tools spezifischer ausgewiesen werden. Ein Large Language Model (LLM), das offene Antworten kodiert, entscheidet bei jeder Antwort, welcher Kategorie sie zugeordnet wird. Ein von einer KI geschriebenes Skript legt fest, welche Fälle als Ausreisser gelten und wie fehlende Werte ersetzt werden. Ohne KI stehen solche Entscheidungen in einem Kodierleitfaden oder in selbst geschriebenem Code, und eine zweite Person kann sie prüfen. Mit jeder weiteren Schnittstelle und jedem automatisierten Schritt wächst die Gefahr, dass Forschende den Prozess ihrer eigenen Forschung nicht mehr überblicken, den Code nicht verstehen und die Analyse in ihrem Output und ihrer Qualität nicht beurteilen können. Ergebnisse, die niemand wirklich nachvollzogen hat, und eine undurchsichtige Verarbeitung im Lebenszyklus der Forschungsdaten gefährden die Qualität der Forschung, die Grundsätze guter wissenschaftlicher Praxis und das Ansehen der Forschenden.

Betroffen sind auch die Menschen, die einer Studie ihre Daten anvertraut haben. Für sie ist es nicht gleichgültig, ob ihre Interviews auf einem Laptop, der jeden Tag auf dem Weg in die Uni im Bus mitfährt, verarbeitet werden oder in einem Rechenzentrum in den USA, und ob ein Vertrag regelt, was der Anbieter mit ihren Daten tun darf.

Für die Angaben zum methodischen Vorgehen hat die Wissenschaft einen bisher bewährten Ort: den Methodenteil. Dort steht, mit welchen Daten, Instrumenten und Verfahren ein Ergebnis zustande kam, damit andere es prüfen können. KI gehört genauso dorthin wie jedes andere Instrument. Viele Verlage und Hochschulen verlangen inzwischen, den Einsatz von KI offenzulegen, geben dafür aber meist keine einheitliche Form vor. Schlimmstenfalls wird – aus einer bürokratischen und ressourcenorientierten Perspektive – der ganze Chatverlauf mit einem LLM verlangt, das am Prozess beteiligt war. Die Angaben zur KI-Nutzung fallen bisher von Studie zu Studie verschieden aus, Wichtiges fehlt oft, und vergleichen lassen sie sich kaum. Eine gemeinsame Form würde es erleichtern, die eingesetzten Werkzeuge auszuweisen und Praktiken zu vergleichen. Bislang ist auch das Bewusstsein der Forschenden noch nicht ausgereift, welche Fragen eine KI-Kennzeichnung beantworten soll. Eine solche Kennzeichnung soll deshalb alle wichtigen Angaben abfragen. Sie muss mit wenig Aufwand auszufüllen, beim Schreiben wie beim Lesen verständlich sein und trotzdem genug aussagen.

PISCATOR ist mein Vorschlag für eine solche Form. [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) kennzeichnet, wie KI an einem Text beteiligt war; PISCATOR überträgt diesen Ansatz auf die Forschungspraxis. Acht kurze Angaben in Form der Buchstaben von PISCATOR beantworten acht Fragen:

- **P – Privacy** (deutsch: Privatsphäre): Beziehen sich die Daten auf Personen?
- **I – Infrastructure** (deutsch: Infrastruktur): Wo lief die KI?
- **S – Script** (deutsch: Skript): Wie viel hat sie zum Code beigetragen?
- **C – Conception** (deutsch: Konzept): Wie viel hat sie zur Fragestellung und zum Design beigetragen?
- **A – Attribution** (deutsch: Anwendungen): Welche Modelle und Werkzeuge wurden genutzt?
- **T – Transformation** (deutsch: Transformation): Was hat die KI mit den Daten gemacht?
- **O – Origin** (deutsch: Ursprung): Woher stammen die Daten, und welcher Art sind sie?
- **R – Responsibility** (deutsch: Verantwortung): Hat ein Mensch die Ergebnisse der KI geprüft?

«Piscator» ist das lateinische Wort für Fischer. Bei der Fangmeldung wird gefragt, was, wo, womit und wann gefangen wurde; wer fischt, trägt es in wenige feste Felder ein. Die Meldung ist kurz und immer gleich aufgebaut; gerade deshalb wird sie ausgefüllt. Eine solche Fangmeldung ist unscheinbar, aber nicht trivial: Aus vielen Meldungen entsteht ein Bild davon, was in einem Gewässer geschieht, was gefangen wird und mit welchen Methoden. Eine einzelne PISCATOR-Zeile weist aus, wo und wie KI an einem Projekt mitgearbeitet hat. Viele solche Zeilen können wiederum zeigen, wie sich die Forschungspraxis verändert.

Der Name PISCATOR verweist also auf die Fangmeldung als Vorbild. Er kann auch an den Fischerring erinnern, den *Anulus Piscatoris*, mit dem päpstliche Schreiben bis 1842 gesiegelt wurden. Ein Siegel zeigt, wer für ein Dokument einsteht. Bei PISCATOR übernimmt das, wie bei CLEAR, die Angabe R – Responsibility, also Verantwortung.

Einige Angaben berühren eine Frage, die die Forschung schon lange beschäftigt: Wie offen sollen Daten sein? Open Science will Daten, Code und Prompts zugänglich machen, damit andere ein Ergebnis prüfen können, nach dem Grundsatz «so offen wie möglich, so geschlossen wie nötig». Der Datenschutz verlangt, Personendaten nur so weit zu verarbeiten und weiterzugeben, wie es der Zweck erfordert. PISCATOR enthält deshalb sowohl Angaben zum Personenbezug der Daten als auch dazu, wie offen mit den Daten gearbeitet wurde: Es weist aus, wie stark die Daten auf Personen verweisen, wo sie verarbeitet wurden und ob Daten und Code zugänglich sind.

PISCATOR macht sichtbar, an welchen Stellen des Forschungsprozesses KI beteiligt war. So können andere ein Ergebnis einordnen, nachvollziehen und, wo möglich, wiederholen. Wer eine Studie begutachtet, in einer Ethikkommission sitzt oder Forschungsdaten betreut, sieht damit in nur einer Zeile, wie und mit welchen Tools geforscht wurde.

Wer mit PISCATOR Forschung veröffentlicht, gibt beide Angaben an: PISCATOR für das Vorgehen im Methodenteil, CLEAR für den Text, sofern KI-Tools auch bei der Herstellung und Bearbeitung des Textes genutzt wurden. Die Verantwortung für ein Ergebnis trägt immer, wer es veröffentlicht. Die Verantwortung (R) steht deshalb sowohl bei CLEAR als auch bei PISCATOR am Ende der Kennzeichnung.

> **Verhältnis zu CLEAR.** PISCATOR ist aufgebaut wie CLEAR und übernimmt die Buchstaben C, A und R sowie die Zusätze (p), (n) und (t). Wer CLEAR kennt, kann PISCATOR lesen.

## Kultur vor Kennzeichnung

Eine Kennzeichnung hilft nur dort, wo Offenheit nicht bestraft wird. Wer heute offenlegt, dass ein Sprachmodell Interviews kodiert oder ein Skript geschrieben hat, muss damit rechnen, dass die Studie als weniger sorgfältig gilt. Wer angibt, dass Daten bei einem externen Anbieter verarbeitet wurden, macht sich angreifbar. Solange eine ehrliche Angabe schadet, kennzeichnet nur, wer es sich leisten kann. Für alle anderen bleibt Schweigen die vernünftige Wahl.

Deshalb braucht PISCATOR zuerst eine Verständigung darüber, wie die Forschung mit KI umgehen will. Eine PISCATOR-Zeile ist eine Auskunft, kein Geständnis. Wer eine Studie begutachtet, sollte sie lesen wie einen Methodenteil: als Grundlage für Fragen, nicht als Beleg für Nachlässigkeit. Dazu gehört auch, zu unterscheiden. Eine lokale, vollständig geprüfte Transkription ist etwas anderes als ein Sprachmodell, das sensible Daten ungeprüft bei einem Anbieter in den USA kodiert. Wer beides pauschal «KI-gestützt» nennt, macht Ehrlichkeit teuer. Und wenn eine Angabe ein Problem sichtbar macht, ist das ein Anlass zur Korrektur. Gerade dafür ist die Kennzeichnung da.

Die Wissenschaft hat für diese Verständigung bessere Voraussetzungen als jeder andere Bereich. Sie ist seit langem führend darin, ihr Vorgehen offenzulegen und sich der Kritik zu stellen. Methodenteil, Begutachtung und Replikation gehören zu ihrem Selbstverständnis. Angaben zu Interessenkonflikten, zur Verfügbarkeit von Daten oder zu den Beiträgen der einzelnen Autorinnen und Autoren sind in vielen Fächern längst Routine. Die meisten dieser Regeln hat sich die Forschung selbst gegeben, weil Ergebnisse überprüfbar sein müssen. Warum also sollte sie nicht auch bei der KI den ersten Schritt machen?

Gelingt das, kann die Forschung zeigen, dass Offenheit Vertrauen schafft. Wirksam wird PISCATOR erst, wenn auch das Fehlen einer Angabe etwas aussagt: wenn man bei einer empirischen Studie nachfragt, warum sie nicht ausweist, wo und wie KI beteiligt war.

## Für welche Forschung

PISCATOR richtet sich an empirische Forschung, quantitative wie qualitative, die Daten erhebt, aufbereitet oder mit Code auswertet. Dazu gehören Interviewstudien und Befragungen, Experimente und Messreihen, Korpus- und Archivarbeit, Modellierungen und Simulationen. Theoretische, historische oder hermeneutische Arbeiten ohne eigene Daten und ohne eigenen Code brauchen keine PISCATOR-Angabe; für ihren Text genügt CLEAR.

Nicht jede Studie braucht alle acht Angaben. Was nicht vorkommt, wird mit X markiert; SX heisst zum Beispiel, dass kein Code geschrieben wurde.

## Kurzreferenz

Die acht Angaben auf einen Blick:

| Achse | Gegenstand | Angabe |
|---|---|---|
| **P** – Privacy | Personenbezug der Daten, die eine KI verarbeitet hat | P0 kein Personenbezug · P1 anonymisiert · P2 pseudonymisiert · P3 identifizierbar; Zusatz (s) für besonders schützenswerte Daten; Zugänglichkeit (p) veröffentlicht · (r) eingeschränkt · (e) geplant · (n) nicht veröffentlicht |
| **I** – Infrastructure | Wo die KI lief, die Zugriff auf die Daten hatte | I0 lokal · I1 geschützte Infrastruktur der Institution · I2 externer Dienst mit Auftragsbearbeitungsvertrag · I3 externer Dienst nur mit allgemeinen Nutzungsbedingungen; Zusatz: Land des Serverstandorts, etwa (CH) |
| **S** – Script | KI beim Programmieren | S0 ohne KI · S1 Hilfe · S2 Teile generiert · S3 weitgehend generiert · S4 vollständig generiert; Zugänglichkeit von Code und Prompts wie bei P |
| **C** – Conception | Fragestellung, Hypothesen, Design, Instrumente | C0 ausschliesslich menschlich · C1 KI als Gesprächspartnerin · C2 einzelne Teile von der KI ausgearbeitet · C3 umfassend von der KI erzeugt |
| **A** – Attribution | Ausweisung der Werkzeuge | Modelle und Werkzeuge mit Version, Anbieter und Art der Nutzung (angewendet, angepasst, trainiert), Programmiersprachen, Zeitraum |
| **T** – Transformation | Was die KI mit den Daten getan hat | (co) Erhebung · (ts) Transkription · (oc) Texterkennung · (t) Übersetzung · (ps) Pseudonymisierung · (cl) Bereinigung · (im) Imputation · (li) Verknüpfung · (ex) Extraktion · (su) Zusammenfassung · (an) Kodierung · (mo) Modellierung; T0 ohne KI |
| **O** – Origin | Herkunft und Form der Daten | O0 nur selbst erhoben · O1 selbst erhoben und nachgenutzt · O2 nur nachgenutzt; Formen (or) original · (sc) scrambled · (ag) aggregiert · (sy) synthetisch · (si) simuliert · (au) augmentiert |
| **R** – Responsibility | Prüfung der KI-Ergebnisse | R1 vollständig geprüft und verantwortet · R2 stichprobenartig geprüft · R3 ungeprüft; Zusatz (v) systematisch validiert |

```
PISCATOR (Rolle): P(…)?, I(…)?, S(…)?, C?, A: Modelle, Sprachen, Zeitraum, T(…), O(…)?, R(…)?
```

**Regeln für die Einstufung.**

- Zusätze stehen wie bei CLEAR vor der Zahl: P(s, n)3, I(CH)2, S(p)2, O(or, sy)0, R(v)2.
- Bei P, I, S, C und R steht die höchste erreichte Stufe. Bei T und den Formen von O stehen alle zutreffenden Kürzel.
- X steht, wenn etwas in der Forschung nicht vorkommt: SX ohne Code; PX, TX und OX ohne Daten; IX, wenn keine KI Zugriff auf die Daten hatte.
- T sagt, was die KI mit den Daten getan hat; O sagt, was für Daten es sind. Erzeugt eine KI neue Datensätze, etwa synthetische oder augmentierte, gehört das zu O; verändert sie Werte in bestehenden Einträgen, etwa bei einer Imputation, gehört das zu T.
- Zu I zählt jede KI mit Zugriff auf die Daten, auch ein Codeassistent, der Datendateien lesen kann. Massgebend ist, wo das Modell tatsächlich läuft, nicht wo ein Programm installiert ist.
- Unterscheiden sich Arbeitsschritte stark in Personenbezug oder Infrastruktur, erhält jeder Schritt eine eigene Zeile, etwa «PISCATOR (Projektteam, Training)».
- In Klammern steht, wer die Angabe macht und verantwortet: eine Person, ein Projektteam oder ein Labor.

**Wo die Kennzeichnung steht.**

- Artikel und Buch: im Methodenteil oder bei den Angaben zur Datenverfügbarkeit
- Daten- und Code-Repository: im README
- Abschlussarbeit: neben der Selbständigkeitserklärung
- Datenmanagementplan und Forschungsantrag: als geplante Nutzung

Die CLEAR-Zeile steht wie gewohnt am Schluss des Textes oder im Impressum.

## Beispiele

Vier Beispiele zeigen, wie aus einer konkreten Studie eine Angabe wird.

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

Das Kapitel [«Spezifikation»](SPEZIFIKATION.md) erklärt alle Achsen ausführlich und gibt Hinweise zur Einstufung. Das [Factsheet](FACTSHEET.md) fasst alle Kürzel zusammen und enthält einen Prompt, mit dem ein Sprachmodell eine Angabe vorschlagen kann.

## Zusammen mit CLEAR

In einer Publikation stehen beide Angaben: PISCATOR im Methodenteil, CLEAR am Schluss des Textes. Dazu ein Beispiel: Für die Interviewstudie hält CLEAR fest, dass der Gedankengang von der Autorin stammt und dass die KI die Sprache geglättet und ihr eigenes, unveröffentlichtes Material zugänglich gemacht hat. PISCATOR hält fest, was mit den Interviews geschah. Der Buchstabe C bezieht sich bei CLEAR auf den Gedankengang des Textes, bei PISCATOR auf Fragestellung und Design der Studie:

```
CLEAR (Autorin): C0, L2, E(n)1, A: noScribe (Whisper large-v3), ChatGPT (GPT-5), 03–10/2026, R1
PISCATOR (Autorin): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, angewendet), 03–09/2026, T(ts), O(or)0, R1
```

## Was Institutionen einfordern können

PISCATOR ist zuerst eine Selbstauskunft. Es lässt sich aber auch umkehren: Wer Forschung betreut, prüft, fördert oder veröffentlicht, kann mit denselben Angaben festlegen, was erwartet wird. Statt Werkzeuge zu verbieten, benennt eine Institution Stufen, und alle wissen, woran sie sind.

**Hochschule und Institut.** Eine Hochschule kann in ihren Richtlinien zur guten wissenschaftlichen Praxis und zu Abschlussarbeiten verlangen, dass jede empirische Arbeit eine PISCATOR-Zeile im Methodenteil trägt. Sie kann festlegen, dass jede Kodierung durch eine KI, die in Ergebnisse eingeht, vollständig oder systematisch geprüft wird (R1 oder R(v)), und dass identifizierbare oder besonders schützenswerte Daten (P3, P(s)) nur lokal, auf der eigenen Infrastruktur oder bei Diensten mit Auftragsbearbeitungsvertrag verarbeitet werden (I0 bis I2). Wer das verlangt, muss solche Infrastruktur allerdings auch bereitstellen und sagen, welche Dienste als I1 oder I2 gelten.

**Ethikkommission und Förderorganisation.** Ob die Einwilligung der Teilnehmenden die KI-Verarbeitung abdeckt, ob besonders verletzliche Gruppen wie Minderjährige beteiligt sind und wie viel Rechenaufwand und Energie eine Auswertung brauchte, erfasst PISCATOR bewusst nicht. Das gehört in den Ethikantrag und den Datenmanagementplan. Dort kann aber eine geplante PISCATOR-Zeile stehen. Sie zeigt auf einen Blick, wo sich Nachfragen lohnen, etwa bei P(s)3 zusammen mit I2 oder I3. Weicht die spätere Zeile in der Publikation davon ab, lässt sich das begründen.

**Zeitschrift und Verlag.** In den Hinweisen für Autorinnen und Autoren kann stehen, dass PISCATOR in den Methodenteil gehört und CLEAR an den Schluss. Wer eine Open-Science-Politik verfolgt, kann zugängliche Daten und zugänglichen Code als Regelfall erwarten (P(p) oder P(r), S(p)) und Ausnahmen begründen lassen. Wer begutachtet, erhält mit der Zeile einen Ausgangspunkt für die eigenen Fragen.

Für alle Institutionen gilt dasselbe wie für die Kennzeichnung selbst: Wer Offenlegung verlangt, darf sie nicht bestrafen. Eine ausgewiesene Schwäche ist besser als eine verschwiegene. Chatverläufe oder Prompt-Protokolle pauschal einzufordern, schafft Bürokratie und neue Datenschutzprobleme, ohne die Beurteilung zu erleichtern. Am meisten bewirkt eine Institution, wenn ihre eigenen Forschenden, Herausgeberinnen und Gutachter mit gutem Beispiel vorangehen.

## Kritische Einwände

PISCATOR muss sich Einwänden stellen. Die wichtigsten sind hier mit einer Antwort versammelt.

**«Wer will, kann lügen.»** Das stimmt. PISCATOR beruht auf Selbstauskunft, wie Angaben zur Autorschaft oder zu Interessenkonflikten. Auch diese lassen sich fälschen und sind trotzdem unverzichtbar, weil sie Verantwortung zuordnen. Eine falsche Angabe lässt sich überprüfen und beanstanden. Schweigen lässt sich nicht beanstanden.

**«Das ist zusätzliche Bürokratie.»** Die Kennzeichnung ist eine Zeile. Sie ersetzt Beschreibungen, die heute ohnehin verlangt werden, aber uneinheitlich ausfallen. Bürokratisch wird es eher dort, wo ganze Chatverläufe eingefordert werden.

**«Eine Zeile kann einen Forschungsprozess nicht abbilden.»** Das soll sie auch nicht. Wie die Fangmeldung hält sie fest, was andere wissen müssen, um gezielt nachzufragen. Die Einzelheiten gehören weiterhin in den Methodenteil. Unterscheiden sich Arbeitsschritte stark, erhält jeder eine eigene Zeile.

**«Die Stufen sind unscharf.»** Ob ein Skript S2 oder S3 ist, verlangt ein Urteil. Das ist kein Mangel, denn auch die Beschreibung einer Methode beruht auf Einschätzungen. Die Spezifikation gibt Hinweise und Beispiele. Strittige Fälle sind ein Anlass für das Gespräch, etwa in der Begutachtung.

**«Die Angabe macht angreifbar.»** Wer bei identifizierbaren Daten I3 angibt, legt ein Problem offen. Genau darin liegt der Nutzen: Was sichtbar ist, lässt sich beheben. Damit das funktioniert, darf Offenheit nicht bestraft werden. Technische Einzelheiten, die ein Sicherheitsrisiko wären, verlangt PISCATOR nicht; die Angabe nennt nur das Land und die Art des Vertrags.

**«PISCATOR veraltet mit den Werkzeugen.»** Die Achsen beschreiben Arbeitsschritte und Verantwortung, keine Produkte. Welche Werkzeuge im Einsatz waren, steht bei A und darf sich ändern. Neue Arbeitsweisen werden neue Kürzel brauchen; deshalb trägt PISCATOR eine Versionsnummer.

## Status

PISCATOR ist ein Vorschlag in einer ersten Fassung. Es baut auf CLEAR auf, ist in der Forschungspraxis aber noch nicht erprobt und sicher unvollständig. Wie jede Selbstauskunft ist es darauf angewiesen, dass die Angaben ehrlich gemacht werden; überprüfen lassen sie sich nur zum Teil. Rückmeldungen aus Forschung, Datenmanagement und Ethikkommissionen helfen, PISCATOR weiterzuentwickeln, ausdrücklich auch Einwände und Fälle, die sich nicht einordnen lassen. Ein Feedback dazu ist möglich über die [«Issues» dieses Repositorys](https://github.com/LeonieGantenbein/piscator-kennzeichnung/issues).

## Zitieren

Gantenbein, Leonie (2026): PISCATOR – Kennzeichnung von KI-Beteiligung in der Forschung. Version 1.0. https://github.com/LeonieGantenbein/piscator-kennzeichnung

Maschinenlesbare Zitierangaben: [CITATION.cff](CITATION.cff) (auf GitHub über «Cite this repository»)

## Lizenz

© 2026 Leonie Gantenbein. [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar, unter Namensnennung von Leonie Gantenbein.

---

Theorie und Spezifikation – `CLEAR (Leonie Gantenbein): C1, L3, E(p)2, A: Claude Opus 5.5, 11/2026, R1`<br>
PISCATOR entfällt: Dieser Text beruht nicht auf eigener Datenverarbeitung.

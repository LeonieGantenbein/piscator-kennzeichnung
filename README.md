# PISCATOR

**Kennzeichnung von KI-Beteiligung in der Forschung**

*Privacy · Infrastructure · Script · Conception · Attribution · Transformation · Origin · Responsibility*

Leonie Gantenbein · Version 1.0 · 2026

© 2026 Leonie Gantenbein · Lizenz: [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar unter Namensnennung der Urheberin.<br>
URL: https://github.com/LeonieGantenbein/piscator-kennzeichnung

English version: [README.en.md](README.en.md)

---

In der empirischen Forschung ist KI oft beteiligt, lange bevor ein Text entsteht. Sie transkribiert Interviews, kodiert offene Antworten, schreibt Auswertungscode, erzeugt synthetische Daten oder wird selbst als Modell trainiert. Sie läuft auf dem eigenen Rechner, auf Servern der Hochschule oder bei externen Anbietern. Wer ein Ergebnis beurteilen will, muss das wissen. Und für die Menschen, deren Daten verarbeitet wurden, macht es einen Unterschied, wo das geschah.

[CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) kennzeichnet, wie KI an einem Text beteiligt war. PISCATOR kennzeichnet, wie sie an der Forschung beteiligt war, auf der ein Text beruht. Acht kurze Angaben halten fest, wie weit die Daten auf Personen verweisen, wo die KI lief, was sie zum Code beitrug, wer Fragestellung und Design entwickelt hat, welche Modelle und Werkzeuge im Einsatz waren, was die KI mit den Daten getan hat, woher die Daten stammen und wer die Ergebnisse der KI geprüft hat.

Vorbild ist die Fangmeldung. Sie hält in wenigen festen Angaben fest, was, wo, womit und wann gefangen wurde. Sie ist knapp und standardisiert, und gerade deshalb wird sie im Alltag tatsächlich ausgefüllt. PISCATOR soll ebenso einfach sein: ein Einzeiler, der im Methodenteil Platz findet.

Eine solche Angabe beansprucht nicht, ein Ergebnis zu beglaubigen. Ludwik Fleck und Thomas S. Kuhn haben gezeigt, dass wissenschaftliches Wissen nicht einfach anwächst, bis alles aufgedeckt ist. Es entsteht in Denkstilen und Paradigmen, mit bestimmten Instrumenten und Verfahren. PISCATOR macht sichtbar, welche dieser Verfahren eine KI mitgetragen hat. Das hilft, einen Befund einzuordnen, nachzuvollziehen und, wo möglich, zu wiederholen.

Wer wissenschaftlich publiziert, gibt beide Angaben an: PISCATOR für den Forschungsprozess, CLEAR für den Text.

> **Zwei Angaben, ein Prinzip.** PISCATOR übernimmt von CLEAR die Logik, drei Buchstaben und die Zusätze (p), (n) und (t): Sie bedeuten in beiden dasselbe. Wer CLEAR kennt, kann PISCATOR lesen. Und wie bei CLEAR gilt: Verantwortlich für ein Ergebnis bleibt, wer es veröffentlicht, nicht die KI.

## Für welche Forschung

PISCATOR richtet sich an empirische Forschung, die Daten erhebt, aufbereitet, kodiert oder mit Code auswertet, quantitativ wie qualitativ: Interviewstudien und Befragungen, Experimente und Messreihen, Korpus- und Archivarbeit, Modellierungen und Simulationen. Arbeiten ohne eigene Datenverarbeitung, etwa theoretische, historische oder hermeneutische, kennzeichnen ihren Text mit CLEAR. Eine PISCATOR-Angabe ist dort nicht nötig.

Oft betrifft eine Studie nur einen Teil der Angaben. Was in einer Forschung nicht vorkommt, wird mit X markiert: SX heisst, es gibt keinen Code. Das ist etwas anderes als S0: Dort gibt es Code, aber er wurde ohne KI geschrieben. X ist keine Lücke, sondern eine Auskunft.

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

Zusätze stehen wie bei CLEAR vor der Zahl. Bei P, I, S, C und R steht die höchste erreichte Stufe; bei T und den Formen von O stehen alle zutreffenden Kürzel. Unterscheiden sich Arbeitsschritte stark in Personenbezug oder Infrastruktur, erhält jeder Schritt eine eigene Zeile.

**Wo die Kennzeichnung steht.**

- Artikel und Buch: im Methodenteil oder bei den Angaben zur Datenverfügbarkeit
- Daten- und Code-Repository: im README
- Abschlussarbeit: neben der Selbständigkeitserklärung
- Datenmanagementplan und Forschungsantrag: als geplante Nutzung

Die CLEAR-Zeile steht wie gewohnt am Schluss des Textes oder im Impressum.

**Zwei Beispiele.** Eine Soziologin führt zwanzig Interviews zum Leben mit einer chronischen Erkrankung, transkribiert sie mit noScribe auf dem eigenen Rechner, prüft jedes Transkript und kodiert von Hand:

```
PISCATOR (Autorin): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, angewendet), 03–09/2026, T(ts), O(or)0, R1
```

Ein Projektteam lässt die offenen Antworten einer eigenen Befragung auf dem Hochschulserver von einem Sprachmodell kodieren, validiert die Kodierung an einer Stichprobe und veröffentlicht eine synthetische Fassung der Daten:

```
PISCATOR (Projektteam): P(p, r)2, I1, S(p)2, C1, A: Llama 3.3 70B (angewendet), SDV CTGAN (trainiert auf den Befragungsdaten), Claude Code (Anthropic), Python 3.13, 02–07/2026, T(an), O(or, sy)0, R(v)2
```

Alle Achsen mit Erklärungen, Hinweise zur Einstufung und weitere Beispiele, etwa für ein Modell, das in zwei Schritten trainiert und angewendet wird, finden Sie im Kapitel [«Spezifikation»](SPEZIFIKATION.md). Das [Factsheet](FACTSHEET.md) fasst alle Kürzel zusammen und enthält einen Prompt, mit dem ein Sprachmodell eine Angabe vorschlägt.

## Zusammen mit CLEAR

In einer Publikation stehen beide Angaben, PISCATOR im Methodenteil, CLEAR am Schluss eines Artikels oder im Impressum eines Buches. Für die Interviewstudie sähe das so aus:

```
CLEAR (Autorin): C0, L2, E(n)1, A: noScribe (Whisper large-v3), ChatGPT (GPT-5), 03–10/2026, R1
PISCATOR (Autorin): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, angewendet), 03–09/2026, T(ts), O(or)0, R1
```

CLEAR sagt, wie der Text entstanden ist: Der Gedankengang ist der eigene, die KI hat die Sprache geglättet und eigenes, unpubliziertes Material zugänglich gemacht. PISCATOR sagt genauer, was dabei mit den Daten geschah. Bei CLEAR bezieht sich C auf den Gedankengang des Textes, bei PISCATOR auf Fragestellung und Design der Forschung.

## Status

PISCATOR ist ein Vorschlag. Er baut auf CLEAR auf, wurde aber noch in keiner Praxis erprobt und ist sicher noch unvollständig. Rückmeldungen aus Forschung, Datenmanagement und Ethikkommissionen sind willkommen, am besten über die [Issues dieses Repositorys](https://github.com/LeonieGantenbein/piscator-kennzeichnung/issues).

## Zum Namen

Piscator ist lateinisch und heisst Fischer, daher das Vorbild der Fangmeldung. Der Name erinnert zudem an den Fischerring, den *Anulus Piscatoris*, mit dem päpstliche Dokumente bis 1842 gesiegelt wurden. Ein Siegel macht sichtbar, wer für ein Dokument einsteht. Diese Aufgabe übernimmt bei PISCATOR wie bei CLEAR die Angabe R.

## Zitieren

Wenn Sie PISCATOR verwenden oder weiterentwickeln, zitieren Sie bitte:

Gantenbein, Leonie (2026): PISCATOR – Kennzeichnung von KI-Beteiligung in der Forschung. Version 1.0. https://github.com/LeonieGantenbein/piscator-kennzeichnung

Maschinenlesbare Zitierangaben: [CITATION.cff](CITATION.cff) (auf GitHub über «Cite this repository»)

## Lizenz

© 2026 Leonie Gantenbein. [CC BY 4.0](LICENSE.md) – frei nutzbar und veränderbar, unter Namensnennung von Leonie Gantenbein.

---

Theorie und Spezifikation – `CLEAR (Autorin): C1, L4, E(p)2, A: Claude Opus 5.5, 11/2026, R1`<br>
PISCATOR entfällt: Dieser Text beruht nicht auf eigener Datenverarbeitung.

# PISCATOR

**Labelling AI Involvement in Research**

*Privacy · Infrastructure · Script · Conception · Attribution · Transformation · Origin · Responsibility*

Leonie Gantenbein · Version 1.0 · 2026

© 2026 Leonie Gantenbein · Licence: [CC BY 4.0](LICENSE.md) – free to use and adapt with attribution to the author.<br>
URL: https://github.com/LeonieGantenbein/piscator-kennzeichnung<br>
DOI: [10.5281/zenodo.24372962](https://doi.org/10.5281/zenodo.24372962)

Deutsche Fassung: [README.md](README.md)

---

The use of artificial intelligence (AI), and of the interfaces, tools and software that come with it, has long since arrived in research practice. These tools transcribe interviews, code open-ended responses, write analysis code, analyse large datasets, cluster data or generate synthetic data. Sometimes, and ideally locally under secure conditions, they are also trained on sensitive research data. AI tools run on researchers’ own computers, on university servers or with commercial providers abroad.

The widespread use of AI in scientific data processing and in writing scientific publications is not matched by the declaration of this use. Methods sections, and publications in general, still contain little information on how AI was actually used: which models were used, when and how, which data were processed with them, or how a text was improved or co-generated with AI. As things stand, we have arrived at declarations such as “Transcription was AI-assisted”. Which tool was used, on which server and under what control remains unknown.

If we want to ensure and assess research – indeed the integrity of science and its practice as a whole – in the future, the use of AI tools must be declared more specifically. A large language model (LLM) that codes open-ended responses decides, for every response, which category it belongs to. A script written by an AI determines which cases count as outliers and how missing values are replaced. Without AI, such decisions are set down in a coding manual or in code the researchers wrote themselves, and a second person can check them. With every additional interface and every automated step, the risk grows that researchers lose track of the process of their own research, do not understand the code and cannot assess the output and quality of the analysis. Results that no one has really understood, and opaque processing during the research data life cycle, put at risk the quality of research, the principles of good scientific practice and the standing of researchers.

The people who entrusted their data to a study are affected too. For them, it matters whether their interviews are processed on a laptop that rides the bus to the university every day or in a data centre in the United States, and whether a contract specifies what the provider may do with their data.

Science has so far had a well-established place for describing methodological procedures: the methods section. It states with which data, instruments and procedures a result was obtained, so that others can check it. AI belongs there like any other instrument. Many publishers and universities now require the use of AI to be disclosed, but most do not prescribe a common format. In the worst case – from a bureaucratic and resource-oriented perspective – the entire chat with an LLM involved in the process is demanded. Statements on AI use have so far varied from study to study, important details are often missing, and they can hardly be compared. A shared format would make it easier to declare the tools used and to compare practices. Researchers are also not yet fully aware of which questions an AI label should answer. Such a label should therefore ask for all the important information. It must take little effort to fill in, be clear to both writers and readers, and still say enough.

PISCATOR is my proposal for such a format. [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) labels how AI was involved in a text; PISCATOR transfers this approach to research practice. Eight short statements, one for each letter of PISCATOR, answer eight questions:

- **P – Privacy**: Do the data refer to persons?
- **I – Infrastructure**: Where did the AI run?
- **S – Script**: How much did it contribute to the code?
- **C – Conception**: How much did it contribute to the research question and design?
- **A – Attribution**: Which models and tools were used?
- **T – Transformation**: What did the AI do with the data?
- **O – Origin**: Where do the data come from, and what kind of data are they?
- **R – Responsibility**: Did a human check the AI’s results?

“Piscator” is the Latin word for fisherman. A catch report asks what was caught, where, with what and when; anyone who fishes enters this in a few fixed fields. The report is short and always has the same structure; that is precisely why it gets filled in. Such a catch report is inconspicuous, but not trivial: many reports together give a picture of what is happening in a body of water, what is being caught and with which methods. A single PISCATOR line declares where and how AI was involved in a project. Many such lines, in turn, can show how research practice is changing.

The name PISCATOR thus refers to the catch report as a model. It may also recall the Fisherman’s Ring, the *Anulus Piscatoris*, with which papal letters were sealed until 1842. A seal shows who stands behind a document. In PISCATOR, as in CLEAR, this is done by the statement R – Responsibility.

Some statements touch on a question that research has long been dealing with: how open should data be? Open science wants data, code and prompts to be accessible so that others can check a result, following the principle “as open as possible, as closed as necessary”. Data protection requires personal data to be processed and shared only as far as the purpose requires. PISCATOR therefore contains statements both on the personal reference of the data and on how openly the data were handled: it declares how far the data refer to persons, where they were processed and whether data and code are accessible.

PISCATOR makes visible at which points in the research process AI was involved. This allows others to place a result, follow it and, where possible, replicate it. Anyone who reviews a study, sits on an ethics committee or looks after research data can thus see in a single line how, and with which tools, the research was done.

Anyone publishing research with PISCATOR gives both statements: PISCATOR for the procedure in the methods section, CLEAR for the text, provided AI tools were also used to produce or revise the text. Responsibility for a result always lies with whoever publishes it. This is why responsibility (R) comes at the end of the label in both CLEAR and PISCATOR.

> **Relation to CLEAR.** PISCATOR is structured like CLEAR and adopts the letters C, A and R as well as the suffixes (p), (n) and (t). Anyone who knows CLEAR can read PISCATOR.

## Culture before labelling

A label only helps where openness is not penalised. Anyone who discloses today that a language model coded interviews or wrote a script must expect the study to be seen as less rigorous. Anyone who states that data were processed by an external provider becomes open to attack. As long as an honest statement does harm, only those who can afford it will label. For everyone else, silence remains the sensible choice.

PISCATOR therefore first needs a shared understanding of how research wants to deal with AI. A PISCATOR line is information, not a confession. Anyone reviewing a study should read it like a methods section: as a basis for questions, not as evidence of carelessness. This also means making distinctions. A local, fully checked transcription is something different from a language model coding sensitive data, unchecked, with a provider in the United States. Calling both “AI-assisted” makes honesty expensive. And if a statement reveals a problem, that is a reason to correct it. This is exactly what the label is for.

Science is better placed for this than any other field. It has long led the way in disclosing its procedures and exposing itself to criticism. Methods sections, peer review and replication are part of its self-understanding. Statements on conflicts of interest, data availability or the contributions of individual authors have long been routine in many disciplines. Research has given itself most of these rules because results must be verifiable. So why should it not take the first step with AI as well?

If it succeeds, research can show that openness builds trust. PISCATOR only becomes effective when the absence of a statement also says something: when people ask why an empirical study does not declare where and how AI was involved.

## Which research

PISCATOR is intended for empirical research, quantitative or qualitative, that collects, prepares or analyses data with code. This includes interview studies and surveys, experiments and measurement series, corpus and archival work, modelling and simulation. Theoretical, historical or hermeneutic work without its own data and code does not need a PISCATOR statement; CLEAR is sufficient for its text.

Not every study needs all eight statements. Anything that does not occur is marked with an X; SX, for example, means that no code was written.

## Quick reference

The eight statements at a glance:

| Axis | Subject | Statement |
|---|---|---|
| **P** – Privacy | Personal reference of the data an AI processed | P0 no personal reference · P1 anonymised · P2 pseudonymised · P3 identifiable; suffix (s) for sensitive personal data; availability (p) published · (r) restricted · (e) planned · (n) not published |
| **I** – Infrastructure | Where the AI with access to the data ran | I0 local · I1 protected infrastructure of the institution · I2 external service with a data processing agreement · I3 external service with general terms of use only; suffix: country of server location, e.g. (CH) |
| **S** – Script | AI in programming | S0 without AI · S1 assistance · S2 parts generated · S3 largely generated · S4 fully generated; availability of code and prompts as for P |
| **C** – Conception | Research question, hypotheses, design, instruments | C0 exclusively human · C1 AI as a discussion partner · C2 individual parts worked out by the AI · C3 comprehensively generated by the AI |
| **A** – Attribution | Declaration of the tools | Models and tools with version, provider and type of use (applied, adapted, trained), programming languages, period |
| **T** – Transformation | What the AI did with the data | (co) collection · (ts) transcription · (oc) text recognition · (t) translation · (ps) pseudonymisation · (cl) cleaning · (im) imputation · (li) linkage · (ex) extraction · (su) summarisation · (an) coding · (mo) modelling; T0 without AI |
| **O** – Origin | Source and form of the data | O0 own collection only · O1 own and reused data · O2 reused data only; forms (or) original · (sc) scrambled · (ag) aggregated · (sy) synthetic · (si) simulated · (au) augmented |
| **R** – Responsibility | Checking of the AI’s results | R1 fully checked and taken responsibility for · R2 spot-checked · R3 unchecked; suffix (v) systematically validated |

```
PISCATOR (role): P(…)?, I(…)?, S(…)?, C?, A: models, languages, period, T(…), O(…)?, R(…)?
```

**Rules for classification.**

- As in CLEAR, suffixes precede the number: P(s, n)3, I(CH)2, S(p)2, O(or, sy)0, R(v)2.
- For P, I, S, C and R, give the highest level reached. For T and the forms in O, list all applicable codes.
- X marks what does not occur in the research: SX without code; PX, TX and OX without data; IX if no AI had access to the data.
- T says what the AI did with the data; O says what kind of data they are. If an AI generates new records, for example synthetic or augmented ones, that belongs to O; if it changes values in existing entries, for example through imputation, that belongs to T.
- I covers every AI with access to the data, including a coding assistant that can read data files. What counts is where the model actually runs, not where a program is installed.
- If work steps differ considerably in personal reference or infrastructure, each step gets a line of its own, for example “PISCATOR (project team, training)”.
- The brackets name who makes the statement and takes responsibility for it: a person, a project team or a lab.

**Where the label goes.**

- Article and book: in the methods section or the data availability statement
- Data and code repository: in the README
- Thesis: next to the declaration of authorship
- Data management plan and grant proposal: as planned use

The CLEAR line appears as usual at the end of the text or in the imprint.

## Examples

Four examples show how a specific study becomes a statement.

**Interview study.** A sociologist conducts twenty interviews on living with a chronic illness. She transcribes the recordings with noScribe on her own computer and checks every transcript against the recording. Coding is done by hand; there are no scripts. The data are not published.

Identifiable health data, not published (P(s, n)3), but processed only locally (I0). There is no code (SX). The AI did nothing but transcribe (T(ts)), working with original data collected by the author (O(or)0). Every transcript was checked (R1).

```
PISCATOR (author): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, applied), 03–09/2026, T(ts), O(or)0, R1
```

**Survey with a synthetic version.** A project team analyses its own survey. The pseudonymised data are stored on a university server. There, a language model codes the open-ended responses; 10% are re-coded by hand and the agreement is calculated. The team discussed its hypotheses with an AI. A coding assistant without access to the data writes parts of the analysis code. A model trained on the survey data generates a synthetic version, which is published; the original data are available on request.

Pseudonymised data (P2), openly available as a synthetic version and in the original on request (p, r). Everything ran on the university’s infrastructure (I1); the coding assistant does not count for I because it never saw the data. Parts of the code were generated; code and prompts are published (S(p)2). The language model did the coding (T(an)), systematically validated on a sample (R(v)2). A synthetic version was derived from original data collected by the team (O(or, sy)0).

```
PISCATOR (project team): P(p, r)2, I1, S(p)2, C1, A: Llama 3.3 70B (applied), SDV CTGAN (trained on the survey data), Claude Code (Anthropic), Python 3.13, 02–07/2026, T(an), O(or, sy)0, R(v)2
```

**Training and application in two steps.** A team trains a classification model on the university’s infrastructure with synthetic data that it previously generated without AI and published. It then applies the model locally to sensitive, identifiable data.

During training, the model saw only synthetic data judged to be anonymous (P1); during application, it ran locally (I0) on data that will not be published (P(s, n)3). Had an AI generated the synthetic data from real data, a third line would be added.

```
PISCATOR (project team, training): P(p)1, I1, S(p)2, C1, A: own classification model (trained on synthetic data), Python 3.13, 03–05/2026, T0, O(sy)0, R(v)2
PISCATOR (project team, application): P(s, n)3, I0, S(p)2, C1, A: own classification model (applied), Python 3.13, 06–08/2026, T(an), O(or)0, R(v)2
```

**Statistics in a chat.** An economist uploads tables from official statistics to a chat that runs the analysis itself. She uses a private account and recalculates three results by hand.

The data have no personal reference and are published (P(p)0). A service without a data processing agreement is therefore unproblematic here (I(US)3). The code was produced invisibly in the chat (S4). With personal data, the same line would be a warning sign.

```
PISCATOR (author): P(p)0, I(US)3, S4, C0, A: ChatGPT (GPT-5, OpenAI, applied), 05/2026, T0, O(ag)2, R2
```

The chapter [“Specification”](SPECIFICATION.md) explains all axes in detail and gives guidance on classification. The [factsheet](FACTSHEET.en.md) summarises all codes and contains a prompt with which a language model can propose a statement.

## Together with CLEAR

A publication carries both statements: PISCATOR in the methods section, CLEAR at the end of the text. An example: for the interview study, CLEAR records that the line of thought is the author’s own and that the AI smoothed the language and made her own unpublished material accessible. PISCATOR records what happened to the interviews. In CLEAR, the letter C refers to the line of thought of the text; in PISCATOR, to the research question and design of the study:

```
CLEAR (author): C0, L2, E(n)1, A: noScribe (Whisper large-v3), ChatGPT (GPT-5), 03–10/2026, R1
PISCATOR (author): P(s, n)3, I0, SX, C0, A: noScribe (Whisper large-v3, applied), 03–09/2026, T(ts), O(or)0, R1
```

## What institutions can require

PISCATOR is first of all a self-declaration. But it can also be reversed: anyone who supervises, reviews, funds or publishes research can use the same statements to specify what is expected. Instead of banning tools, an institution names levels, and everyone knows where they stand.

**Universities and institutes.** A university can require in its guidelines on good scientific practice and on theses that every empirical study carries a PISCATOR line in the methods section. It can stipulate that any AI coding that feeds into results is fully or systematically checked (R1 or R(v)), and that identifiable or sensitive data (P3, P(s)) are processed only locally, on its own infrastructure or by services with a data processing agreement (I0 to I2). Anyone who requires this must, however, also provide such infrastructure and say which services count as I1 or I2.

**Ethics committees and funders.** PISCATOR deliberately does not record whether participants’ consent covers AI processing, whether particularly vulnerable groups such as minors are involved, or how much computing power and energy an analysis required. These belong in the ethics application and the data management plan. A planned PISCATOR line can, however, be included there. It shows at a glance where questions are worth asking, for example with P(s)3 together with I2 or I3. If the line in the later publication differs, the difference can be explained.

**Journals and publishers.** Author guidelines can state that PISCATOR belongs in the methods section and CLEAR at the end. A publisher with an open science policy can expect accessible data and code as the norm (P(p) or P(r), S(p)) and ask for exceptions to be justified. Reviewers get a starting point for their own questions.

For all institutions, the same applies as for the label itself: whoever requires disclosure must not penalise it. A declared weakness is better than a concealed one. Demanding chat histories or prompt logs across the board creates bureaucracy and new data protection problems without making assessment any easier. An institution achieves most when its own researchers, editors and reviewers lead by example.

## Critical objections

PISCATOR has to face objections. The most important ones are collected here, each with a reply.

**“Anyone who wants to can lie.”** That is true. PISCATOR relies on self-declaration, like statements on authorship or conflicts of interest. These can be falsified too, and they are still indispensable because they assign responsibility. A false statement can be checked and challenged. Silence cannot.

**“This is extra bureaucracy.”** The label is one line. It replaces descriptions that are already required today but vary widely. Bureaucracy tends to arise where entire chat histories are demanded.

**“One line cannot capture a research process.”** It is not meant to. Like a catch report, it records what others need to know in order to ask targeted questions. The details still belong in the methods section. If work steps differ considerably, each gets its own line.

**“The levels are fuzzy.”** Whether a script is S2 or S3 requires judgement. That is no flaw, since describing a method also rests on assessments. The specification offers guidance and examples. Contested cases are an occasion for discussion, for instance in peer review.

**“The statement makes you vulnerable.”** Anyone who declares I3 for identifiable data discloses a problem. That is precisely the benefit: what is visible can be fixed. For this to work, openness must not be penalised. PISCATOR does not ask for technical details that would pose a security risk; the statement only names the country and the type of contract.

**“PISCATOR will become outdated as tools change.”** The axes describe work steps and responsibility, not products. Which tools were used is stated under A and may change. New ways of working will need new codes; that is why PISCATOR carries a version number.

## Status

PISCATOR is a proposal in a first version. It builds on CLEAR but has not yet been tested in research practice and is certainly incomplete. Like any self-declaration, it depends on the statements being made honestly; they can only partly be verified. Feedback from research, data management and ethics committees helps to develop PISCATOR further, explicitly including objections and cases that do not fit. Feedback is possible via the [“Issues” of this repository](https://github.com/LeonieGantenbein/piscator-kennzeichnung/issues).

## Citation

Gantenbein, Leonie (2026): PISCATOR – Kennzeichnung von KI-Beteiligung in der Forschung [PISCATOR – Labelling AI Involvement in Research]. Version 1.0. Zenodo. https://doi.org/10.5281/zenodo.24372962

Machine-readable citation: [CITATION.cff](CITATION.cff) (on GitHub via “Cite this repository”)

## Licence

© 2026 Leonie Gantenbein. [CC BY 4.0](LICENSE.md) – free to use and adapt, with attribution to Leonie Gantenbein.

---

Theory and specification – `CLEAR (Leonie Gantenbein): C1, L3, E(p)2, A: Claude Opus 5.5, 11/2026, R1`<br>
English translation – `CLEAR (Leonie Gantenbein): C1, L(t)3, E(p)2, A: Claude Opus 5.5, 11/2026, R1`<br>
No PISCATOR statement: this text is not based on any data processing of its own.

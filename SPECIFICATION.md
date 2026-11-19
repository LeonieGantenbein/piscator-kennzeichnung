# Specification v1.0

## Starting point

In empirical research, AI works on data long before a text is written: it transcribes, codes, pseudonymises, writes analysis code, generates synthetic data or is itself the method. [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) labels how AI was involved in a text. It says little about this work on the data. PISCATOR closes this gap with eight short statements.

## Scope

PISCATOR is intended for empirical research that collects, prepares, codes or analyses data with code, whether quantitative or qualitative: interview studies and surveys, experiments and measurement series, corpus and archival work, modelling and simulation. Work without data processing of its own, such as theoretical, historical or hermeneutic studies, labels its text with CLEAR. A PISCATOR statement is not needed there.

Anyone publishing research gives both statements: PISCATOR for the research process, CLEAR for the text, provided AI tools were also used to produce or revise the text.

## The eight axes

### P – Privacy (personal reference)

Axis P records how easily the data an AI processed can be traced back to persons.

- **P0** – The data have no personal reference, for example measurements from lakes.
- **P1** – The data are anonymised. They can no longer be attributed to a person with reasonable effort.
- **P2** – The data are pseudonymised. Names and other direct identifiers have been replaced, but the data can be re-attributed by means of a key.
- **P3** – The data are identifiable.

Legally, pseudonymised data are still personal data, whereas anonymised data are not. The term “personal data” is therefore ambiguous. For the unaltered form, PISCATOR speaks of “identifiable” data.

**Suffix (s) – sensitive.** This covers data on religious, philosophical, political or trade union-related views or activities, on health, the private sphere or ethnic origin, genetic data, biometric data that uniquely identify a person, data on administrative and criminal proceedings or sanctions and on social assistance measures (Art. 5(c) Swiss FADP; cf. Art. 9 GDPR).

**Suffixes for availability.** They state whether the data underlying the results are accessible to others. (p) and (n) mean the same as in CLEAR.

- **(p)** – published, openly accessible
- **(r)** – restricted access: on request or in a repository with controlled access
- **(e)** – publication planned, for example after an embargo
- **(n)** – not published

If there are several versions, several suffixes are given, for example P(p, r)2: a synthetic version openly available, the original data on request. Which version is where is stated in the data availability statement. The availability suffix is mandatory as soon as there are data.

**Guidance on classification**

- What counts is the form most easily traced back to persons that an AI processed.
- P2 applies as soon as a key exists anywhere, even if it is held by a trustee and the researchers do not know it.
- P describes whether data can be attributed to persons, not their legal status. Data on deceased persons are usually no longer personal data in law; anyone identifiable in them is nonetheless P3.
- Public does not mean anonymous. Publicly accessible social media posts with names or profiles are P3.
- Synthetic does not automatically mean anonymous. A generator can memorise rare real cases. Whether synthetic data count as P1 must be checked separately.

### I – Infrastructure

Axis I records where the AI with access to the data ran.

- **I0** – locally, on one’s own computer. The data do not leave the device.
- **I1** – on protected infrastructure of one’s own institution: server, virtual machine, computing cluster, secure research environment.
- **I2** – with an external service under a data processing agreement.
- **I3** – with an external service under general terms of use only, for example via a free or private account.

**Suffix: country of server location**, as a country code: I(CH)2, I(DE)2, I(US)3. If only the region is known, (EU) is given. The suffix is omitted for I0 and optional for I1.

**On the agreement.** Anyone using a service always accepts terms of use, and these are a contract. What matters is whether the provider is bound as a processor: it may then process the data only on instructions, must secure them and may not use them for its own purposes. In Switzerland this is governed by Art. 9 FADP, in the EU by Art. 28 GDPR. Free and private accounts lack such an agreement, and depending on the terms the provider may also use inputs for training. Personal data (P2, P3) therefore do not belong in I3 as a rule.

**Guidance on classification**

- What counts is where the model actually runs, not where a program is installed. Some locally installed programs send data to external servers for their AI functions. That is I2 or I3, not I0.
- I covers every AI with access to the data, including a coding assistant that can read data files. A coding assistant without access to the data does not count.
- A downloaded model running on one’s own computer is I0, even if it comes from an external platform.
- Computing centres outside one’s own institution, including academic ones, are I2, provided a data processing agreement is in place.
- If several services were used, the least protected one counts. A names the provider.

The legal notes are for orientation. They do not replace legal advice or consultation with one’s institution’s data protection office.

### S – Script (code)

Axis S records how far AI was involved in the code: analysis scripts, data collection programs, notebooks and tools.

- **S0** – The code was written without AI.
- **S1** – Assistance: the AI completed code, searched for errors or explained code.
- **S2** – Parts generated: individual functions or sections come from the AI and were integrated by the human.
- **S3** – Largely generated: most of the code comes from the AI; the human read, steered and revised it.
- **S4** – Fully generated: the human described what the code should do and checked the result but did not read the code. This is vibe coding or working with agents.

The boundary between S3 and S4 lies in reading: whoever knows the code is at S3; whoever knows only its behaviour is at S4.

**Suffixes for availability** as for P: (p), (r), (e), (n), here for code and prompts. S(p)2 means: parts of the code were generated; code and prompts are published.

**Guidance on classification.** If someone uploads data to a chat that runs the analysis itself, code is produced that no one reads. That is S4, and I depends on the service.

### C – Conception

Axis C means the same as in CLEAR. It refers to the research question, hypotheses, design and research instruments such as questionnaires and interview guides.

- **C0** – Research question, hypotheses, design and instruments were developed exclusively by humans.
- **C1** – The AI served as a discussion partner during conception.
- **C2** – Individual parts were worked out by the AI, for example a questionnaire or an interview guide.
- **C3** – The conception was comprehensively generated by the AI.

### A – Attribution

Axis A means the same as in CLEAR. It names:

- the models and tools with their exact version. Models change under the same name, so the version designation or date belongs with them.
- for external services, the provider, for example “GPT-4o (Microsoft Azure, applied)”.
- the type of use: applied, adapted (for example by fine-tuning) or trained. For own models, the training data appear in brackets: “own model (trained on synthetic data)”.
- the programming languages.
- the period.

Prompts, parameters and packages belong in the repository, not in the line.

### T – Transformation (collection and processing)

Axis T records what the AI did with the data. It is a selection, not a scale: all applicable codes are given, for example T(ts, ps, an). T0 means the data were collected and processed without AI.

| Step | Code | What the AI does | Example |
|---|---|---|---|
| Collection | **(co)** collection | It conducts interviews or surveys, collects or records data. | A chatbot conducts guided interviews. |
| Conversion | **(ts)** transcription | It converts spoken language into text. | Interview recordings are transcribed. |
| | **(oc)** text and handwriting recognition | It makes printed or handwritten text machine-readable. | Letters from an archive are recognised. |
| | **(t)** translation | It translates data into another language. The code corresponds to L(t) in CLEAR. | Interviews in Portuguese are translated into German. |
| Preparation | **(ps)** pseudonymisation | It recognises names, places, employers and similar details and replaces or removes them. This also applies if the result is anonymous. | All personal names in 40 transcripts are replaced by codes. |
| | **(cl)** cleaning | It corrects errors, removes duplicates and standardises spellings. | “Zürich”, “Zuerich” and “ZH” become a single value. |
| | **(im)** imputation | It estimates missing values. | Income is missing for 8% of a survey; a model fills it in. |
| | **(li)** linkage | It matches entries from different datasets that belong to the same person or case. | Survey data are merged with register data. |
| Structuring | **(ex)** extraction | It pulls information out of documents, images or texts. | Sample sizes and effects are extracted from 300 studies. |
| | **(su)** summarisation | It summarises material with which work then continues. | Transcripts are condensed to one page each. |
| | **(an)** coding, classification, annotation | It assigns data to categories or labels them with features. | Open-ended responses are assigned to a category system. |
| Analysis | **(mo)** modelling | It produces findings itself, for example through prediction, clustering or topic models. | A model predicts student drop-out. |

Some codes deserve particular attention:

- **(ps)** acts directly on P. If the AI misses a name, the data are not pseudonymised, even though P2 is stated.
- **(im)** produces values that were not collected.
- **(su)** replaces material with a condensation. Whatever is missing there is also missing in the analysis, as with E2 in CLEAR.
- **(li)** increases the risk that persons become recognisable again.
- With **(mo)**, the AI is the method itself.

**Distinction from O.** T says what the AI did with the data; O says what kind of data they are, regardless of who made them so. If an AI generates new records, a new kind of data results: that belongs to O, for example (sy) or (au), and A names the model. If it changes values in existing entries, that belongs to T. A dataset with imputed values remains an original dataset; that is why imputation belongs to T.

The interpretation of results is declared in CLEAR (E3, E4).

### O – Origin (source and form)

Axis O records where the data come from and in what form they were worked with. The number states how far the data are reused:

- **O0** – own collection or generation only
- **O1** – own collection and reused data
- **O2** – reused data only: from repositories, registers, archives or the web

The forms appear as codes before the number, like the suffix in CLEAR:

- **(or)** – original: the data as collected or obtained
- **(sc)** – scrambled: real values swapped, masked or perturbed. Each row still goes back to a real case; such data are often not anonymous.
- **(ag)** – aggregated: only summarised values, for example tables
- **(sy)** – synthetic: newly generated records that reproduce the statistical properties of real data. No row corresponds to a real case.
- **(si)** – simulated or model-generated: produced without a real template, for example by a simulation, by a language model simulating respondents, or as AI texts that are themselves the object of research
- **(au)** – augmented: real data supplemented with artificially generated variants

The form in which the data were available and every form derived from it are named:

| Case | Statement |
|---|---|
| own interviews | O(or)0 |
| data reused and synthesised by the researchers | O(or, sy)2 |
| a ready-made synthetic dataset reused | O(sy)2 |
| own survey and figures from official statistics | O(or, ag)1 |
| own simulation | O(si)0 |

Whether synthetic data were generated by the researchers or obtained ready-made shows in whether (or) also appears.

### R – Responsibility

Axis R means the same as in CLEAR. It makes visible whether a human checked the AI’s results. Responsibility for a result always remains with whoever publishes it, not with the AI.

- **R1** – The AI’s results were fully checked and are taken responsibility for by the human.
- **R2** – They were spot-checked and are therefore not fully taken responsibility for.
- **R3** – They were used unchecked, with the risk of having to take responsibility for them nonetheless.

**Suffix (v) – validated.** The results were not merely looked at but checked by a fixed procedure, and the figures are documented. For example:

- 10% of the AI’s codings are re-coded by hand and the agreement is calculated.
- A model is tested on test data it had not seen, and its accuracy is recorded.
- Code is checked with automated tests.

R(v)2 means: spot-checked, but systematically validated. In research, this is often the realistic and good case when an AI has processed thousands of entries.

## X: not applicable

Whatever does not occur in a piece of research is marked with X:

- **SX** – There is no code.
- **PX, TX, OX** – There are no data.
- **IX** – No AI had access to the data.

SX differs from S0: with S0 there is code, but it was written without AI. X is not a gap but a piece of information. C, A and R occur in all research and need no X.

## Notation

```
PISCATOR (role): P(…)?, I(…)?, S(…)?, C?, A: models, languages, period, T(…), O(…)?, R(…)?
```

- As in CLEAR, suffixes precede the number: P(s, n)3, I(CH)2, S(p)2, O(or, sy)0, R(v)2.
- For P, I, S, C and R, the highest level reached is given.
- For T and for the forms in O, all applicable codes are given.
- The brackets after PISCATOR name who makes the statement and takes responsibility for it: a person, a project team or a lab.

## Several work steps

If work steps differ considerably in personal reference or infrastructure, each step gets a line of its own. The brackets then name role and step: “PISCATOR (project team, training)”. This avoids the impression that identifiable data were with an external service when only synthetic or pseudonymised data were there.

## Where the label goes

- Article and book: in the methods section or the data availability statement
- Data and code repository: in the README
- Thesis: next to the declaration of authorship
- Data management plan and grant proposal: as planned use

The CLEAR line appears as usual at the end of the text or in the imprint.

## Examples

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

## Relationship to CLEAR

PISCATOR takes its logic and three letters from CLEAR: C, A and R mean the same in both. In CLEAR, C refers to the line of thought of a text; in PISCATOR, to the research question and design. The suffixes (p), (n) and (t) also mean the same in both. The axes L and E do not appear in PISCATOR, so that nothing is confused.

CLEAR says how a text came about; PISCATOR says in more detail what happened to the data. If an AI transcribed interviews, for example, CLEAR states E(n)1 and PISCATOR T(ts).

## Deliberately not included

Whether participants’ consent covers AI processing, whether particularly vulnerable groups such as minors are involved, and how much computing power and energy an analysis required belong in the ethics application and the data management plan. PISCATOR does, however, show where questions are worth asking, for example with P(s)3 together with I2.

## Limits

PISCATOR has not yet been tested in research practice and is certainly incomplete. The label is a self-declaration and proves nothing. It does not say whether a result is correct; it makes visible where AI was involved in the research process.

---

[Back to the overview](README.en.md) · [Factsheet](FACTSHEET.en.md) · [CLEAR](https://github.com/LeonieGantenbein/clear-kennzeichnung) · Deutsch: [SPEZIFIKATION.md](SPEZIFIKATION.md)

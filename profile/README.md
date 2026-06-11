# Policy Observatory and Link Analysis for Antarctic Records & Institutional Support

This repository provides a shared research platform for SAEF members at Queensland University of Technology working on policy processes in the Antarctic Treaty System (ATS). It brings together tools, data, and methods for analysing institutional dynamics, policy development, agenda formation, and the structure of Antarctic governance.

The repository supports work on how issues enter the ATS agenda, how policy attention evolves over time, how documents relate to formal outcomes, and how institutional records can be used to study governance processes systematically.

# Datasets

The Antarctic Treaty System has a rich documentary record. Its central annual forum is the Antarctic Treaty Consultative Meeting (ATCM), which is held each year and hosted by different Parties. The meeting agenda is built from a range of formal document types submitted by Parties, Observers, Experts, and the ATS Secretariat.

These documents provide the main inputs into ATCM discussions and decisions.

| Document type           | Who submits                                                        | Content / function                                                                                                                                                                                                  |
| ----------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Working Papers (WP)     | Consultative Parties; Observers                                    | Substantive papers requiring discussion or action at the meeting. These include proposals, draft Measures, Decisions, Resolutions, management plans, policy positions, and reports that require a meeting response. |
| Secretariat Papers (SP) | ATS Secretariat                                                    | Papers prepared by the Secretariat, usually under a meeting mandate or to support meeting operations.                                                                                                               |
| Information Papers (IP) | Consultative Parties; Observers; Non-Consultative Parties; Experts | Supporting or relevant information that may inform discussion but does not necessarily require formal action.                                                                                                       |
| Background Papers (BP)  | Any participant                                                    | Formal information submitted for the record, but not introduced for discussion during the meeting.                                                                                                                  |

In addition to submitted meeting documents, each ATCM produces a Final Report. These reports provide the official record of the meeting and document how agenda items were treated, which issues were discussed, and which formal outputs were adopted.

Formal outputs include:

* **Measures**
* **Decisions**
* **Resolutions**
* **Recommendations** for earlier ATCM records, before the current terminology was adopted

Final Reports are structured documents. They generally contain:

* an index or table of contents listing agenda items, topics, and adopted outcomes;
* agenda-item sections containing titles, numbered paragraphs, discussion summaries, and references to submitted documents;
* records of formal outputs adopted by the meeting;
* opening and closing sections;
* draft agendas or planning material for future meetings.

Together, the submitted papers and Final Reports make it possible to trace how policy concerns enter the ATS, how they are discussed, and whether they become part of the formal institutional record.

## What is Available
- All final reports have been OCR'ed running a NVIDIA V100 on the NCI using marker-pdf (without llms). The quality of the extraction is generally good (visual check) but will have some issues with `<br>` being inserted. No common OCR artifacts were found (i.e. `2` being `z` etc). Extraction is clean if one is looking for formal outcomes or inputs
- The final reports use a mixture of arabic numerals (in modern documents, say > ATCM18) and roman numerals (<ATCM18).


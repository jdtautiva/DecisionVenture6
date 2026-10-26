# DecisionVenture6 — Marketing Planning and Operational Control Simulator

> **Interactive marketing simulator focused on marketing mix coherence, implementation, performance indicators, budget control, and evidence-based corrective decisions.**  
> Developed for **undergraduate marketing and managerial decision-making courses** by **Julián Díaz Tautiva, PhD**

# DecisionVenture 1 — Innovation Metrics Decision Simulator

> **Interactive managerial economics simulator focused on innovation metrics, business model evaluation, and financial decision-making.**  
> Developed for the **Managerial Economics** course by **Julián Díaz Tautiva, PhD**

---
## Overview

**DecisionVenture6** is a browser-based pedagogical simulation tool in which students work in teams as the management committee of **Pausa Campus**, a fictional campus business offering a beverage-and-snack combo through reservations and scheduled collection. Across **six missions and 35 challenges**, teams turn an approved marketing plan into operational decisions, examine implementation evidence, interpret deviations, and justify corrective actions.

The case follows a 12-week marketing plan and introduces an operational review at the end of Week 4. Students discover that sales above target can coexist with delivery delays, unauthorized discounts, and weaker contribution. They must connect product, price, distribution, and communication with responsibilities, deliverables, service standards, expenditure forecasts, and evidence of improvement.

The simulator combines decision questions, student-calculated indicators, immediate feedback, progressive mission unlocking, and a final management report. It distinguishes **first-attempt performance** from **mastery achieved through corrections** and records the attempts required to reach the final result.

The simulator runs entirely as a **single self-contained HTML file**. It requires no backend, installation, external libraries, or internet connection after download. It can be opened locally or served from a static web server, including GitHub Pages. The student-facing application uses the Pausa Campus case identity; DecisionVenture6 is the simulator's project name.

---
## Learning Objectives

By completing the simulation, students are able to:

- Specify and justify coherent **product, price, distribution, and communication** decisions
- Formulate measurable objectives with a defined indicator, target, scope, and time horizon
- Translate marketing decisions into actions, deliverables, acceptance criteria, responsibilities, dates, and resource requirements
- Calculate and interpret sales fulfillment, relative deviations, service punctuality, percentage-point gaps, and deliverable acceptance
- Distinguish **revenue**, **unit contribution**, **total contribution**, and the **marketing plan balance**
- Reconcile executed expenditure, outstanding commitments, and estimated remaining work without double counting
- Evaluate expenditure forecasts against an authorized budget ceiling and identify changes requiring approval
- Prioritize deviations and distinguish observed problems from causal hypotheses requiring verification
- Design operational indicators with consistent formulas, sources, periods, targets, and alert thresholds
- Compare conditional pricing scenarios while recognizing uncertainty about demand and operational capacity
- Propose corrective actions with an executor, approver, implementation date, review schedule, resources, and evidence of closure
- Communicate managerial recommendations through a written follow-up report

---
## Key Features

**One integrated managerial case** — all teams work with Pausa Campus, using a common approved plan and Week 4 execution records. Data are fictional, and monetary values are expressed in Chilean pesos (CLP), excluding VAT. Reported balances are before common overheads, taxes, and financing.

**Six progressive missions** — the learning sequence covers a coherent marketing plan, implementation commitments, indicator calculations, budget reconciliation, corrective decisions, and closure supported by evidence. Teams unlock the next mission after correctly resolving every challenge in the current mission.

**Team registration and roles** — students enter a team name and can add participants or roles. The activity is designed for teams of **3–5 students** using one device. Coordination, strategy, operations, analysis, and evidence-review roles support discussion before submitting answers.

**Accessible case dossier** — the approved objectives, marketing mix, budget, capacity, service rules, execution records, and scenario assumptions remain available throughout the activity.

**Marketing mix and implementation review** — teams identify specific, coherent decisions and connect them with evidence, acceptance criteria, dependencies, authorized resources, and traceable documentation.

**Calculation challenges** — students calculate sales fulfillment, sales and price deviations, punctuality, deliverable acceptance, revenue, contribution, plan balances, projected expenditure, and remaining budget margins. Numeric inputs accept decimal commas or points and common thousands separators.

**Formula-based error support in Mission 3** — incorrect answers receive the calculation formula, substitution using the case data, and procedural guidance **without revealing the result**. The full numerical explanation becomes available after a correct answer.

**First-attempt scoring and mastery tracking** — the game awards up to **100 points** for correct first responses. Subsequent corrections build mastery and unlock progress without adding first-attempt points. There is no time penalty.

**Detailed attempt tracking** — results and exported reports show total attempts across challenges, additional retries, valid review submissions by mission, challenges solved on the first attempt, and attempts for each individual challenge. The successful attempt is included. Incomplete or invalid submissions do not count, and already-mastered challenges are not counted again.

**Budget and scenario decisions** — teams separate executed expenditure from outstanding commitments and remaining work, evaluate a proposed service improvement, and determine when a budget change must be escalated. They also compare two pricing scenarios under the same assumed remaining sales volume, recognizing that these are conditional projections rather than guaranteed outcomes.

**Mandatory closing report** — teams write an **80–120-word executive follow-up summary**, complete **three corrective-action records**, and provide a reflection of **at least 25 words**. Each action records the problem or cause to verify, proposed response, responsibilities, implementation and review dates, resources or authorization, and closure evidence.

**Final report and export** — the report includes team identification, first-attempt score, mastery, attempts, consolidated indicators, budget projections, scenario comparisons, final answers, corrective actions, and reflection. Teams can view the report inside the application, download it as HTML, or print it as PDF using the browser's native print functionality.

**Separate instructor guide** — a standalone Word document contains facilitation instructions, the solutions to all 35 challenges, discussion questions, and a **20-point assessment rubric** for the written report. The guide and answer-key interface are excluded from the student HTML. Automated report checks verify length and field completion; the instructor evaluates the quality of the reasoning.

**Offline operation and local progress** — the university logo is embedded in the HTML, alongside inline SVG illustrations. Progress is saved automatically in the same browser when local storage is available. Reports are delivered through the instructor's usual submission channel; the application does not automatically send results or synchronize devices.

## Technical Details

| Attribute | Detail |
|---|---|
| Format | Single `.html` file, fully self-contained |
| Student application | `Operacion_Pausa_Campus_Tema_9.html` |
| Instructor guide | `Guia_Docente_Pausa_Campus_Tema_9.docx`, distributed separately |
| Implementation | HTML, CSS, and JavaScript |
| Dependencies | No external dependencies for running the simulator |
| Backend required | None |
| External libraries | None |
| Visual assets | Inline SVG illustrations and an embedded PNG institutional logo |
| Learning structure | Six missions and 35 challenges |
| Scoring | 100 first-attempt points; mastery and retries tracked separately |
| Written-report assessment | Instructor-reviewed rubric worth 20 points |
| Report export | HTML download, in-application report view, and browser-native print/export to PDF |
| Storage | JavaScript state with browser `localStorage` when available |
| Data transmission | No automatic submission, accounts, or cross-device synchronization |
| Offline use | Supported after downloading the HTML |
| Browser support | Modern browsers with JavaScript enabled, such as Chrome, Firefox, Safari, and Edge |
| Screen | Responsive layout for desktop, tablet, and mobile screens |
| Language | Spanish interface; English project documentation |
| Currency and accounting | CLP excluding VAT; plan balances before common overheads, taxes, and financing |
| Estimated duration | 65 minutes: 55 for missions and 10 for the closing report |
| Course context | Undergraduate marketing planning, operational control, and managerial decision-making |
| Instructor attribution | Julián Díaz Tautiva, PhD |

---

## Suggested Citation

Díaz Tautiva, J. A. (2026). *DecisionVenture6 — Marketing planning and operational control simulator* [Interactive teaching simulator].

---
title: Program
permalink: "/program/"
author_profile: true
sitemap: false
classes: wide
redirect_from:
- "/agenda/"
---

The MODEVAR workshop is planned as a half-day online event at **April 29th, 2026**, 13:00-17:00 (CEST). Find the program below. *You can join the workshop here: [https://webconf.tu-bs.de/rooms/dpr-p1e-jwe-plh/join](https://webconf.tu-bs.de/rooms/dpr-p1e-jwe-plh/join).*


| Time Slot (CEST) | Session | Session Chair | Details |
|---|---|---|---|
| 13:00-13:15 | Session 0: Welcome & Overview on State of UVL | - | Short introduction into MODEVAR and UVL.<br> Overview on Program. |
| 13:15-14:55 | Session 1: Tool Demos / Presentation of Use Cases | Rick Rabiser | Tool demos by participants targeting UVL and variability modeling in general.<br> & Presentations showcasing different requirements for variability specifications. |
| 15:20-15:40 | Session 2: How to develop UVL as a community effort? | David Benavides | Presentation of new repository for language extension proposals.<br> Discussion on latest protocol to continuously incorporate community. |
| 15:40-17:00 | Session 3: UVL Language Roadmap & Open Discussion | Kevin Feichtinger | Discussion on change suggestions for the language.<br> Create potential roadmap for UVL development. |

## Session 1 Detailed Schedule (tentative)

| Time Slot | Title | Speaker |
|---|---|---|
| 13:15-13:25 | UVL and UVLHub: enhancements and new applications | Esther Rocío Valladolid Ortíz |
| 13:25-13:35 | FlamapyIDE 2.0: What's Next for Client-Side AAFM | Francisco Benítez |
| 13:35-13:45 | Modular Software Product Lines with UVL | Miguel Ángel Rodríguez Luaces & Víctor Juan Lamas Sardinna |
| 13:45-13:55 | UVL feature model configuration selection with simulated annealing: The FMCooler tool | Jabier Martinez |
| 13:55-14:05 | UVL-Based Prompt Variability for AI Agents in UX design processes | Guillermo Ciria González |
| 14:05-14:15 | SENSOLIVE: UVL for Variability Management in Deficit Irrigation of Olive Groves | Guillermo Ciria González |
| 14:15-14:25 | uvllang: Towards a bidirectional UVL Parser | Tobias Heß |
| 14:25-14:35 | Variability in Cyber Physical Production System | Malte Grave |
| 14:35-14:45 | What UVL Made Us Invent: An Industrial Feature Model Toolchain and Its Unresolved Tensions | Thomas Kurpick |
| 14:45-14:55 | Order Matters: Configuration Sequences in Feature Models | Kristof Meixner |

## Session 1 Presentations: Further Information

Title: uvllang: Towards a bidirectional UVL Parser

Speaker: Tobias Heß, DHBW Heidenheim

Abstract: uvllang [1] enhances the default UVL parser [2] by an UVL extractor (from dimacs/smt2 -> UVL). While such extractions will almost never be true to the original UVL model, especially when formulas have been preprocessed in the meantime, they produce a start for semi-automatic refinement by humans or AI systems. Similar techniques may also be used to simplify complex cross-tree constraints and remove redundant constraints.

---

Title: Modular Software Product Lines with UVL

Speaker: Miguel Ángel Rodríguez Luaces & Víctor Juan Lamas Sardin~na, University of A Coruña

Abstract: We've been applying Software Product Line concepts to build a web-based GIS platform. In practice, though, we kept running into a recurring issue: different use cases required us to fork the product line, each time with slightly different subsets of functionality. At the same time, many parts of the system (e.g., user management) are clearly reusable and shouldn't be duplicated or reimplemented. What we really need is a way to define SPLs by composing modules, rather than treating the whole product line as a single monolithic artifact.

---

Title: UVL feature model configuration selection with simulated annealing : The FMCooler tool

Speaker: Jabier Martinez, Tecnalia France

Abstract: FMCooler is a tool that uses the classical Simulated Annealing algorithm to search for valid and optimized feature configurations within feature models. Built on top of flamapy, qubovert and dwave-neal, it is a competitive open-source addition for your toolbox on mono- or multi-criteria optimization for variability management. It requires UVL for the feature model. For the numeric values of the quality attributes for the features, it supports both CSV files and UVL attributes format. https://github.com/jdanielescanez/fmcooler

---

Title: Order Matters: Configuration Sequences in Feature Models

Speaker: Kristof Meixner, TU Wien

Abstract: Feature models struggle when their configuration requires order, guidance, and scalability. We introduce visibility constraints to enable sequence-aware, human-guided configuration.

---

Title: What UVL Made Us Invent: An Industrial Feature Model Toolchain and Its Unresolved Tensions

Speaker: Thomas Kurpick, Trusted Shops

Abstract: At Trusted Shops we use UVL as the single source of truth for a large SaaS product feature model, but ecosystem gaps forced us to build our own solutions: custom SVG rendering (no headless API), comment-encoded constraint metadata (no extension points), and a bespoke configuration format (no standard exists). Beyond tooling gaps, we face an unresolved modelling challenge - our domain has a commercial view (ProductArea/ProductFeature) and a technical product view (product/feature) that need to coexist, and while UVL's submodel imports help with file ownership separation, they provide no mechanism for the semantic cross-view relationships our domain requires.

---

Title: SENSOLIVE: UVL for Variability Management in Deficit Irrigation of Olive Groves

Speaker: Guillermo Ciria González (Jose Manuel Sanchez Ruiz), University of Sevilla

Abstract: Our tool support and empirical evaluation shows that they reduce complexity, accelerate configuration, and improve correctness.

---

Title: UVL-Based Prompt Variability for AI Agents in UX design processes

Speaker: Guillermo Ciria González, University of Sevilla

Abstract: This project investigates how variability modeling can systematically support the transformation and semi-automation of the UX design process and product discovery. We present an approach based on UVL to model and orchestrate prompt and workflow variability, enabling the automatic generation of tailored AI agents adapted to different design and discovery scenarios.

---

Title: Variability in Cyber Physical Production System

Speaker: Malte Grave, JKU Linz

Abstract: -

---

Title: UVL and UVLHub: enhancements and new applications.

Speaker: Esther Rocío Valladolid Ortíz, University of Seville

Abstract: The presentation covers the latest enhancements to UVLHub as a centralized repository for UVL feature models, as well as a new application towards a Software Product Line for drone propellers.

---

Title: FlamapyIDE 2.0: What's Next for Client-Side AAFM

Speaker: Francisco Benítez, University of Seville

Abstract: This presentation highlights the new features of FlamapyIDE, a web-based editor with client-side Automated Analysis of Feature Models (AAFM) capabilities, including secure UVL model sharing via URLs and direct saving to UVLHub. Furthermore, the updated tool introduces dedicated visual views for model metrics and a live-coding collaborative mode that enables multiple users to edit the same model in real time.

---

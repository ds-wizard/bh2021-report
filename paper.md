---
title: 'DS Wizard Meets DAISY: A Romance Solving Data Protection Requirements in Data Management Planning'
tags:
  - Data Stewardship
  - Data Protection
  - GDPR
  - Tool Integration
  - Document Generation
authors:
  - name: Marek Suchánek
    orcid: 0000-0001-7525-9218
    affiliation: 1
  - name: Pinar Alper
    orcid: 0000-0002-2224-0780
    affiliation: 2
  - name: Jan Slifka
    orcid: 0000-0002-4941-0575
    affiliation: 1
  - name: Vilém Děd
    orcid: 0000-0001-9235-8496
    affiliation: 2
  - name: Nene Djenaba Barry
    orcid: 0000-0003-3757-4211
    affiliation: 2
  - name: Paulette Lieby
    orcid: 0000-0002-9289-9652
    affiliation: 3
  - name: Marko Vidak
    orcid: 
    affiliation: 4
  - name: Nadja Zlender
    orcid: 
    affiliation: 4
affiliations:
  - name: Faculty of Information Technology, Czech Technical University in Prague
    index: 1
  - name: Luxembourg Centre for Systems Biomedicine, University of Luxembourg
    index: 2
  - name: Institut Français de Bioinformatique (IFB)
    index: 3
  - name: Institute for Biostatistics and Medical Informatics
    index: 4
date: 23 November 2021
bibliography: paper.bib
group: \#18 DSW + DAISY
authors_short: authors?
git_url: https://github.com/ds-wizard/bh2021-report
event: BH2021
---

# Abstract

This report summarizes our activities and achievements in connecting Data Stewardship Wizard (DSW) and DAISY during the ELIXIR BioHackathon Europe 2021. As a data information system for GDPR compliance, DAISY is very focused on a single goal – gathering all information required for GDPR compliance. On the other hand, DSW is very flexible and can be used even beyond data management planning. We worked on the connection on two fronts. First, we created a new Knowledge Model in DSW to make a data protection impact assessment (DPIA) and develop a related document template. Second, we introduced an integration between projects in DSW and DAISY and querying DAISY data upon document generation. Both of these independent activities brought successful results that were polished and published after the actual BioHackathon. Finally, we provide the related materials as an on-demand training course in the ELIXIR e-Learning Platform.

# Introduction

GDPR requires research projects with sensitive human data to perform a data protection impact assessment (DPIA) for documenting the project’s data protection risks and corresponding safeguards. Data stewards across Europe are tasked to support researchers with DPIAs, which occur commonly in tandem with data management planning. Two ELIXIR tools fall in the data protection realm. Data Stewardship Wizard (DSW) [@dswPaper] raises awareness for data protection requirements, such as the DPIA. However, it is not specialised in DPIA reporting. The Data Information System (DAISY), which allows institutions to keep a register of their projects using sensitive data, stores structured information on the project’s GDPR-relevant aspects – crucial input to a DPIA. Meanwhile, DAISY lacks the means to combine project facts with the narrative response needed in a DPIA.

As the DSW and DAISY are highly complementary, we decided to integrate the two to support DPIAs. The integration has been designed in two independent tasks:

1. **DPIA in DSW (Content-Based Integration)**: Allow to create DPIA directly in DSW by introducing a new Knowledge Model (questionnaire structure) and corresponding document template. After achieving this task, a user may create a DPIA project in DSW, fill in the information, and get a DPIA document. During the work in DSW, the user may benefit from all the features, including version history, collaboration, comments, and others.
2. **Querying DAISY Data in DSW (Technical Integration)**: Enable linking a project in DAISY inside a project in DSW and querying DAISY project details using API when necessary. The goal is to benefit from DAISY GDPR-specific features and allow us to use them when generating documents in DSW. For example, the results of these tasks can be then used to create a data management plan (DMP) appendix related to GDPR compliance.

To support the use of our output, we planned to compose a brief on-demand training course in the ELIXIR e-Learning Platform. Training on DPIAs has already been identified as a gap by the ELIXIR Training Platform.

# DPIA in DSW

*TODO: (Pinar) and Vilém - motivation for having DPIA KM+template in DSW, core idea and advantages*

## Forming DPIA Knowledge Model

*TODO: (Pinar), Vilém, Nene, and Paulette - what was the process, how you worked, what is the result*

## DPIA Document Template

*TODO: Nene and Paulette - what was the process, how you worked, what is the result*

## DPIA Projects in DSW

*TODO: Nene and Vilém - how the results work together (KM+template)*

# Querying DAISY Data in DSW

*TODO: Marek - describe goals and motivation*

*TODO: Jan - schema how it works*

## Integration Question for DAISY Projects

*TODO: Marek - motivation, describe issues with integration question*

*TODO: Marek - screenshot of the DSW*

## DSW Widget Integrations

*TODO: Jan - describe the widget integration question*

*TODO: Jan - screenshot of the DSW side, code snippet*

## Widget for DAISY Projects

*TODO: Vilém (and Jan) - describe implementation on DAISY side*

*TODO: Jan - screenshot of the "widget"*

## Retrieving Data for Document Generation

*TODO: Marek - describe HTTP requests from DSW*

## DPIA Appendix Template using DAISY

*TODO: Marek - describe template that renders the data from DAISY*

# Training Materials in EeLP

*Brief section of just in conclusions?*

# Conclusions and Future Steps

*TODO*

# Acknowledgements

This work was done during the BioHackathon Europe 2021 organized by ELIXIR in November 2021. We thank the organizers and fellow participants. The development and operation of DSW is supported by ELIXIR CZ research infrastructure (MEYS Grant No. LM2018131) and ELIXIR-CONVERGE (H2020 No. 871075).  

# References

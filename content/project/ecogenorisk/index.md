---
title: EcoGenoRisk
date: 2022-02-23T22:13:22.590Z
summary: >-
  <!--StartFragment-->


  ### Approach:


  The development of *EcoGenoRisk* focuses on three subfunctions to achieve a risk assessment workflow: *HazID*, *EnvCen*, and *RiskQ*. *HazID* identifies the susceptible community members within a population. *EnvCen* then quantifies the population of different environmental matrices that are likely susceptible. Finally, *RiskQ* then quantifies the overall ecological risk of a synbio microorganism released into various environmental matrices. Each of these functions requires database development and curation, linking to and employing the resources of public bioinformatic and chemoinformatic archives.


  ### Expected Results:


  The ultimate outcome of this project is the development and release of *EcoGenoRisk*, a computational package to compare the novel synbio organism to the available genetic databases, characterizing the risk to known organisms and environments. This bioinformatic system supports the risk assessment of synbio microorganisms by first identifying the presence of a hazard through comparing the modified genomes to wildtype in a combined comparative genetic, pathway, and produced inhibitor analysis (*HazID*). After identification of a hazard, the habitats most at risk are identified through an ecological census lookup (*EcoCen*). Finally, the overall risk is characterized by assessing the likelihood of the organism arriving, establishing, and surviving within a given location by considering additional constraints (*RiskQ*). Combined, *EcoGenoRisk* will provide the user with an ability to query current genetic databases for predicted risks as the final output. The open-source development of *EcoGenoRisk* will ensure that users may incorporate the software and approach into other bioinformatic pipelines and link with existing EPA ecological risk assessment tools.


  <!--EndFragment-->
draft: false
featured: false
external_link: https://cfpub.epa.gov/ncer_abstracts/index.cfm/fuseaction/display.abstractDetail/abstract_id/11176
links: []
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

### Description:

Synthetic biological (synbio) products pose a unique challenge for effective assessment and mitigation of risks. Unlike the handling of chemical agents, select synbio products maintain the ability to actively replicate within the environment, compounding on the mass and locations required to manage. This proposal focuses on developing an ecological risk assessment for the release of a full synthetic microbial cell (a subset of all synbio organisms) into an environmental matrix by developing the bioinformatic tool *EcoGenoRisk*.

### Objective:

The objective of this proposal is to develop and deploy the Python-based *EcoGenoRisk*, a bioinformatic tool with three primary aims for the software to deliver: (1) identify those genomes within public databases that negatively respond to the product, display the most similarity genetically to the synbio microorganism, and/or harbor similar or competing pathways, in combination, defining the susceptible populations;(2) identify environmental habitats that are likely to harbor the susceptible populations; and (3) quantify both the likelihood of the synbio microorganism to arrive in the susceptible habitat and the extent of structural or functional disruption experienced by the resident microbial community.

<!--EndFragment-->
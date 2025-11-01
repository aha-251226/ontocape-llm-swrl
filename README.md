# ontocape-llm-swrl
This repository contains the implementation and supplementary materials for the paper:
"Hierarchical LLM-SWRL Integration for Scalable and Consistent Ontology Expansion Enabling Automated Safety Compliance Checking"

Repository Contents
corpus.json - 45 KOSHA safety regulations (Korean Occupational Safety and Health Agency)
Source: KOSHA D-5, D-29, D-37, D-52 standards
Corresponds to Table 2 in the paper
Categories: AR (Annotation Review), BR (Basic Review), CR (Conditional Review), DR (Design Review), ER (Engineering Review)

Templates
safety_review_ontocape.yaml - OntoGPT extraction template
Maps regulatory text to OntoCAPE ontology structure
Defines ProcessEquipment, SafetyConstraint, and SafetyRelation classes
Used in Section 4.1 of the paper

Ontology Files
kosha_safety_rules.swrl - SWRL rules generated from 45 regulations
Formal logic rules for automated reasoning
Used in Section 4.3 (SWRL rule execution)

ontocape-kosha-delta.owl - Extended OntoCAPE ontology
46 new classes + 44 RDF triples
Δ-Module integration (Section 4.2)

Test Data
test_scenarios.csv - 50 P&ID validation scenarios
Corresponds to Appendix 1 in the paper
Used for performance evaluation (Table 6)

@article{uhm2025hierarchical,
  title={Hierarchical LLM-SWRL Integration for Scalable and Consistent Ontology Expansion Enabling Automated Safety Compliance Checking},
  author={Uhm, Miyoung and Lee, Ghang and Jeong, David H.},
  journal={[Journal Name]},
  year={2025}}

This project is licensed under the MIT License - see LICENSE file for details.
For questions or collaboration: Email: aha0810@yonsei.ac.kr

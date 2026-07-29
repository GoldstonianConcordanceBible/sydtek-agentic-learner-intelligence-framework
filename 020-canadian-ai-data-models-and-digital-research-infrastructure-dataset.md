# Canadian AI Data, Models, and Digital Research Infrastructure Dataset

## Canonical Metadata Standard for Datasets, Models, Compute Resources, Repositories, Platforms, and Shared Research Infrastructure

**Version:** 1.0.0  
**Document ID:** WIBC-DS-020  
**Status:** Foundational Dataset Specification  
**Maintained by:** Women in Blockchain Canada

---

# Purpose

The Canadian AI Data, Models, and Digital Research Infrastructure Dataset establishes a standardized, machine-readable framework for documenting the datasets, artificial intelligence models, computing resources, software platforms, repositories, laboratories, test environments, knowledge graphs, digital identity systems, blockchain networks, and shared research infrastructure supporting Canada’s responsible AI ecosystem.

The dataset is designed to improve research discovery, infrastructure access, grant planning, reproducibility, data stewardship, model governance, collaboration, commercialization, cybersecurity, and public-interest innovation.

It provides a structured record of the technical assets required to design, test, govern, deploy, scale, and preserve responsible AI systems.

---

# Dataset Objectives

The dataset supports:

- dataset discovery;
- model discovery;
- research reproducibility;
- infrastructure mapping;
- compute-resource planning;
- grant proposal development;
- consortium formation;
- data governance;
- model governance;
- cybersecurity planning;
- commercialization readiness;
- infrastructure-gap analysis;
- standards alignment;
- knowledge graph construction;
- long-term research preservation.

---

# Dataset Scope

The dataset may include:

- public datasets;
- restricted datasets;
- research datasets;
- administrative datasets;
- synthetic datasets;
- benchmark datasets;
- training datasets;
- validation datasets;
- testing datasets;
- foundation models;
- domain-specific models;
- open-source models;
- proprietary models;
- large language models;
- multimodal models;
- agentic systems;
- knowledge graphs;
- software libraries;
- APIs;
- cloud platforms;
- high-performance computing resources;
- secure research environments;
- data trusts;
- repositories;
- blockchain networks;
- digital identity infrastructure;
- cybersecurity testbeds;
- digital twins;
- simulation environments;
- research laboratories.

---

# Core Record Types

The dataset should support distinct but connected records for:

- Datasets
- Models
- Model Versions
- Software
- APIs
- Compute Resources
- Storage Resources
- Research Platforms
- Repositories
- Knowledge Graphs
- Laboratories
- Testbeds
- Blockchain Networks
- Digital Identity Systems
- Secure Research Environments
- Data Access Agreements
- Licenses
- Infrastructure Providers
- Infrastructure Projects

Each record should receive a stable identifier.

---

# Identifier Examples

Dataset-ID:

CAN-DS-000001

Model-ID:

CAN-MDL-000001

Model-Version-ID:

CAN-MDLV-000001

Software-ID:

CAN-SW-000001

API-ID:

CAN-API-000001

Compute-Resource-ID:

CAN-CMP-000001

Repository-ID:

CAN-REP-000001

Knowledge-Graph-ID:

CAN-KG-000001

Laboratory-ID:

CAN-LAB-000001

Testbed-ID:

CAN-TSTB-000001

Blockchain-Network-ID:

CAN-BCN-000001

Digital-Identity-System-ID:

CAN-DID-000001

---

# Dataset Record

Each dataset record should contain:

- Dataset Identifier
- Official Dataset Name
- Short Name
- Dataset Description
- Dataset Type
- Dataset Status
- Dataset Owner
- Dataset Steward
- Publishing Organization
- Contributing Organizations
- Country
- Province or Territory
- Geographic Coverage
- Sector
- Research Domain
- Data Subjects
- Data Sources
- Collection Method
- Collection Period
- Publication Date
- Last Updated Date
- Record Count
- File Formats
- Data Volume
- Language
- Access Level
- Access Procedure
- License
- Cost
- Ethical Approval Status
- Consent Basis
- Privacy Classification
- Security Classification
- Data Residency
- Retention Period
- Provenance Documentation
- Data Quality Documentation
- Bias Documentation
- Indigenous Data Governance
- Accessibility Documentation
- Persistent Identifier
- Official URL
- Citation
- Repository Version
- Last Verified Date

---

# Dataset Types

Datasets may be classified as:

- Research Dataset
- Administrative Dataset
- Government Open Data
- Public Dataset
- Restricted Dataset
- Confidential Dataset
- Commercial Dataset
- Synthetic Dataset
- Benchmark Dataset
- Training Dataset
- Validation Dataset
- Testing Dataset
- Evaluation Dataset
- Longitudinal Dataset
- Survey Dataset
- Sensor Dataset
- Geospatial Dataset
- Financial Dataset
- Health Dataset
- Education Dataset
- Supply Chain Dataset
- Climate Dataset
- Text Corpus
- Image Dataset
- Audio Dataset
- Video Dataset
- Multimodal Dataset
- Knowledge Graph

---

# Dataset Status

Recommended status values include:

- Proposed
- In Development
- Collecting Data
- Active
- Published
- Restricted
- Archived
- Deprecated
- Superseded
- Withdrawn
- Destroyed

---

# Dataset Access Levels

## Level 1 — Open

The dataset is publicly accessible without registration.

## Level 2 — Registered Access

Users must create an account or agree to basic terms.

## Level 3 — Approved Access

Users must submit an access request and receive approval.

## Level 4 — Controlled Research Access

Access is restricted to approved researchers within a governed environment.

## Level 5 — Highly Restricted

Access is limited because of legal, ethical, security, contractual, or privacy obligations.

## Level 6 — Internal Only

The dataset is not available outside the owning organization.

---

# Data Subject Metadata

Records should indicate whether data relates to:

- individuals;
- households;
- organizations;
- communities;
- Indigenous communities;
- government services;
- businesses;
- infrastructure;
- devices;
- environmental systems;
- financial transactions;
- supply chains;
- public records;
- synthetic entities;
- nonhuman systems.

---

# Data Sensitivity Classification

Recommended classifications include:

- Public
- Internal
- Confidential
- Restricted
- Highly Restricted
- Personal Information
- Sensitive Personal Information
- Health Information
- Financial Information
- Commercially Sensitive
- Security Sensitive
- Indigenous Knowledge
- Critical Infrastructure Information
- Unknown

---

# Data Quality Metadata

Each dataset should document:

- completeness;
- accuracy;
- consistency;
- timeliness;
- representativeness;
- validity;
- uniqueness;
- missingness;
- duplication;
- class balance;
- geographic coverage;
- demographic coverage;
- label quality;
- annotation quality;
- known errors;
- known limitations;
- quality review date.

---

# Data Provenance Metadata

Provenance documentation should include:

- original source;
- collection authority;
- collection method;
- transformation history;
- annotation process;
- preprocessing;
- cleaning;
- aggregation;
- filtering;
- version history;
- responsible organization;
- chain of custody;
- derived datasets;
- model usage;
- publication history.

---

# Data Bias Metadata

Dataset records should document known or potential bias related to:

- sampling;
- representation;
- geography;
- gender;
- race or ethnicity;
- language;
- disability;
- income;
- age;
- historical discrimination;
- measurement;
- labeling;
- missing populations;
- institutional practices;
- technology access;
- selection effects.

Bias documentation should identify whether mitigation was attempted and how effectiveness was evaluated.

---

# Indigenous Data Governance Metadata

Where Indigenous data, knowledge, communities, or territories are involved, records should document:

- governing community;
- community authority;
- consent process;
- ownership;
- control;
- access;
- possession;
- stewardship;
- benefit sharing;
- cultural protocols;
- localization;
- data residency;
- permitted uses;
- prohibited uses;
- community review;
- withdrawal conditions.

---

# Model Record

Each model record should contain:

- Model Identifier
- Official Model Name
- Short Name
- Model Description
- Model Type
- Model Status
- Model Owner
- Model Developer
- Host Organization
- Contributors
- Country
- Province or Territory
- Initial Release Date
- Latest Release Date
- Model Version
- Architecture
- Parameter Count
- Training Method
- Training Data Summary
- Intended Uses
- Prohibited Uses
- Supported Languages
- Input Modalities
- Output Modalities
- Performance Metrics
- Limitations
- Known Risks
- Responsible AI Controls
- Human Oversight Requirements
- Explainability Features
- Security Controls
- Privacy Controls
- Accessibility Features
- License
- Access Method
- Hosting Environment
- Compute Requirements
- Energy Documentation
- Model Card
- Evaluation Reports
- Official URL
- Persistent Identifier
- Repository Version
- Last Verified Date

---

# Model Types

Models may be classified as:

- Statistical Model
- Machine Learning Model
- Deep Learning Model
- Large Language Model
- Small Language Model
- Foundation Model
- Generative Model
- Multimodal Model
- Computer Vision Model
- Speech Model
- Recommendation Model
- Forecasting Model
- Classification Model
- Optimization Model
- Reinforcement Learning Model
- Agentic System
- Constitutional AI System
- Digital Twin Model
- Knowledge Graph Model
- Hybrid AI System

---

# Model Status

Recommended values include:

- Research
- Experimental
- Prototype
- Pilot
- Production
- Limited Production
- Suspended
- Deprecated
- Retired
- Withdrawn

---

# Intended Use Metadata

Each model should document:

- target users;
- target sectors;
- expected tasks;
- approved environments;
- decision significance;
- human oversight;
- expected inputs;
- expected outputs;
- performance assumptions;
- operational constraints;
- excluded populations;
- prohibited applications.

---

# High-Impact Use Metadata

Records should identify whether a model may affect:

- employment;
- education;
- healthcare;
- finance;
- insurance;
- housing;
- justice;
- immigration;
- public benefits;
- identity verification;
- critical infrastructure;
- public safety;
- children or youth;
- vulnerable populations;
- essential services.

High-impact systems should include enhanced governance and assurance documentation.

---

# Model Evaluation Metadata

Each model may include evaluation results for:

- accuracy;
- precision;
- recall;
- robustness;
- reliability;
- calibration;
- fairness;
- privacy;
- security;
- explainability;
- toxicity;
- hallucination;
- factuality;
- accessibility;
- energy use;
- latency;
- scalability;
- domain performance;
- language performance;
- human acceptance.

---

# Model Version Record

Each model version should contain:

- Model Version Identifier
- Parent Model Identifier
- Version Number
- Release Date
- Change Summary
- Architecture Changes
- Training Data Changes
- Safety Changes
- Performance Changes
- Known Regressions
- Compatibility
- Migration Requirements
- Deprecation Date
- Verification Status
- Repository Version

---

# Model Card Requirements

Each model should have a model card containing:

- model purpose;
- model architecture;
- training data summary;
- intended uses;
- prohibited uses;
- performance;
- limitations;
- fairness considerations;
- privacy considerations;
- security considerations;
- accessibility considerations;
- human oversight;
- monitoring requirements;
- incident reporting;
- retirement conditions.

---

# Software Record

Each software record should contain:

- Software Identifier
- Software Name
- Software Description
- Software Type
- Developer
- Maintainer
- Contributing Organizations
- Initial Release Date
- Latest Release Date
- Version
- Programming Languages
- Operating Environment
- Dependencies
- Installation Method
- License
- Source Code Availability
- Documentation
- Testing Status
- Security Review
- Accessibility Review
- Responsible AI Relevance
- Official Repository URL
- Persistent Identifier
- Repository Version
- Last Verified Date

---

# Software Types

Software may include:

- Library
- Framework
- Application
- Command-Line Tool
- Web Platform
- Mobile Application
- Data Pipeline
- Model Evaluation Tool
- Governance Tool
- Audit Tool
- Privacy Tool
- Security Tool
- Annotation Tool
- Visualization Tool
- Knowledge Graph Platform
- Blockchain Application
- Digital Identity Application
- Research Workflow Tool

---

# API Record

Each API record should contain:

- API Identifier
- API Name
- Provider
- Description
- API Type
- Access Method
- Authentication Method
- Authorization Model
- Rate Limits
- Pricing
- Supported Data
- Supported Models
- Data Residency
- Privacy Terms
- Security Requirements
- Logging
- Versioning
- Availability Commitment
- Deprecation Policy
- Documentation URL
- Repository Version
- Last Verified Date

---

# Compute Resource Record

Each compute resource should contain:

- Compute Resource Identifier
- Resource Name
- Provider
- Resource Type
- Geographic Location
- Data Centre Location
- Country
- Province or Territory
- Access Eligibility
- Access Procedure
- Cost Model
- Processor Type
- Accelerator Type
- Memory Capacity
- Storage Capacity
- Network Capacity
- Supported Frameworks
- Security Classification
- Data Residency
- Availability
- Scheduling Model
- Energy Source Documentation
- Environmental Metrics
- Technical Support
- Official URL
- Repository Version
- Last Verified Date

---

# Compute Resource Types

Compute resources may include:

- High-Performance Computing Cluster
- Supercomputer
- GPU Cluster
- Cloud Computing Environment
- Private Cloud
- Public Cloud
- Edge Computing Platform
- Secure Enclave
- Research Computing Facility
- Quantum Computing Resource
- Hybrid Computing Platform
- University Computing Cluster
- Government Computing Environment
- Commercial Compute Service

---

# Compute Access Models

Recommended values include:

- Public
- Academic
- Institutional
- Consortium
- Grant Allocated
- Subscription
- Commercial
- Invitation Only
- Restricted
- Security Cleared

---

# Storage Resource Record

Each storage resource should document:

- Storage Resource Identifier
- Provider
- Storage Type
- Geographic Location
- Capacity
- Access Model
- Encryption
- Backup
- Replication
- Retention
- Data Residency
- Security Classification
- Disaster Recovery
- Cost
- Supported Data Types
- Official URL
- Repository Version
- Last Verified Date

---

# Research Platform Record

Each research platform should contain:

- Platform Identifier
- Platform Name
- Platform Description
- Host Organization
- Platform Type
- Users
- Research Domains
- Supported Datasets
- Supported Models
- Software Tools
- Compute Resources
- Access Requirements
- Collaboration Features
- Governance Structure
- Privacy Controls
- Security Controls
- Audit Features
- Licensing
- Cost
- Official URL
- Repository Version
- Last Verified Date

---

# Repository Record

Each repository should contain:

- Repository Identifier
- Repository Name
- Host Organization
- Repository Type
- Content Types
- Research Domains
- Access Model
- Submission Requirements
- Review Process
- Version Control
- Persistent Identifier Support
- Citation Support
- Preservation Policy
- Licensing Support
- Metadata Standards
- API Availability
- Interoperability
- Official URL
- Repository Version
- Last Verified Date

---

# Repository Types

Repositories may include:

- Code Repository
- Data Repository
- Model Repository
- Institutional Repository
- Publication Repository
- Preprint Repository
- Standards Repository
- Policy Repository
- Educational Repository
- Blockchain Repository
- Knowledge Repository
- Archival Repository

---

# Knowledge Graph Record

Each knowledge graph should contain:

- Knowledge Graph Identifier
- Knowledge Graph Name
- Description
- Owner
- Maintainer
- Knowledge Domain
- Ontology
- Entity Types
- Relationship Types
- Data Sources
- Provenance Model
- Update Frequency
- Access Method
- Query Language
- API Availability
- License
- Privacy Controls
- Security Controls
- Validation Method
- Official URL
- Repository Version
- Last Verified Date

---

# Laboratory Record

Each laboratory record should contain:

- Laboratory Identifier
- Laboratory Name
- Host Institution
- Department
- Country
- Province or Territory
- City
- Research Domains
- Principal Investigators
- Technical Staff
- Equipment
- Datasets
- Models
- Compute Resources
- Research Projects
- Industry Partnerships
- Government Partnerships
- Nonprofit Partnerships
- Student Opportunities
- Access Policy
- Official URL
- Repository Version
- Last Verified Date

---

# Testbed Record

Each testbed should contain:

- Testbed Identifier
- Testbed Name
- Host Organization
- Testbed Type
- Research Domains
- Supported Technologies
- Available Data
- Available Models
- Simulation Capabilities
- Testing Capabilities
- Security Controls
- Safety Controls
- Access Requirements
- Pricing
- Scheduling
- Technical Support
- Certification Support
- Official URL
- Repository Version
- Last Verified Date

---

# Testbed Types

Testbeds may include:

- AI Safety Testbed
- Cybersecurity Testbed
- Smart City Testbed
- Supply Chain Testbed
- Digital Identity Testbed
- Blockchain Test Network
- Robotics Testbed
- Autonomous Vehicle Testbed
- Health Technology Testbed
- Financial Technology Sandbox
- Public-Sector Innovation Lab
- Regulatory Sandbox
- Digital Twin Environment
- Agentic AI Sandbox

---

# Secure Research Environment Record

Each secure environment should contain:

- Environment Identifier
- Environment Name
- Provider
- Security Level
- Eligible Users
- Supported Data Classes
- Access Procedure
- Authentication
- Authorization
- Monitoring
- Logging
- Export Controls
- Privacy Controls
- Data Residency
- Approved Software
- Compute Resources
- Audit Requirements
- Incident Response
- Official URL
- Repository Version
- Last Verified Date

---

# Blockchain Network Record

Each blockchain network should contain:

- Blockchain Network Identifier
- Network Name
- Network Type
- Governance Organization
- Consensus Mechanism
- Network Status
- Launch Date
- Supported Assets
- Smart Contract Support
- Identity Support
- Privacy Features
- Security Model
- Validator Model
- Node Requirements
- Interoperability
- Cross-Chain Support
- Data Availability
- Transaction Fees
- Sustainability Documentation
- Responsible Governance Controls
- Official Documentation
- Repository Version
- Last Verified Date

---

# Blockchain Network Types

Recommended values include:

- Public Permissionless
- Public Permissioned
- Private Permissioned
- Consortium
- Research Network
- Test Network
- Application-Specific Chain
- Layer 1
- Layer 2
- Sidechain
- Relay Chain
- Hybrid Network

---

# Digital Identity System Record

Each digital identity system should contain:

- Digital Identity System Identifier
- System Name
- Provider
- Governance Authority
- Identity Type
- Credential Types
- Authentication Methods
- Authorization Methods
- Consent Model
- Revocation Model
- Privacy Features
- Security Features
- Interoperability Standards
- Wallet Support
- Cross-Chain Support
- Auditability
- Accessibility
- Data Residency
- Official Documentation
- Repository Version
- Last Verified Date

---

# Digital Identity Types

Identity systems may include:

- Centralized Identity
- Federated Identity
- Decentralized Identity
- Self-Sovereign Identity
- Verifiable Credential System
- Soulbound Credential System
- Organizational Identity
- Device Identity
- Agent Identity
- Cross-Chain Identity
- Public-Sector Digital Identity

---

# Agentic Infrastructure Metadata

Agentic systems should additionally document:

- agent identity;
- owner;
- operator;
- delegated authority;
- tool permissions;
- spending authority;
- data access;
- memory;
- logging;
- human override;
- revocation;
- sandboxing;
- action limits;
- escalation requirements;
- incident handling;
- inter-agent communication;
- constitutional rules;
- audit trail.

---

# Data Access Agreement Record

Each data access agreement should contain:

- Agreement Identifier
- Dataset Identifier
- Provider
- Recipient
- Permitted Uses
- Prohibited Uses
- Access Period
- Data Location
- Security Requirements
- Privacy Requirements
- Publication Rules
- Intellectual Property Rules
- Derived Data Rules
- Model Training Rules
- Data Return Requirements
- Data Destruction Requirements
- Audit Rights
- Breach Notification
- Termination Conditions
- Approval Date
- Expiry Date
- Repository Version

---

# License Metadata

Licenses should document:

- License Identifier
- License Name
- License Type
- Rights Granted
- Restrictions
- Commercial Use
- Research Use
- Redistribution
- Modification
- Derivative Works
- Model Training
- Attribution
- Share-Alike Requirements
- Patent Terms
- Liability Terms
- Termination
- Official License URL
- Repository Version
- Last Verified Date

---

# License Types

Licenses may include:

- Open Data License
- Open-Source Software License
- Open Model License
- Research-Only License
- Commercial License
- Institutional License
- Government License
- Community License
- Custom License
- No Public License
- Unknown

---

# Infrastructure Readiness Levels

## Level 1 — Conceptual

The infrastructure need has been identified but no resource has been established.

## Level 2 — Planned

Technical, governance, funding, and access requirements are documented.

## Level 3 — Development

Infrastructure is being built, configured, or acquired.

## Level 4 — Pilot Available

The resource is accessible for limited research or testing.

## Level 5 — Operational

The infrastructure supports ongoing users and documented processes.

## Level 6 — Shared and Scalable

The resource supports multiple institutions, projects, or regions.

## Level 7 — National Infrastructure

The resource functions as a strategically important national capability.

## Level 8 — Internationally Interoperable

The resource supports sustained international research and standards-based integration.

---

# Data Governance Maturity Levels

## Level 1 — Unmanaged

Data ownership, quality, access, and accountability are unclear.

## Level 2 — Documented

Basic policies and stewardship roles are established.

## Level 3 — Controlled

Access, privacy, security, quality, and retention controls are implemented.

## Level 4 — Auditable

Data use, provenance, access, and transformations can be independently reviewed.

## Level 5 — Interoperable

Data is documented using reusable standards and can be responsibly shared.

## Level 6 — Continuously Governed

Data risks, quality, access, and lifecycle changes are continuously monitored.

---

# Model Governance Maturity Levels

## Level 1 — Experimental

Models are developed without formal governance.

## Level 2 — Documented

Models have ownership, purpose, versioning, and basic documentation.

## Level 3 — Evaluated

Performance, risk, fairness, privacy, and security are assessed.

## Level 4 — Controlled Deployment

Approval, monitoring, human oversight, and incident processes are operational.

## Level 5 — Independently Assured

Model governance and evidence are independently reviewed.

## Level 6 — Continuously Monitored

Model performance, drift, incidents, dependencies, and changes are continuously governed.

---

# Interoperability Metadata

Infrastructure records should identify support for:

- open standards;
- common metadata schemas;
- persistent identifiers;
- APIs;
- semantic interoperability;
- data portability;
- model portability;
- identity interoperability;
- cross-chain interoperability;
- cloud interoperability;
- research workflow integration;
- standards-based authentication;
- standards-based authorization.

---

# Security Metadata

Infrastructure security records may include:

- threat model;
- security classification;
- encryption;
- key management;
- identity management;
- access control;
- network security;
- monitoring;
- logging;
- vulnerability management;
- penetration testing;
- incident response;
- disaster recovery;
- business continuity;
- third-party risk;
- software supply chain security;
- security review date.

---

# Privacy Metadata

Privacy documentation may include:

- legal authority;
- consent;
- purpose limitation;
- data minimization;
- anonymization;
- pseudonymization;
- retention;
- deletion;
- access rights;
- correction rights;
- data portability;
- privacy impact assessment;
- cross-border transfer;
- privacy review date.

---

# Accessibility Metadata

Infrastructure records should document:

- user-interface accessibility;
- documentation accessibility;
- keyboard access;
- screen-reader compatibility;
- captioning;
- transcripts;
- accessible authentication;
- language access;
- accommodation procedures;
- accessibility testing;
- accessibility review date.

---

# Environmental Metadata

Compute and infrastructure records may include:

- energy consumption;
- energy source;
- carbon emissions;
- water use;
- hardware lifecycle;
- equipment reuse;
- equipment recycling;
- cooling requirements;
- utilization rate;
- environmental reporting;
- sustainability targets;
- measurement methodology.

---

# Cost Metadata

Infrastructure cost records may include:

- acquisition cost;
- subscription cost;
- storage cost;
- compute cost;
- data-access cost;
- licensing cost;
- support cost;
- maintenance cost;
- security cost;
- staffing cost;
- training cost;
- energy cost;
- cost per project;
- cost per user;
- cost per compute hour.

---

# Funding Metadata

Infrastructure may be supported through:

- federal grants;
- provincial or territorial grants;
- institutional funding;
- research infrastructure programs;
- industry partnerships;
- nonprofit funding;
- philanthropic funding;
- user fees;
- subscriptions;
- procurement contracts;
- consortium contributions;
- international funding.

---

# Reproducibility Metadata

Research assets should document:

- source code;
- environment specifications;
- dependency versions;
- model versions;
- dataset versions;
- random seeds;
- preprocessing;
- evaluation methods;
- hardware;
- compute environment;
- scripts;
- notebooks;
- workflow files;
- containers;
- persistent identifiers;
- replication instructions.

---

# Preservation Metadata

Long-term preservation should include:

- preservation owner;
- archival repository;
- retention period;
- file integrity checks;
- format migration;
- version retention;
- software dependency preservation;
- data deletion requirements;
- model retirement;
- persistent identifiers;
- succession planning;
- repository continuity.

---

# Relationship Graph

The dataset should support relationships among:

- datasets;
- models;
- model versions;
- software;
- APIs;
- compute resources;
- repositories;
- knowledge graphs;
- laboratories;
- testbeds;
- institutions;
- experts;
- projects;
- funding programs;
- standards;
- licenses;
- publications;
- patents;
- blockchain networks;
- digital identity systems.

---

# Machine-Readable Formats

The dataset should be published in:

- CSV
- JSON
- JSON-LD
- RDF
- GraphML
- YAML

---

# Persistent Identifier Strategy

Recommended prefixes include:

- CAN-DS for datasets;
- CAN-MDL for models;
- CAN-MDLV for model versions;
- CAN-SW for software;
- CAN-API for APIs;
- CAN-CMP for compute resources;
- CAN-STR for storage resources;
- CAN-PLAT for platforms;
- CAN-REP for repositories;
- CAN-KG for knowledge graphs;
- CAN-LAB for laboratories;
- CAN-TSTB for testbeds;
- CAN-SRE for secure research environments;
- CAN-BCN for blockchain networks;
- CAN-DID for digital identity systems;
- CAN-LIC for licenses;
- CAN-DAA for data access agreements.

Identifiers should remain stable across repository versions.

---

# Data Sources

Records should prioritize:

1. official institutional websites;
2. official repository records;
3. government open-data portals;
4. institutional data catalogues;
5. model cards;
6. data cards;
7. technical documentation;
8. software repositories;
9. infrastructure-provider documentation;
10. peer-reviewed publications;
11. official funding announcements;
12. verified governance records.

---

# Verification Requirements

Each record should include:

- primary source;
- source type;
- date accessed;
- verification status;
- reviewer;
- confidence level;
- version status;
- access status;
- license status;
- governance status;
- last updated date;
- uncertainty notes.

---

# Update Cycle

The dataset should be updated:

- monthly for active models, software, and APIs;
- quarterly for dataset and infrastructure status;
- semiannually for access, license, and governance verification;
- annually for full technical and institutional review;
- immediately after major releases, security incidents, deprecations, or retirements.

---

# Version Control

Each release should document:

- dataset version;
- publication date;
- dataset count;
- model count;
- software count;
- API count;
- compute-resource count;
- repository count;
- laboratory count;
- testbed count;
- blockchain-network count;
- digital-identity-system count;
- new records;
- revised records;
- deprecated records;
- withdrawn records;
- methodology changes;
- verification summary;
- change log.

---

# Repository Relationships

This dataset supports:

- Canadian AI Research Institutions Dataset
- Canadian AI Researchers and Subject Matter Experts Dataset
- Canadian AI Projects and Innovation Initiatives Dataset
- Canadian Responsible AI Risk and Assurance Dataset
- Canadian Responsible AI Standards and Policy Crosswalk Dataset
- Canadian Responsible AI Education and Workforce Development Dataset
- Canadian Responsible AI Implementation Playbook
- Global Responsible AI Grant Standard

---

# Repository Outputs

This dataset enables development of:

- national dataset catalogues;
- model registries;
- research infrastructure maps;
- compute-access directories;
- software and API catalogues;
- laboratory directories;
- testbed directories;
- blockchain infrastructure maps;
- digital identity registries;
- data governance dashboards;
- model governance dashboards;
- infrastructure-gap analyses;
- reproducibility reports;
- machine-readable technical knowledge graphs.

---

# Limitations

The dataset recognizes that:

- technical infrastructure changes rapidly;
- model capabilities may be overstated;
- model documentation may be incomplete;
- dataset access conditions may change;
- licenses may contain complex restrictions;
- public metadata may not reflect current security status;
- proprietary systems may disclose limited information;
- compute availability may vary;
- environmental estimates may be incomplete;
- research infrastructure may be distributed across multiple organizations;
- model and dataset versions may become obsolete;
- some information may be restricted for privacy, security, contractual, or legal reasons.

Technical and governance claims should therefore be verified against current primary documentation before high-stakes use.

---

# Long-Term Objective

The Canadian AI Data, Models, and Digital Research Infrastructure Dataset establishes a transparent, version-controlled, machine-readable foundation for discovering and governing the technical assets that support Canada’s responsible AI ecosystem.

Its long-term objective is to improve research reproducibility, expand equitable access to infrastructure, strengthen data and model governance, support grant competitiveness, and connect Canadian researchers, institutions, governments, communities, and companies through interoperable digital research infrastructure.
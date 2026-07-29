# Canadian Responsible AI Standards and Policy Crosswalk Dataset

## Canonical Metadata Standard for Mapping Laws, Policies, Standards, Frameworks, and Governance Requirements

**Version:** 1.0.0  
**Document ID:** WIBC-DS-016  
**Status:** Foundational Dataset Specification  
**Maintained by:** Women in Blockchain Canada

---

# Purpose

The Canadian Responsible AI Standards and Policy Crosswalk Dataset establishes a standardized, machine-readable framework for mapping the laws, regulations, policies, standards, guidance documents, assurance frameworks, and institutional governance requirements relevant to artificial intelligence, blockchain, Web4, cybersecurity, digital identity, data governance, and public-interest technology.

The dataset is intended to support legal and policy analysis, grant development, procurement readiness, standards alignment, institutional governance, audit preparation, implementation planning, and comparative research.

It does not replace legal advice, regulatory interpretation, or formal certification.

---

# Dataset Objectives

The dataset supports:

- policy discovery;
- standards comparison;
- regulatory readiness;
- grant compliance analysis;
- institutional governance;
- procurement planning;
- audit preparation;
- implementation design;
- assurance mapping;
- international comparison;
- evidence-based policy research;
- knowledge graph construction.

---

# Dataset Scope

The dataset may include:

- federal legislation;
- provincial legislation;
- territorial legislation;
- regulations;
- government directives;
- public-sector policies;
- institutional policies;
- voluntary standards;
- technical standards;
- management system standards;
- risk management frameworks;
- assurance frameworks;
- ethical principles;
- procurement requirements;
- privacy requirements;
- cybersecurity guidance;
- accessibility standards;
- data governance frameworks;
- Indigenous data governance principles;
- international reference frameworks.

---

# Primary Record

Each source should receive a permanent identifier.

Example:

Crosswalk-Source-ID:

CAN-XWALK-000001

---

# Required Metadata

Each source record should contain:

- Crosswalk Source Identifier
- Official Title
- Short Title
- Source Type
- Issuing Organization
- Jurisdiction
- Country
- Province or Territory
- Publication Date
- Effective Date
- Last Updated Date
- Current Status
- Official URL
- Version
- Language
- Sector Scope
- Technology Scope
- Legal Authority
- Mandatory or Voluntary Status
- Applicability
- Responsible AI Domains
- Core Requirements
- Evidence Requirements
- Audit Requirements
- Reporting Requirements
- Enforcement Mechanism
- Penalties or Consequences
- Related Standards
- Related Policies
- Superseded Documents
- Primary Source Citation
- Repository Version
- Last Verified Date

---

# Source Types

Sources may be classified as:

- Legislation
- Regulation
- Government Directive
- Government Policy
- Regulatory Guidance
- Voluntary Standard
- Technical Standard
- Management System Standard
- Ethical Framework
- Assurance Framework
- Risk Framework
- Procurement Requirement
- Institutional Policy
- Sector Guidance
- International Framework
- Indigenous Data Governance Framework
- Accessibility Standard
- Cybersecurity Standard
- Privacy Standard
- Data Governance Standard

---

# Status Classification

Recommended status values include:

- Proposed
- Draft
- Under Consultation
- Published
- In Force
- Voluntary
- Mandatory
- Revised
- Superseded
- Withdrawn
- Archived
- Unknown

---

# Jurisdiction Metadata

Each source should identify the relevant jurisdiction.

Examples include:

- Canada
- Federal
- Provincial
- Territorial
- Municipal
- Institutional
- Sector-Specific
- International
- Multilateral
- Indigenous Governance Authority

Where a source applies across multiple jurisdictions, all applicable jurisdictions should be recorded.

---

# Responsible AI Domains

Each source should be mapped to one or more governance domains:

- Human Oversight
- Accountability
- Transparency
- Explainability
- Fairness
- Privacy
- Consent
- Cybersecurity
- Accessibility
- Auditability
- Contestability
- Data Governance
- Data Provenance
- Model Risk
- Safety
- Reliability
- Environmental Sustainability
- Public Benefit
- Procurement
- Incident Reporting
- Recordkeeping
- Lifecycle Monitoring
- Third-Party Risk
- Intellectual Property
- Indigenous Data Governance

---

# Requirement Record

Each source may contain multiple individual requirements.

Every requirement should receive a stable identifier.

Example:

Requirement-ID:

CAN-REQ-000001

---

# Requirement Metadata

Each requirement record should include:

- Requirement Identifier
- Parent Source Identifier
- Requirement Title
- Requirement Text Summary
- Requirement Category
- Mandatory or Advisory Status
- Applicable Entity
- Applicable System Type
- Lifecycle Stage
- Evidence Required
- Responsible Role
- Review Frequency
- Enforcement Mechanism
- Related Requirements
- Crosswalk Notes
- Confidence Level
- Last Verified Date

---

# Lifecycle Stages

Requirements may apply to:

- Strategy
- Research
- Problem Definition
- Data Collection
- System Design
- Development
- Testing
- Procurement
- Pilot
- Deployment
- Monitoring
- Incident Response
- Change Management
- Scaling
- Retirement
- Post-Deployment Review

---

# Crosswalk Relationship Types

Mappings between requirements should use explicit relationship categories.

## Direct Equivalence

The requirements have substantially the same purpose and operational effect.

## Partial Equivalence

The requirements overlap but differ in scope, evidence, or implementation.

## Broader Than

The source requirement covers a wider range of obligations.

## Narrower Than

The source requirement addresses only part of another requirement.

## Complementary To

The requirements support each other but are not equivalent.

## Potential Conflict

The requirements may create inconsistent or competing obligations.

## No Clear Match

No sufficiently similar requirement has been identified.

## Historical Precedence

One source predates another and contains a similar concept.

## Documented Influence

A later source explicitly cites or attributes the earlier source.

## Formal Adoption

A source has been officially incorporated into another policy, standard, or governance process.

---

# Crosswalk Record

Each mapping between two requirements should receive a permanent identifier.

Example:

Crosswalk-ID:

CAN-MAP-000001

---

# Crosswalk Metadata

Each crosswalk record should include:

- Crosswalk Identifier
- Source Requirement Identifier
- Target Requirement Identifier
- Relationship Type
- Similarity Score
- Scope Match
- Evidence Match
- Governance Match
- Implementation Match
- Reviewer
- Review Method
- Supporting Notes
- Confidence Level
- Verification Date
- Repository Version

---

# Suggested Similarity Scale

## Score 0 — No Alignment

The requirements address unrelated subjects.

## Score 1 — Minimal Alignment

The requirements share limited terminology or broad themes.

## Score 2 — Partial Alignment

The requirements address similar goals but differ materially in scope or implementation.

## Score 3 — Strong Alignment

The requirements are closely related and could support shared controls.

## Score 4 — Near Equivalence

The requirements are highly similar with only limited differences.

## Score 5 — Direct Equivalence

The requirements have substantially equivalent intent, scope, and evidence expectations.

---

# Evidence Categories

Crosswalk conclusions should identify the evidence used.

Examples include:

- official legal text;
- regulatory guidance;
- standards documentation;
- official implementation guide;
- government policy document;
- institutional policy;
- certification criteria;
- audit guidance;
- public consultation record;
- official cross-reference;
- peer-reviewed analysis;
- expert legal interpretation;
- structured reviewer judgment.

---

# Evidence Hierarchy

Priority should be given to:

1. legislation and regulations;
2. official standards;
3. government and regulatory guidance;
4. official institutional documentation;
5. certification and audit criteria;
6. peer-reviewed legal or policy analysis;
7. verified expert interpretation;
8. structured stakeholder evidence;
9. LLM-assisted comparison subject to human verification.

---

# Legal Authority Metadata

Each source should identify its level of authority.

Suggested values include:

- Binding Law
- Binding Regulation
- Contractual Requirement
- Funding Requirement
- Procurement Requirement
- Institutional Requirement
- Certification Requirement
- Voluntary Standard
- Advisory Guidance
- Ethical Principle
- Research Recommendation

---

# Applicability Metadata

The dataset should specify whether a source applies to:

- federal institutions;
- provincial institutions;
- municipalities;
- universities;
- colleges;
- nonprofit organizations;
- private companies;
- regulated industries;
- startups;
- public-sector suppliers;
- healthcare organizations;
- financial institutions;
- critical infrastructure;
- research organizations;
- international partners.

---

# Sector Metadata

Sources may be tagged by sector:

- General
- Government
- Education
- Health
- Finance
- Insurance
- Telecommunications
- Transportation
- Energy
- Manufacturing
- Agriculture
- Defence
- Justice
- Public Safety
- Cybersecurity
- Consumer Services
- Employment
- Media
- Indigenous Governance
- Public Interest Technology

---

# Technology Scope

Sources may apply to:

- Artificial Intelligence
- Machine Learning
- Generative AI
- Foundation Models
- Autonomous Systems
- Agentic AI
- Decision Support Systems
- High-Impact Systems
- Biometric Systems
- Blockchain
- Smart Contracts
- Web3
- Web4
- Digital Identity
- Cybersecurity
- Cloud Computing
- Data Analytics
- Knowledge Graphs
- Internet of Things
- Robotics
- Digital Twins

---

# Control Mapping

Individual requirements may be mapped to organizational controls.

Suggested control categories include:

- Governance
- Risk Management
- Human Oversight
- Data Management
- Privacy
- Security
- Fairness
- Transparency
- Explainability
- Testing
- Monitoring
- Incident Response
- Accessibility
- Procurement
- Vendor Management
- Recordkeeping
- Audit
- Training
- Change Management
- Retirement

---

# Evidence Artifact Mapping

Requirements should be connected to evidence artifacts such as:

- governance charter;
- risk register;
- impact assessment;
- privacy assessment;
- security assessment;
- model card;
- data card;
- testing report;
- bias evaluation;
- accessibility review;
- decision log;
- change log;
- incident log;
- audit report;
- training record;
- vendor assessment;
- system inventory;
- retirement plan.

---

# Compliance Readiness Classification

## Level 1 — Unmapped

The organization has not identified applicable requirements.

## Level 2 — Identified

Relevant laws, policies, and standards have been identified.

## Level 3 — Mapped

Requirements have been mapped to internal policies and controls.

## Level 4 — Evidenced

Implementation evidence exists for mapped controls.

## Level 5 — Reviewed

Controls and evidence have undergone internal or external review.

## Level 6 — Continuously Monitored

Requirements, controls, evidence, and changes are monitored over time.

---

# Standards Crosswalk Methodology

The recommended process includes:

1. identify authoritative source documents;
2. extract individual requirements;
3. normalize terminology;
4. classify requirements by domain and lifecycle stage;
5. compare intent, scope, evidence, and enforcement;
6. assign relationship type;
7. assign similarity score;
8. document reviewer rationale;
9. verify against primary sources;
10. publish versioned mappings.

---

# LLM-Assisted Crosswalk Protocol

Language models may assist with:

- requirement extraction;
- terminology normalization;
- initial similarity scoring;
- draft relationship classification;
- gap identification;
- duplicate detection;
- metadata generation.

LLM-generated outputs must be:

- traceable to source text;
- reviewed by a qualified human;
- labeled as machine-assisted;
- assigned a confidence level;
- corrected before publication when necessary.

Language model output should not be treated as legal interpretation.

---

# Human Review Requirements

Crosswalks involving binding legal obligations should be reviewed by appropriately qualified personnel.

Review may include:

- legal counsel;
- privacy professionals;
- cybersecurity professionals;
- standards specialists;
- policy researchers;
- institutional compliance officers;
- Indigenous governance experts;
- accessibility specialists.

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

# Persistent Identifiers

Recommended identifiers include:

- CAN-XWALK for source documents;
- CAN-REQ for individual requirements;
- CAN-MAP for crosswalk relationships;
- CAN-CTRL for organizational controls;
- CAN-EVID for evidence artifacts.

Identifiers should remain stable across repository versions.

---

# Relationship Graph

The dataset should support relationships among:

- laws;
- regulations;
- policies;
- standards;
- requirements;
- controls;
- evidence artifacts;
- institutions;
- projects;
- funding programs;
- audits;
- incidents;
- governance roles;
- sectors;
- jurisdictions.

---

# Data Sources

Records should prioritize:

1. official legislative databases;
2. official regulatory websites;
3. government publications;
4. official standards organizations;
5. public-sector policy repositories;
6. institutional governance documents;
7. certification bodies;
8. official consultation records;
9. peer-reviewed policy research;
10. verified legal and standards analysis.

---

# Verification Requirements

Each source and requirement record should include:

- official source URL;
- publication or effective date;
- date accessed;
- verification status;
- reviewer;
- confidence level;
- last updated date;
- supersession status;
- uncertainty notes.

---

# Update Cycle

The dataset should be reviewed:

- monthly for proposed or fast-changing regulatory initiatives;
- quarterly for policy and standards updates;
- semiannually for crosswalk verification;
- annually for full source validation;
- immediately after major legal, regulatory, or standards changes.

---

# Version Control

Each release should document:

- dataset version;
- publication date;
- source count;
- requirement count;
- crosswalk count;
- new sources;
- revised sources;
- superseded sources;
- mapping changes;
- methodology changes;
- verification summary;
- change log.

---

# Repository Relationships

This dataset supports:

- Canadian Responsible AI Grant Standard
- Responsible AI Safety and Constitutional Governance Framework
- Canadian Responsible AI Implementation Playbook
- Canadian AI Funding Opportunities Dataset
- Canadian AI Projects and Innovation Initiatives Dataset
- Global Responsible AI Grant Standard
- Research Methodology and Evidence Framework

---

# Repository Outputs

This dataset enables development of:

- standards comparison tables;
- regulatory readiness dashboards;
- compliance matrices;
- grant requirement crosswalks;
- procurement checklists;
- governance control libraries;
- audit preparation tools;
- legal and policy knowledge graphs;
- implementation gap analyses;
- institutional readiness assessments;
- machine-readable assurance frameworks.

---

# Limitations

The dataset recognizes that:

- laws and policies change;
- official interpretations may evolve;
- standards may be revised or withdrawn;
- jurisdictional obligations can overlap;
- applicability depends on organizational and technical context;
- crosswalks require judgment;
- similarity does not establish legal equivalence;
- voluntary standards do not replace legal obligations;
- public summaries may omit important details;
- LLM-assisted analysis may contain errors.

All high-stakes compliance decisions should be verified against current primary sources and qualified professional advice.

---

# Long-Term Objective

The Canadian Responsible AI Standards and Policy Crosswalk Dataset establishes a transparent, version-controlled, machine-readable foundation for understanding how responsible AI obligations relate across laws, policies, standards, governance frameworks, and institutional controls.

Its long-term objective is to reduce fragmentation, improve regulatory readiness, strengthen grant and procurement compliance, and enable organizations to implement responsible AI through evidence-based and auditable governance.
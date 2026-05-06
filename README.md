# Project Shipshape: Process Automation & Integration

## Overview
This project focuses on optimizing logistics and clearance workflows by automating manual data entry and improving system interoperability between **Shipshape** and **Easy Clear**. The goal is to reduce human error, enhance auditability, and streamline communication with external transporters. [cite: 1]

## Business Objectives
* **Automation**: Replace manual Excel-based transport instructions with automated data triggers from Shipshape. [cite: 1]
* **Integration**: Create a "friendly" handshake between Shipshape and Easy Clear to facilitate seamless RIT Clearances. [cite: 1]
* **Compliance**: Implement digital logging and time-stamping for all document collections to ensure audit readiness. [cite: 1]
* **Efficiency**: Eliminate "long-winded" email chains between FML-OPS and Cargo Services (CS). [cite: 1]

## User Stories

### 1. Automated Transport Instructions
**As an** Operations Coordinator,  
**I want** to automatically generate and transmit transport instructions directly from Shipshape data,  
**So that** I can eliminate manual Excel exports and ensure transporters receive 100% accurate loading details without delay. [cite: 1, 2]

**Acceptance Criteria:**
* Extraction of specific data fields from Shipshape. [cite: 1]
* Standardized template formatting for external transporters. [cite: 1]
* Comprehensive transmission logs (who, what, when). [cite: 1]

---

### 2. Integrated RIT Clearance Workflow
**As a** Cargo Services (CS) Specialist,  
**I want** to access a pre-populated digital form containing existing shipment records,  
**So that** I can complete RIT Clearances and SAD500 entries without re-keying data from emails. [cite: 1, 2]

**Acceptance Criteria:**
* Pre-population of SARS, Commodity, and Consignee data. [cite: 1]
* Digital form handoff/draft capability between CS and FML-OPS. [cite: 1]
* Integration of 5x PDF documents directly to the SAD500 record. [cite: 1]
* Verification log with date/time stamps for document collection auditing. [cite: 1]

## Technical Scope
* **Primary Systems**: Shipshape, Easy Clear. [cite: 1]
* **Key Modules**: RIT Clearance, SAD500, Commodity Entry, Remover Code - Block59. [cite: 1]
* **Side Quest**: Collaboration with Riaan on alternate integration paths. [cite: 1]

## Definition of Done
The stories are considered "Done" when the user can complete the outlined task within the system UI without external manual workarounds (e.g., manual Excel picking), and all acceptance criteria are met. [cite: 2]

---
*Reference Documents:*
- *SHIPSHAPE-EXAMPLE1.md* [cite: 1]
- *TEAMPLATE.md* [cite: 2]*
{9e52a215-8da3-4048-a68d-3c918461775a}

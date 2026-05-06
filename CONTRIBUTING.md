This `CONTRIBUTING.md` file is designed to bridge the gap between a standard technical repository and the specific logistics domain of **FML-OPS** and **Cargo Services**. It sets clear expectations for any collaborator on how to handle Shipshape and Easy Clear integration ideas.

---

# Contributing to Project Shipshape

Thank you for your interest in improving our logistics and clearance workflows. To maintain the integrity of our operational data and ensure a "friendly" handshake between **Shipshape** and **Easy Clear**, we follow a structured contribution process.

## 1. The "Ask First" Policy
Before starting any technical work or opening a Pull Request, you must **open an Issue** to discuss the proposed change. This ensures that:
* The logic aligns with current **FML-OPS** and **Cargo Services (CS)** requirements.
* We aren't duplicating work already being handled in "side quests" (e.g., existing automation work by Riaan).
* The proposal respects the "single-entry" data principle to avoid "email ping-pong."

## 2. Our Workflow
We use the **Fork and Pull** model for all contributions:
1. **Fork** this repository to your own account.
2. **Create a branch** for your specific user story or fix.
3. **Draft your changes**, ensuring they meet the defined **Acceptance Criteria** for the relevant persona (Operations or Cargo Services).
4. **Submit a Pull Request (PR)** back to this main repository.

## 3. Pull Request Requirements
For a PR to be considered for a merge, it must:
* **Reference an Issue:** Link to the approved issue discussed in step 1.
* **Include Documentation:** Any changes to data handling (e.g., SARS Entry or Commodity data) must be reflected in the README or relevant documentation.
* **Pass Review:** All PRs require at least one approval from a Project Maintainer (Jason Ungerer).

## 4. Operational Integrity
Since this project involves sensitive logistics data and SARS compliance (SAD500/CN1), please ensure:
* No real shipment data is included in code or examples; use the **SHIPSHAPE-EXAMPLE** format.
* Any new forms or automation must include a timestamped audit log for document collection.

---
**Note:** This repository is public for visibility and collaboration, but the main branch is protected. Only approved Pull Requests will be merged.
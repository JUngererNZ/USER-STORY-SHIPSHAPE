SHIPSHAPE

Make use of resource to may my life easier

Can Shipshape be customized to send:
*** Trannsport Instructions to Transporters? ***
*** Show an example of what we have to send from excel sheet ***
- Alternate side quest that Riaan was working on

Big question to ask, buit to whom does that get sent to?
Maybe a watered down version picking data from within Shipeshape?

*** Another Shipshape problem to solve ***
- RIT Clearance
- The problem is that FML-OPS send CargoServices (CS) a long winded email to get RIT Clearance data to re-imput into
Easy Clear

- Is there a way to create a form with as much data from our records, and the allow CS to see the form, and further complete the:
    1. SARS Entry
    2. Comodity Entry
    3. Consignee
    4. Remover Code - Block59
    5. PDF Documents x5 
SAD500

The goal is to get a form populated in such a way that CS can pull to create finished RIT or take over DRAFT-FORM
and check, to complete sending it back to FML-OPS in some way shape or form.
Also have a log that can verify whom collected document with date/time stamp for auditing.
Utopia on completed SAD500 and linked Worksheet that comes from Easy Clear. There has to be a way for the 2 systems to talk friendly?!

# Mirishen Shipshape


------------

Based on the requirements in **SHIPSHAPE-EXAMPLE1.md** and the structured format in **TEAMPLATE.md**, I have drafted two high-level User Stories. These are designed to be presented to a Managing Director or Operations Manager to demonstrate the business value of these automation tasks.

---

## **User Story 1: Automated Transport Instructions**
**Focus:** Streamlining communication and reducing manual data entry between the office and transporters.

* **User Story:** > "As an **Operations Coordinator**, I want to **automatically generate and transmit transport instructions directly from Shipshape data**, so that I can **eliminate manual Excel exports and ensure transporters receive 100% accurate loading details without delay.**"

* **Business Value (The "So That"):**
    * Reduces the risk of human error inherent in manual "watered down" data picking.
    * Saves time by removing the need to manually format Excel sheets for external vendors.
    * Creates a single source of truth within Shipshape.

* **Acceptance Criteria:**
    * [ ] System can extract specific data fields from Shipshape.
    * [ ] Data can be formatted into a standardized template suitable for transporters.
    * [ ] Transmission log records exactly what was sent, to whom, and when.

---

## **User Story 2: Integrated RIT Clearance Workflow**
**Focus:** Solving the "long-winded email" problem and bridging the gap between Shipshape and Easy Clear.

* **User Story:** > "As a **Cargo Services (CS) Specialist**, I want to **access a pre-populated digital form containing existing shipment records**, so that I can **complete RIT Clearances and SAD500 entries without re-keying data from emails.**"

* **Business Value (The "So That"):**
    * **Efficiency:** Eliminates the "re-input" phase into Easy Clear.
    * **Compliance/Audit:** Provides a digital log with date/time stamps of who collected/processed documents.
    * **Utopia Goal:** Establishes a "friendly" handshake between Shipshape and Easy Clear to reduce the friction between FML-OPS and CS.

* **Acceptance Criteria:**
    * [ ] Form is pre-populated with SARS, Commodity, and Consignee data.
    * [ ] Ability to upload/link the 5 required PDF documents directly to the record.
    * [ ] Audit trail captures the user ID and timestamp for every document collection.
    * [ ] Draft-form handoff capability between CS and FML-OPS is functional.

-----------------------------

### **Suggested Email/Message to Leadership**
> **Subject:** Proposal: Automation of Transport Instructions and RIT Clearance Workflows
>
> Hi [Name],
>
> I’ve been reviewing our current bottlenecks in the Shipshape and Easy Clear workflows—specifically the manual data re-entry for RIT Clearances and the manual coordination of transport instructions. 
>
> I’ve drafted two User Stories (attached/below) that outline how we can automate these processes to reduce errors and improve our audit trail. I am seeking permission to proceed with a formal discovery phase to see how we can make these two systems "talk friendly" and eliminate the long-winded email chains currently slowing down Cargo Services.
>
> Best regards,
> [Your Name]

---
**Note on the "Side Quest":** If you'd like to include Riaan's work specifically, we can add a third story titled "Historical Data Migration/Sync" once we have more details on that specific task!

{ce003434-3a91-4ed4-bdab-fb74149cea76}
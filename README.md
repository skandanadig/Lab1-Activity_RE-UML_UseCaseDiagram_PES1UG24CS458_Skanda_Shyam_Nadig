# Smart Cities Municipal Infrastructure Damage Reporting App

**Problem Statement #29** — Transport & Logistics Municipal Infrastructure Damage Reporting App

**Student Info**: PES1UG24CS458 | Section H | Skanda Shyam Nadig

## Problem Context
A citizen portal for reporting road potholes, broken streetlights, and water pipeline leaks using geotagged photos, with automated ticket dispatch to the relevant municipal engineering department.

**Actors:** 
- Citizen Reporter
- Municipal Engineer
- System Administrator

## Contents
<img width="350" height="211" alt="image" src="https://github.com/user-attachments/assets/80dc0aec-59a4-4ad6-9382-9823f2dc42a9" />

### Files Included

| File | Description |
| :--- | :--- |
| **Requirements_Table.docx** | 5 FRs (FR-001–FR-005) + 2 NFRs (NFR-001, NFR-002) with ID, type, description, priority, acceptance criteria, and rationale |
| **UseCase_Diagram.pdf** | UML use-case diagram — 3 actors, 7 use cases, one `«include»` and one `«extend»` relationship |
| **UseCase_Flow.docx** | Use-case flow spec for UC-01 (Report Damage) — preconditions, postconditions, main success scenario, alternate flows |

## Use Cases
- **UC-01:** Report Damage
- **UC-02:** Extract GPS Metadata (`«include»` of UC-01)
- **UC-03:** Draft Offline Report (`«extend»` of UC-01)
- **UC-04:** Auto-Dispatch Ticket
- **UC-05:** Track Ticket Status
- **UC-06:** Update Ticket Status
- **UC-07:** Manage User Accounts

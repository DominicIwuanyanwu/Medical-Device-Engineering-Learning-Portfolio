# Patient and staff safety in medical-device management

**Prepared for:** Dominic Iwuanyanwu  
**Date prepared:** 29 September 2026  
**Status:** Draft, AI-assisted independent-study exercise for personal review and revision  
**Scope:** Hypothetical infusion pump in a hospital equipment library; no real device, patient, service record or incident was used.

> **Portfolio disclosure:** This is independent study and a simulated medical-device safety exercise. It does not demonstrate patient use, clinical validation, authorised device maintenance, device-specific competence, or conformity with ISO 14971.

## Aim and source boundary

I want to demonstrate how an EBME technician might *think through* potential harm to patients and staff, recognise when a device should be escalated, and keep traceable records. This desktop exercise draws on the publicly available MHRA guidance listed below. It is not a hospital procedure, clinical instruction, test method or complete ISO 14971 risk-management file. In a real service, the manufacturer’s instructions, local policy and trained authorised personnel govern actions.

## Source notes

- MHRA, *Managing Medical Devices* (January 2021), especially section 2.7 (adverse incidents, including near misses), section 6 (training), section 8 (maintenance and repair) and section 9 (decontamination): https://www.gov.uk/government/publications/managing-medical-devices
- MHRA, *Devices in Practice: Checklists for using medical devices*, especially checklists 2–4 (training, records and incident reporting): https://www.gov.uk/government/publications/devices-in-practice-checklists-for-using-medical-devices/devices-in-practice-checklists-for-using-medical-devices
- ISO, *ISO 14971:2019 — Medical devices — Application of risk management to medical devices*, public overview (not a claim to have read or implemented the full standard): https://www.iso.org/standard/72704.html

**Interpretation:** The MHRA documents address safe management and use in a healthcare organisation. ISO 14971 describes a broader device risk-management process, including identifying hazards, evaluating risks, applying controls and monitoring their effectiveness. I am using these ideas as a study framework, not claiming a formal risk evaluation or acceptable residual risk.

## Scenario and boundaries

A fictional rechargeable infusion pump, **SIM-PUMP-001**, has been returned to a hospital equipment library and may later be issued for clinical use. Its manufacturer, model, instructions, maintenance interval, electrical classification, battery specifications and local procedures are deliberately unspecified. That missing information would have to be obtained before making any real servicing or release decision. No clinical settings, electrical measurements, calibration values or maintenance intervals are proposed here.

## Illustrative hazard review

| ID | Hypothetical situation and possible harm | Who may be affected | What an authorised team would need to consider | Evidence/record to retain | Unresolved point |
|---|---|---|---|---|---|
| R1 | Battery performance is insufficient and the pump stops unexpectedly; prescribed therapy may be interrupted. | Patient; clinical staff responding to the interruption. | Identify and remove a suspected faulty device from circulation; clinical team manages continuity of care; authorised EBME staff follow manufacturer-approved battery checks and local return-to-service criteria. | Device identifier, reported symptom, time, battery/alarm information if available, work order, approved check result, disposition and authorisation. | What battery checks, alarms and replacement intervals does this model actually require? |
| R2 | Damaged mains cable or connector could expose a user to an electrical hazard or cause loss of power. | Staff, patient and anyone handling the device. | Do not issue a visibly damaged device; isolate and label it under local policy; appropriately trained personnel inspect and perform only the manufacturer-approved tests. | Visual defect description, device and accessory identifiers, date, quarantine status, authorised work and decision. | Which cable and electrical safety checks apply to this device and accessory? |
| R3 | Incorrect configuration or unclear instructions could lead to an inappropriate delivery setting. | Patient; staff operating the device. | Use current manufacturer instructions, confirm user training and escalate confusing labels, instructions or reported use errors. Clinical staff retain responsibility for clinical prescription and operation. | Version of instructions, training record or query, reported event/near miss, escalation and any corrective action. | What setup checks and training does the local clinical policy require? |

**No scores have been assigned.** Likelihood, severity, risk acceptability and effectiveness of controls cannot be credibly established from this fictional scenario. A real assessment needs defined intended use, actual device information, local processes and competent reviewers.

## Simulated response to a reported fault or near miss

1. **Protect care first:** notify the responsible clinical team immediately so it can manage patient care. Do not make clinical treatment decisions as a technician.
2. **Prevent further use:** identify the device and follow the organisation’s procedure for removal, labelling and safe storage; preserve relevant device and accessory details for investigation.
3. **Record facts:** capture asset ID, manufacturer/model/serial number, location, date/time, reporter, observed symptom, alarm/error messages, settings if relevant and permitted, people affected, and action taken. Avoid assuming the cause.
4. **Escalate and report:** inform the relevant manager and Medical Device Safety Officer under local policy. Consider MHRA Yellow Card reporting in line with organisational procedures; the MHRA includes near misses in its guidance and accepts individual reports.
5. **Investigate and close:** authorised personnel consult manufacturer instructions, investigate, document any repair and checks, and record the decision and authorisation before a device returns to circulation. Review whether other devices or training are affected.

This is a conceptual flow only. Actual preservation, decontamination, manufacturer contact, reporting, testing and return-to-service steps depend on the trust’s procedure and the device.

## Dummy equipment/incident record (invented data)

| Field | Example entry |
|---|---|
| Asset ID | SIM-PUMP-001 (fictional) |
| Device description | Simulated rechargeable infusion pump |
| Location/date | Example equipment library; 29 September 2026 |
| Reporter / observed symptom | Fictional ward report: “Low battery warning occurred earlier than expected” |
| Immediate status | Marked **DO NOT ISSUE** in this exercise; clinical escalation assumed |
| Incident reference | SIM-INC-001 (fictional) |
| EBME action | **None performed**; await authorised assessment using actual manufacturer and trust procedures |
| Test/calibration result | **Not performed / no result** |
| Reporting decision | Pending assessment under local incident and MHRA reporting processes |
| Return-to-service decision | **Not authorised**; no release decision can be made from this scenario |

## Draft learning reflection — personalise before posting

This exercise helped me connect engineering fault diagnosis with the wider safety process: recognising possible harm, preventing further use, involving clinical staff, recording traceable facts and escalating near misses. I also learned that a plausible technical check is not enough to declare a device safe; the actual device instructions, local policy, training and documented authorisation matter. I need supervised experience to understand the real workflow and device-specific checks.

**My own notes after reading (complete before publishing):**
- One detail I found in the MHRA guidance: [add your own observation and section/page].
- One question I would ask an EBME supervisor: [add your question].
- One change I made to this draft after checking the sources: [describe your edit].

## Next evidence to build

Seek supervised EBME shadowing or an assistant/trainee role, learn the trust’s equipment library and incident procedures, and complete device-specific manufacturer/local training with recorded competency where available. This portfolio entry is evidence of study and safety reasoning, not practical clinical-device experience.


# ICSR-Complete-Assesment-Task5

# Task 5: Individual Case Safety Report (ICSR) - Complete Pharmacovigilance Assessment
**ID: task5 | Intern: Jignesh Savaniya - RK University, Rajkot**
**Role: Drug Safety Associate**

## Objective
Perform a complete pharmacovigilance assessment on a detailed case study. This includes ADR identification, ICSR reporting, causality assessment, and severity classification, simulating the role of a Drug Safety Associate.

## CASE STUDY FOR ICSR

**Patient Information:**
- Age: 45 years
- Sex: Female
- Weight: 60 kg
- Patient ID: ICSR-45F-001
- History: No known allergies, No comorbidities

**Suspected Drug:**
- Drug: Amoxicillin
- Dose: 500 mg TID (Three times daily)
- Route: Oral
- Indication: Upper Respiratory Tract Infection (URTI)
- Therapy Dates: Started 3 days ago
- Dechallenge: Positive
- Rechallenge: Not Done (Ethically not allowed)

**Adverse Event:**
- Reaction: Skin Rash, Itching, Erythematous maculopapular rash over arms and trunk
- Onset: 3 days after starting Amoxicillin (Temporal relationship present)
- Outcome: Recovering after drug withdrawal + Antihistamine (Cetirizine)
- Seriousness: NON-SERIOUS

---

## 01 - ADR IDENTIFICATION (Task 1)

- Type: Type B - Bizarre, Dose-independent, Hypersensitivity (Immunological)
- Mechanism: IgE-mediated hypersensitivity to Penicillin beta-lactam ring
- Predictability: Unpredictable
- Dose Relationship: Not dose-related

## 02 - REPORTING (ICSR) (Task 2) - E2B R3 Format

| ICSR Element | Details |
|--------------|---------|
| Patient Age/Sex | 45 Years / Female |
| Suspect Drug | Amoxicillin 500mg TID, Oral |
| Reaction | Skin Rash, Itching |
| Seriousness | Non-serious |
| Causality | Probable |
| Outcome | Recovering |
| Reporter | Drug Safety Associate - Jignesh Savaniya |
| Report Type | Initial Report |

**Narrative:** A 45-year-old female developed skin rash and itching 3 days after starting Amoxicillin 500mg TID for URTI. No other concomitant drugs. Dechallenge positive. No rechallenge. Treated with Cetirizine. Diagnosis: Amoxicillin-induced hypersensitivity.

## 03 - CAUSALITY ASSESSMENT (Task 3)

**WHO-UMC Scale: PROBABLE / LIKELY**
- Temporal relationship: Yes (+)
- Dechallenge: Positive (+)
- Rechallenge: Not done
- Alternative cause: Unlikely

**Naranjo Scale Score: 6 = PROBABLE**
1. Previous reports? Yes +1
2. After drug? Yes +2
3. Improved after stop? Yes +1
4. Rechallenge? Not done 0
5. Alternative causes? No +2
6. Placebo? Not done 0
7. Toxic conc? Not done 0
8. Dose-response? No 0
9. Previous similar? No 0
10. Objective evidence? Yes +0 (Rash)
**Total = 6 Probable**

## 04 - SEVERITY & CLASSIFICATION (Task 4)

**Seriousness (ICH E2A): NON-SERIOUS**
- Reason: No death, no life-threat, no hospitalization, no disability, no congenital anomaly.
- Manageable with antihistamine and drug withdrawal.

**Expectedness (SmPC): EXPECTED**
- Amoxicillin SmPC lists skin rash, itching, hypersensitivity as common ADR (1-10%).

**Severity Level: MILD (Hartwig Level 2)**
**Action:** Stop Amoxicillin, Give Cetirizine 10mg, Document allergy in card, Counsel patient to avoid Penicillins in future, Routine reporting to PvPI.

## Final Conclusion for ICSR

- This is a **Non-serious, Expected, Probable, Type B ADR**.
- Reportable as Routine ICSR to PvPI within 30 days.
- Patient counseling and allergy documentation is critical to prevent recurrence.

## Files in this Repo
- README.md - Complete ICSR
- icsr_case.py - Python code for ICSR generation
- naranjo_assessment.csv - Causality score
- icsr_form_e2b.csv - E2B structured data

## References
- ICH E2A, E2B(R3), WHO-UMC, Naranjo, PvPI, Goodman & Gilman
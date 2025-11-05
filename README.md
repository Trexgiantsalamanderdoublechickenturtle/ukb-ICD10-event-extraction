# ukb-ICD10-event-extraction
R functions for extracting diagnoses and first diagnosis dates from “Data-Field 41270” and “Data-Field 41280” in the UK Biobank, based on ICD-10 codes.

Parameters:
- **df** — data.frame containing ICD-10 diagnosis columns (41270-0.x) and corresponding diagnosis date columns (41280-0.x)
- **event** — name of the output event variable (character)
- **icd_prefixes** — vector of ICD-10 code prefixes to match, e.g., c("I10", "I20","I10.1","C")


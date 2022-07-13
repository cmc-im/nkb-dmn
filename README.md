# DMN: Pure vs. Mixed Pathology
- Research type: [hypothesis generation (data exploration)](https://r4ds.had.co.nz/model-intro.html?q=hyp#hypothesis-generation-vs.-hypothesis-confirmation)
- Data source: Catholic Medical Center (CMC) Nephrology (NEP) Native Kideney Biopsy (NKB) Registry
- Variable (column) identification
  - Full name (with label): e.g. PL_CMT
  - Name (no label): e.g. CMT
  - Description (for humans): e.g. pathology comment
- Observational unit
  - Patient
  - Follow-up visit
- Group by: pathological description of kidney biopsy
  - Comment
  - Diagnosis
- Outcomes
  - Kidney Function
    - eGFR
    - RRT?
  - Microscopic Hematuria
    - UPCR
- File structure
  - Main directory
    - data
      - baseline
        - demographic
        - clinical
        - laboratory
        - pathology
        - treatment
      - fu1
        - clinical
        - laboratory
        - pathology
      - ...
      - fu10
        - clinical
        - laboratory
        - pathology
    - meta
      - code-book

# Re-estimating SMART2
This repository accompanies the manuscript: *"Local calibration of a cardiovascular risk score through linkage of electronic health records and insurance claim data leveraging secure multi-party computation: a privacy preserving approach"*
The manuscript describes how the SMART2 risk score for the estimation of 10-year risk of recurrent CV events in patients with established CV disease was recalibrated to a single hospital outpatient clinic population aged 40-80 with established CV disease using a secure multi party computation (MPC) approach. Using MPC electronic health record data (EHR) was linked to health insurance claim data to provide outcome data. The repository here describes the insurance codes used to define the SMART2 endpoint as well as the baseline definition of CV disease. 

## 📂 Repository Structure

```
secure_recalibration/
├── baseline/                   # Folder containing the information on definition of baseline CV disease presence
│   └── baseline_presence.html
│   └── baseline_presence.pdf
├── insurance_codes/            # Folder containing the information on codes used for ascertainment of outcomes using insurance codes
│   └── insurance_codes.html
│   └── insurance_codes.pdf
├── docs/
│   └── baseline_presence.html  # HTML rendering of the RMarkdown file describing the codes used for baseline presence of CV disease
│   └── insurance_codes.html    # HTML rendering of the RMarkdown file describin the insurance codes used for outcome ascertainment
└── README.md                    # This file
```

## 📬 Contact

- 📧 [j.holtrop-3@umcutrecht.nl](mailto:j.holtrop-3@umcutrecht.nl)
- 📧 [holtropjoris@gmail.com](mailto:holtropjoris@gmail.com)

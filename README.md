# HealthcareDataforLZentropyAnalysis



\# Synthea interoperability sample dataset (78 patients)



This repository contains a reproducible, synthetic dataset generated using

\[Synthea](https://synthetichealth.github.io/synthea/).



It provides \*\*78 matched patient summaries\*\* expressed in three interoperability

formats:



\- FHIR (JSON)

\- CDA (XML)

\- HL7 v2



Each patient appears once in each format, allowing direct comparison across

representations



The origin of the FHIR and CDA formats are the Massachusetts general (Mass 1k) Synthea dataset.

The HL7 v2 versions were generated as a concatenated set of HL7v2 messages representing the same data as the FHIR and CDA formats (using the FHIR formats as a basis)



Filenames share a common stub per patient, enabling deterministic matching

between formats.



\## Data characteristics



\- \*\*Synthetic data only\*\* (no real patient information)

\- Generated with Synthea

\- Suitable for research, benchmarking, and reproducibility studies

\- No clinical validity is implied



\## Intended use



This dataset is intended to support reproducible research into:

\- healthcare interoperability

\- structured data representations

\- information theory and embeddings

\- comparative analysis of FHIR, CDA, and HL7



\## License



This dataset is released under the MIT License.




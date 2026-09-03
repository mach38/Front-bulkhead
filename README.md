# Front-bulkhead
Rule compliant front bulkhead for FSUK 2026, designed in SolidWorks and ran FEA against a frontal impact and torsional rigidity


Material: AISI 1020 Cold rolled steel
<img width="353" height="272" alt="image" src="https://github.com/user-attachments/assets/ab1bb34a-4c7d-44b9-91ca-36e890192c77" />

## Design
| Parameter | Value |
|---|---|
| Bulkhead height | 300 mm |
| Bulkhead width | 400 mm |
| Front hoop height | 370 mm |
| Foot box length | 550 mm |
| Tube profile | 26.9 mm OD x 3.2 mm wall |
Front bulkhead category: 119 mm² / 8509 mm⁴ minimum → design achieves ≈238 mm² / ≈17,033 mm⁴
## FEA results
### Frontal impact
Applied load: 117,720 N (300 kg × 40g × 9.81 m/s²), distributed across the bulkhead face
Fixed constraint: front hoop end joints
Representative mid-span Factor of Safety: ≈3 on primary diagonal members
Lowest observed FOS: ≈1.1
## Torsional Rigidity
Test load: ±500 N force couple applied at front bulkhead top nodes (arbitrary linear-elastic test load)
Result: ≈145,000 Nm/deg

# Front-bulkhead
Rule compliant front bulkhead for FSUK 2026, designed in SolidWorks and ran FEA against a frontal impact and torsional rigidity

<img width="353" height="272" alt="image" src="https://github.com/user-attachments/assets/ab1bb34a-4c7d-44b9-91ca-36e890192c77" />

Material: AISI 1020 Cold rolled steel

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
<img width="935" height="398" alt="image" src="https://github.com/user-attachments/assets/1832ebb4-bf40-4a76-9447-14edd1b1eb14" />

Applied load: 117,720 N (300 kg × 40g × 9.81 m/s²), distributed across the bulkhead face. The fixed constraint was the front hoop end joints, found a factor of Safety: ≈3 on primary diagonal members. lowest observed FOS: ≈ 0.37 on front loop
## Torsional Rigidity
<img width="892" height="397" alt="image" src="https://github.com/user-attachments/assets/c5cbda56-fd62-4650-b4b9-679f44629585" />

Test load: ±500 N force couple applied at front bulkhead top nodes
Result: ≈145,000 Nm/deg

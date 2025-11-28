# 📊 DummyWHIR

How to read this report:
- Table rows correspond to security regimes
- Table columns correspond to proof system components
- Cells show bits of security per component
- Proof size estimate is only indicative

**Parameters:**
- Polynomial commitment scheme: WHIR
- Hash size (bits): 256
- Field: Goldilocks²
- Iterations (M): 5
- Folding factor (k): 4
- Constraint degree: 1
- Batch size: 100
- Batching: Powers
- Queries per iteration: [80, 35, 22, 12, 9]
- OOD samples per iteration: [2, 2, 2, 2]
- Total grinding overhead log2: 20.03

**Proof Size Estimate:** 168 KiB, where 1 KiB = 1024 bytes

| regime | total | OOD(i=1) | OOD(i=2) | OOD(i=3) | OOD(i=4) | Shift(i=1) | Shift(i=2) | Shift(i=3) | Shift(i=4) | batching | fin | fold(i=0,s=1) | fold(i=0,s=2) | fold(i=0,s=3) | fold(i=0,s=4) | fold(i=1,s=1) | fold(i=1,s=2) | fold(i=1,s=3) | fold(i=1,s=4) | fold(i=2,s=1) | fold(i=2,s=2) | fold(i=2,s=3) | fold(i=2,s=4) | fold(i=3,s=1) | fold(i=3,s=2) | fold(i=3,s=3) | fold(i=3,s=4) | fold(i=4,s=1) | fold(i=4,s=2) | fold(i=4,s=3) | fold(i=4,s=4) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UDR | 21 | 219 | 227 | 235 | 243 | 33 | 31 | 21 | 23 | 107 | 28 | 113 | 114 | 115 | 116 | 114 | 115 | 116 | 117 | 115 | 116 | 117 | 118 | 116 | 117 | 118 | 119 | 117 | 118 | 119 | 120 |
| JBR | 36 | 203 | 205 | 207 | 209 | 36 | 68 | 76 | 71 | 85 | 78 | 93 | 94 | 95 | 96 | 89 | 90 | 91 | 92 | 86 | 87 | 88 | 89 | 82 | 83 | 84 | 85 | 79 | 80 | 81 | 82 |

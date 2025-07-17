| Name                         | [MICRO'20] Graphene                      |
|------------------------------|------------------------------------------|
| Summary                      | 
| Category                     | Preventive
| Deterministic                | Deterministic
| Detection Mechanism          | Count-Based
| Mitigation Mechanism         | Victim refresh
| Implementaion Place          | MC
| Storage overhead             | high (SRAM)
| Perf. overhead               | low
| Pessimism Assumptions        | high
| Multi-Agg                    | yes
| Half-Double                  | yes
| DoS res.                     | no
| RowPress res.                | no
| Scalability                  | 
| Dependency on Mitigations    | 
| Side Channel Vulnerabilities |
| T_RH                         | 50k, 20k
| Compared designs             | PARA, CBT, TWiCe

### Summary
- Use Misra-Gries algorithm for tracking aggressors
  - If the item is **already in** the table: increment its count by 1
  - If there is an **empty slot** in the table: insert the new item with an initial count of 1
  - If the table is **full** and the item is not present: decrement the count of all entries by 1; remove any entries whose count drops to 0
- guarantee any row that has been activated more than T times is tracked by the counter table
- 81-entries per bank

### Strength
- Guaranteed protection
  - <-> PARA (probabilistic mitigation)
- Low energy
  - no false positive

### Weakness


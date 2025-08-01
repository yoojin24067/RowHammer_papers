# RowHammer Works

### Attack
|Check |Year |Conference |Name |Note |
|------|-----|-----------|-----|-----|
| |2019 |Security | [ECCploit](https://ieeexplore.ieee.org/abstract/document/8835222) | defeat ECC
| |2020 |SP       | [TRRespass](https://ieeexplore.ieee.org/abstract/document/9152631) |
| |2021 |Security | [SMASH](https://www.usenix.org/conference/usenixsecurity21/presentation/ridder) | Many-sided attack from SW |
| |2022 |Security | [Half-Double](https://www.usenix.org/conference/usenixsecurity22/presentation/kogler-half-double) | Exploit TRR refresh, Blind-Hammering | 
| |2022 |SP       | [Blacksmith](https://ieeexplore.ieee.org/abstract/document/9833772) | Frequency domain attack |
| |2025	|ASPLOS	  | [Marionette](https://dl.acm.org/doi/abs/10.1145/3669940.3707242) | Row coupling |
| |2025	|HPCA	    | [Chronos](https://ieeexplore.ieee.org/abstract/document/10946773) | PRAC target
| |2025	|ISCA	    | When Mitigations Backfire

### Mitigation
- Prior works: [Excel](https://o365skku-my.sharepoint.com/:x:/g/personal/g24067yjs_o365_skku_edu/Ecd5ipVKx05NrmQ5qus-fZ0BglMoKMQMoRMIZPY-5Cl_2g?e=auwctj)
  
|Check |Year |Conference |Name |Category |Note |
|------|-----|-----------|-----|---------|-----|
| |2014 |ISCA     | [PARA](https://ieeexplore.ieee.org/abstract/document/6853210) | Probabilistic refresh |
| |2016 |LCA      | [CBT](https://ieeexplore.ieee.org/abstract/document/7579600) |  | Multi-layer counter |
| |2020 |MICRO    | [Graphene](https://ieeexplore.ieee.org/abstract/document/9251863) |
| |2021	|HPCA	    | [BlockHammer](https://ieeexplore.ieee.org/abstract/document/9407238) |
| |2021	|ICCD	    | HammerFilter
| |2022	|ISCA	    | [Hydra](https://dl.acm.org/doi/abs/10.1145/3470496.3527421) |
| |2023	|CCS	    | [RAMPART](https://dl.acm.org/doi/abs/10.1145/3631882.3631886) |  | Similar with Cube |
| |2023	|HPCA	    | [SRS](https://ieeexplore.ieee.org/abstract/document/10070999) |  | Juggernaut attack pattern |
| |2023 |HPCA     | [SHADOW](https://ieeexplore.ieee.org/abstract/document/10070966) | Row shuffle | Intra-subarray row shuffling |
| |2023	|MICRO	  | [Cube](https://dl.acm.org/doi/abs/10.1145/3613424.3623777) | | Similar with RAMPART |
| |2024	|ASPOLS	  | Rubix
| |2024	|HPCA	    | [START](https://ieeexplore.ieee.org/abstract/document/10476473) |
| |2024 |ISCA     | [PrIDE](https://ieeexplore.ieee.org/abstract/document/10609688) |
| |2024	|MICRO    | [BreakHammer](https://ieeexplore.ieee.org/abstract/document/10764696) |
| |2024	|Security	| [ABACuS](https://www.usenix.org/conference/usenixsecurity24/presentation/olgun) |
| |2025	|ASPLOS	  | MOAT
| |2025	|arxiv    | [CnC-PRAC](https://arxiv.org/abs/2506.11970) |
| |2025	|DRAMSEC  | Counterpoint
| |2025	|DRAMSEC  | DRFM
| |2025	|HPCA	    | AutoRFM
| |2025	|HPCA	    | DAPPER
| |2025	|HPCA	    | PaCRAM
| |2025	|HPCA	    | [QPRAC](https://ieeexplore.ieee.org/abstract/document/10946754) |
| |2025	|ISCA	    | [DREAM](https://dl.acm.org/doi/full/10.1145/3695053.3731117) |
| |2025	|ISCA	    | [MoPAC](https://dl.acm.org/doi/full/10.1145/3695053.3730997) |
| |2025	|ISCAS    | AxRA
| |2025	|	        | PrisonBreak
| |2025	|Security	| MCSEE
| |2025	|arxiv    | [LeakyHammer](https://arxiv.org/abs/2503.17891) |  | Side channel vulnerabilities introduced by RowHammer defenses
| |2025	|arxiv    | [Inter-VM RowHammer simulation](https://arxiv.org/abs/2506.07190) |
| |2025	|uASC	    | Flipper

### Others
|Check |Category |Year |Conference |Name |
|------|---------|-----|-----------|-----|
| |BER |2020 |ISCA | [Revisiting RowHammer vulnerability](https://ieeexplore.ieee.org/abstract/document/9138944) |
| |GPU |2025 |SEC | [GPUHammer](https://arxiv.org/abs/2507.08166) |
| |GPU |2025 |SEC | [Attacking GPUs using RFM Rowhammer Mitigation](https://www.usenix.org/conference/usenixsecurity25/presentation/nazaraliyev) |
| |RowPress |2023 |ISCA | [RowPress](https://dl.acm.org/doi/abs/10.1145/3579371.3589063) |

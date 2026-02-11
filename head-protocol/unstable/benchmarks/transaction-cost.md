--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 05:01:05.137792413 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6042 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 15.22 | 4.84 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 43.76 | 12.52 | 0.63 |
| 4 | 228 | 862 | 49.53 | 14.31 | 0.69 |
| 5 | 285 | 969 | 56.22 | 16.33 | 0.76 |
| 6 | 338 | 1081 | 73.76 | 20.97 | 0.94 |
| 7 | 393 | 1192 | 80.39 | 22.88 | 1.02 |
| 8 | 448 | 1307 | 82.27 | 23.72 | 1.04 |
| 10 | 561 | 1525 | 96.84 | 27.93 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 2000 | 26.42 | 8.96 | 0.52 |
| 3| 2123 | 28.13 | 10.10 | 0.54 |
| 5| 2384 | 30.88 | 12.21 | 0.59 |
| 10| 3149 | 41.03 | 18.36 | 0.75 |
| 40| 7525 | 97.21 | 53.98 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.53 | 7.30 | 0.41 |
| 2| 841 | 25.44 | 8.77 | 0.46 |
| 3| 926 | 26.05 | 9.58 | 0.47 |
| 5| 1207 | 29.15 | 11.79 | 0.52 |
| 10| 2043 | 40.02 | 18.16 | 0.69 |
| 43| 6670 | 96.26 | 55.77 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.09 | 8.89 | 0.48 |
| 2| 814 | 30.91 | 10.06 | 0.51 |
| 3| 967 | 33.51 | 11.46 | 0.55 |
| 5| 1164 | 33.62 | 12.82 | 0.57 |
| 10| 2045 | 48.12 | 20.25 | 0.78 |
| 36| 6028 | 98.93 | 51.89 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.79 | 10.15 | 0.53 |
| 2| 833 | 35.88 | 11.39 | 0.56 |
| 3| 1053 | 39.30 | 13.04 | 0.61 |
| 5| 1327 | 43.43 | 15.51 | 0.67 |
| 10| 2025 | 54.21 | 21.85 | 0.83 |
| 29| 4964 | 98.89 | 46.95 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 27.08 | 9.09 | 0.69 |
| 2| 5869 | 34.84 | 11.65 | 0.77 |
| 3| 6048 | 44.89 | 15.10 | 0.89 |
| 4| 6192 | 51.38 | 17.28 | 0.96 |
| 5| 6412 | 64.61 | 21.73 | 1.11 |
| 6| 6525 | 73.62 | 24.79 | 1.21 |
| 7| 6739 | 84.05 | 28.39 | 1.33 |
| 8| 6976 | 94.50 | 31.89 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.56 | 6.54 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |


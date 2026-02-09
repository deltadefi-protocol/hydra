--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-09 16:20:04.64186146 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7648 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.32 | 9.66 | 0.52 |
| 3 | 170 | 747 | 42.65 | 12.27 | 0.62 |
| 4 | 227 | 862 | 51.17 | 14.70 | 0.71 |
| 5 | 284 | 969 | 59.46 | 17.11 | 0.80 |
| 6 | 340 | 1081 | 68.00 | 19.48 | 0.89 |
| 7 | 394 | 1192 | 76.56 | 22.00 | 0.98 |
| 8 | 449 | 1303 | 96.05 | 27.02 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1828 | 23.92 | 7.60 | 0.48 |
| 2| 1938 | 25.76 | 8.76 | 0.51 |
| 3| 2055 | 27.24 | 9.84 | 0.53 |
| 5| 2365 | 31.45 | 12.35 | 0.60 |
| 10| 3261 | 44.28 | 19.27 | 0.79 |
| 39| 7528 | 97.76 | 53.49 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.80 | 7.37 | 0.41 |
| 2| 696 | 22.62 | 7.97 | 0.42 |
| 3| 853 | 24.07 | 9.03 | 0.45 |
| 5| 1333 | 32.43 | 12.73 | 0.56 |
| 10| 2080 | 40.05 | 18.18 | 0.70 |
| 41| 6606 | 99.35 | 55.33 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.51 | 8.47 | 0.46 |
| 2| 779 | 30.98 | 10.08 | 0.51 |
| 3| 920 | 32.72 | 11.23 | 0.54 |
| 5| 1356 | 38.21 | 14.15 | 0.62 |
| 10| 2055 | 47.96 | 20.21 | 0.77 |
| 34| 5746 | 92.91 | 48.89 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.16 | 0.53 |
| 2| 814 | 35.92 | 11.40 | 0.56 |
| 3| 940 | 37.88 | 12.61 | 0.59 |
| 5| 1338 | 44.15 | 15.73 | 0.68 |
| 10| 2032 | 53.94 | 21.78 | 0.83 |
| 30| 4886 | 98.40 | 47.45 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.08 | 9.08 | 0.69 |
| 2| 6010 | 37.04 | 12.50 | 0.80 |
| 3| 6045 | 44.96 | 15.11 | 0.89 |
| 4| 6195 | 51.68 | 17.38 | 0.97 |
| 5| 6309 | 59.51 | 19.95 | 1.05 |
| 6| 6515 | 72.93 | 24.54 | 1.20 |
| 7| 6532 | 75.26 | 25.24 | 1.23 |
| 8| 6877 | 89.75 | 30.23 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.05 | 6.02 | 0.60 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1709 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 12:54:47.669347524 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 43.90 | 12.57 | 0.63 |
| 4 | 228 | 858 | 48.46 | 14.08 | 0.68 |
| 5 | 284 | 969 | 59.73 | 17.21 | 0.80 |
| 6 | 338 | 1081 | 68.41 | 19.69 | 0.89 |
| 7 | 394 | 1192 | 76.62 | 22.06 | 0.98 |
| 8 | 448 | 1303 | 94.51 | 26.75 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1971 | 26.91 | 9.08 | 0.52 |
| 3| 2055 | 27.31 | 9.86 | 0.53 |
| 5| 2370 | 31.00 | 12.24 | 0.59 |
| 10| 3245 | 43.39 | 19.03 | 0.78 |
| 40| 7750 | 99.90 | 54.72 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.81 | 7.37 | 0.42 |
| 2| 777 | 23.63 | 8.24 | 0.43 |
| 3| 898 | 25.52 | 9.47 | 0.46 |
| 5| 1298 | 30.19 | 12.08 | 0.54 |
| 10| 2114 | 41.97 | 18.73 | 0.72 |
| 44| 6709 | 97.01 | 56.65 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.17 | 8.91 | 0.48 |
| 2| 737 | 30.19 | 9.84 | 0.50 |
| 3| 972 | 33.47 | 11.45 | 0.55 |
| 5| 1305 | 35.72 | 13.46 | 0.59 |
| 10| 2044 | 45.68 | 19.60 | 0.75 |
| 36| 5976 | 99.05 | 51.91 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 867 | 36.56 | 11.60 | 0.57 |
| 3| 1040 | 38.55 | 12.81 | 0.60 |
| 5| 1259 | 42.61 | 15.27 | 0.66 |
| 10| 2088 | 54.58 | 21.97 | 0.84 |
| 30| 4664 | 96.12 | 46.73 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 27.00 | 9.07 | 0.69 |
| 2| 5820 | 31.60 | 10.50 | 0.74 |
| 3| 6155 | 45.89 | 15.48 | 0.90 |
| 4| 6235 | 53.51 | 18.04 | 0.99 |
| 5| 6287 | 59.70 | 20.05 | 1.05 |
| 6| 6604 | 75.12 | 25.32 | 1.23 |
| 7| 6538 | 78.52 | 26.31 | 1.26 |
| 8| 7007 | 94.42 | 31.98 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 567 | 6172 | 40.13 | 14.67 | 0.85 |
| 10 | 37 | 2106 | 7091 | 94.58 | 36.18 | 1.49 |


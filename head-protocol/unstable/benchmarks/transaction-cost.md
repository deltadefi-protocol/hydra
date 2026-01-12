--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 10:03:04.328288068 UTC |
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
| 1| 5838 | 10.78 | 3.43 | 0.52 |
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7651 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 751 | 42.62 | 12.26 | 0.62 |
| 4 | 225 | 862 | 53.64 | 15.27 | 0.73 |
| 5 | 285 | 974 | 62.72 | 17.92 | 0.83 |
| 6 | 337 | 1081 | 75.71 | 21.40 | 0.96 |
| 7 | 396 | 1196 | 85.58 | 24.25 | 1.07 |
| 8 | 454 | 1303 | 95.50 | 26.93 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 1931 | 25.84 | 8.78 | 0.51 |
| 3| 2116 | 28.06 | 10.08 | 0.54 |
| 5| 2396 | 31.64 | 12.41 | 0.60 |
| 10| 3002 | 37.21 | 17.31 | 0.71 |
| 39| 7606 | 99.60 | 53.95 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.84 | 7.39 | 0.42 |
| 2| 801 | 25.53 | 8.79 | 0.46 |
| 3| 993 | 26.10 | 9.60 | 0.47 |
| 5| 1196 | 29.03 | 11.75 | 0.52 |
| 10| 2025 | 40.80 | 18.40 | 0.70 |
| 42| 6787 | 99.61 | 56.09 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 28.46 | 8.69 | 0.47 |
| 2| 813 | 29.18 | 9.60 | 0.49 |
| 3| 1080 | 32.29 | 11.17 | 0.54 |
| 5| 1257 | 34.85 | 13.20 | 0.58 |
| 10| 2173 | 49.23 | 20.60 | 0.79 |
| 35| 5885 | 96.86 | 50.66 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 809 | 35.92 | 11.40 | 0.56 |
| 3| 1042 | 38.59 | 12.82 | 0.60 |
| 5| 1210 | 42.15 | 15.13 | 0.65 |
| 10| 1975 | 53.38 | 21.60 | 0.82 |
| 29| 5010 | 99.29 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.12 | 9.10 | 0.69 |
| 2| 5995 | 37.06 | 12.49 | 0.80 |
| 3| 5943 | 38.13 | 12.69 | 0.81 |
| 4| 6140 | 50.29 | 16.83 | 0.95 |
| 5| 6193 | 58.42 | 19.59 | 1.04 |
| 6| 6552 | 73.52 | 24.78 | 1.21 |
| 7| 6694 | 81.73 | 27.57 | 1.30 |
| 8| 6864 | 90.64 | 30.48 | 1.40 |
| 9| 6810 | 93.30 | 31.31 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1138 | 6513 | 61.31 | 22.98 | 1.10 |
| 10 | 30 | 1711 | 6858 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |


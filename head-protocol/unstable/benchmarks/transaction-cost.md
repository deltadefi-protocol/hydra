--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-19 09:36:32.787358417 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6042 | 12.32 | 3.89 | 0.54 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.91 | 5.98 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 42.34 | 12.17 | 0.61 |
| 4 | 226 | 858 | 53.87 | 15.40 | 0.73 |
| 5 | 282 | 969 | 64.41 | 18.30 | 0.85 |
| 6 | 341 | 1081 | 71.29 | 20.30 | 0.92 |
| 7 | 396 | 1192 | 83.03 | 23.56 | 1.04 |
| 8 | 451 | 1307 | 88.66 | 25.24 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.37 | 7.71 | 0.48 |
| 2| 1992 | 26.92 | 9.09 | 0.52 |
| 3| 2073 | 26.94 | 9.77 | 0.53 |
| 5| 2383 | 31.00 | 12.24 | 0.59 |
| 10| 3220 | 42.11 | 18.66 | 0.77 |
| 41| 7462 | 96.47 | 54.40 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 772 | 24.28 | 8.45 | 0.44 |
| 3| 956 | 26.10 | 9.60 | 0.47 |
| 5| 1269 | 31.21 | 12.39 | 0.55 |
| 10| 2008 | 39.58 | 18.04 | 0.69 |
| 39| 5981 | 89.22 | 51.16 | 1.50 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 29.17 | 8.91 | 0.48 |
| 2| 870 | 29.90 | 9.82 | 0.50 |
| 3| 983 | 33.47 | 11.46 | 0.55 |
| 5| 1309 | 35.56 | 13.42 | 0.59 |
| 10| 2140 | 45.50 | 19.56 | 0.75 |
| 35| 5627 | 98.18 | 50.88 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 859 | 36.56 | 11.60 | 0.57 |
| 3| 995 | 38.62 | 12.83 | 0.60 |
| 5| 1345 | 44.11 | 15.72 | 0.68 |
| 10| 2033 | 54.35 | 21.90 | 0.84 |
| 29| 5046 | 99.80 | 47.29 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5821 | 31.52 | 10.47 | 0.74 |
| 3| 6087 | 44.92 | 15.07 | 0.89 |
| 4| 6327 | 57.48 | 19.46 | 1.03 |
| 5| 6284 | 56.92 | 19.09 | 1.02 |
| 6| 6651 | 75.38 | 25.41 | 1.24 |
| 7| 6579 | 81.16 | 27.27 | 1.29 |
| 8| 7029 | 93.70 | 31.57 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 56 | 5867 | 20.71 | 7.04 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 571 | 6176 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2217 | 7156 | 98.24 | 37.65 | 1.53 |


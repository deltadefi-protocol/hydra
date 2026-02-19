--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-19 15:55:40.484482157 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 29.26 | 9.23 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 34.38 | 9.91 | 0.53 |
| 3 | 171 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 226 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 284 | 969 | 62.52 | 17.81 | 0.83 |
| 6 | 338 | 1081 | 63.51 | 18.44 | 0.84 |
| 7 | 394 | 1192 | 74.48 | 21.46 | 0.96 |
| 8 | 450 | 1303 | 94.52 | 26.80 | 1.16 |
| 9 | 506 | 1414 | 96.97 | 27.75 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2073 | 27.47 | 9.90 | 0.53 |
| 5| 2275 | 29.30 | 11.75 | 0.57 |
| 10| 3228 | 41.97 | 18.65 | 0.77 |
| 42| 7838 | 98.06 | 55.55 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 758 | 23.54 | 8.23 | 0.43 |
| 3| 882 | 25.51 | 9.46 | 0.46 |
| 5| 1168 | 28.54 | 11.65 | 0.52 |
| 10| 2093 | 40.47 | 18.29 | 0.70 |
| 41| 6704 | 98.05 | 54.99 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.50 | 8.46 | 0.46 |
| 2| 793 | 31.21 | 10.15 | 0.51 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1206 | 34.29 | 13.02 | 0.57 |
| 10| 2011 | 44.14 | 19.14 | 0.73 |
| 36| 5829 | 96.61 | 51.22 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.88 | 11.39 | 0.56 |
| 3| 958 | 37.88 | 12.61 | 0.59 |
| 5| 1360 | 43.99 | 15.69 | 0.68 |
| 10| 2057 | 53.90 | 21.77 | 0.83 |
| 30| 4867 | 97.69 | 47.24 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 26.92 | 9.04 | 0.69 |
| 2| 6005 | 37.08 | 12.50 | 0.80 |
| 3| 6114 | 45.49 | 15.37 | 0.90 |
| 4| 6120 | 52.77 | 17.73 | 0.97 |
| 5| 6260 | 59.40 | 19.89 | 1.05 |
| 6| 6605 | 75.62 | 25.51 | 1.24 |
| 7| 6704 | 80.24 | 27.06 | 1.29 |
| 8| 6923 | 92.34 | 31.13 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.55 | 14.13 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |


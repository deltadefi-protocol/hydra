--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-30 03:16:37.269980853 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 15.07 | 4.78 | 0.58 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 227 | 862 | 53.78 | 15.30 | 0.73 |
| 5 | 284 | 974 | 64.61 | 18.37 | 0.85 |
| 6 | 341 | 1081 | 64.16 | 18.60 | 0.85 |
| 7 | 393 | 1192 | 83.27 | 23.51 | 1.04 |
| 8 | 449 | 1303 | 94.48 | 26.69 | 1.16 |
| 9 | 505 | 1414 | 88.50 | 25.60 | 1.11 |
| 10 | 560 | 1525 | 97.76 | 28.28 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2104 | 28.06 | 10.08 | 0.54 |
| 5| 2382 | 31.28 | 12.31 | 0.60 |
| 10| 3106 | 40.62 | 18.26 | 0.75 |
| 41| 7783 | 99.64 | 55.34 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.81 | 7.37 | 0.42 |
| 2| 740 | 24.35 | 8.46 | 0.44 |
| 3| 849 | 23.99 | 9.01 | 0.45 |
| 5| 1245 | 29.08 | 11.77 | 0.52 |
| 10| 2124 | 42.28 | 18.82 | 0.72 |
| 41| 6388 | 93.71 | 53.77 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.54 | 8.47 | 0.46 |
| 2| 878 | 29.82 | 9.80 | 0.50 |
| 3| 902 | 30.23 | 10.54 | 0.51 |
| 5| 1214 | 37.06 | 13.78 | 0.60 |
| 10| 2123 | 45.98 | 19.71 | 0.76 |
| 35| 5783 | 94.42 | 49.96 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 887 | 36.64 | 11.62 | 0.57 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1295 | 43.32 | 15.49 | 0.67 |
| 10| 2217 | 57.06 | 22.71 | 0.87 |
| 28| 4720 | 95.15 | 45.26 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5963 | 35.93 | 12.08 | 0.79 |
| 3| 6084 | 44.96 | 15.09 | 0.89 |
| 4| 6299 | 52.15 | 17.58 | 0.98 |
| 5| 6458 | 65.36 | 22.05 | 1.12 |
| 6| 6542 | 73.13 | 24.58 | 1.21 |
| 7| 6715 | 85.02 | 28.72 | 1.34 |
| 8| 6834 | 90.25 | 30.43 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.67 | 30.67 | 1.32 |
| 10 | 37 | 2109 | 7094 | 94.58 | 36.18 | 1.49 |


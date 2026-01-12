--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 13:24:59.332214501 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.90 | 5.97 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.23 | 11.94 | 0.60 |
| 4 | 227 | 862 | 52.43 | 15.00 | 0.72 |
| 5 | 282 | 969 | 62.65 | 17.84 | 0.83 |
| 6 | 337 | 1081 | 64.03 | 18.60 | 0.85 |
| 7 | 392 | 1192 | 81.21 | 23.16 | 1.03 |
| 8 | 449 | 1303 | 87.07 | 24.86 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 22.92 | 7.32 | 0.47 |
| 2| 1927 | 25.88 | 8.79 | 0.51 |
| 3| 2153 | 28.10 | 10.09 | 0.54 |
| 5| 2398 | 31.00 | 12.24 | 0.59 |
| 10| 3129 | 40.82 | 18.31 | 0.75 |
| 43| 7756 | 97.69 | 56.13 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.81 | 7.37 | 0.42 |
| 2| 739 | 24.08 | 8.41 | 0.44 |
| 3| 951 | 27.07 | 9.88 | 0.48 |
| 5| 1236 | 29.94 | 12.02 | 0.53 |
| 10| 1983 | 39.98 | 18.15 | 0.69 |
| 40| 6425 | 96.27 | 53.81 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 26.83 | 8.26 | 0.45 |
| 2| 906 | 29.89 | 9.82 | 0.50 |
| 3| 903 | 30.15 | 10.52 | 0.51 |
| 5| 1236 | 34.22 | 13.01 | 0.57 |
| 10| 1940 | 46.42 | 19.75 | 0.75 |
| 36| 6048 | 97.69 | 51.56 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 980 | 38.62 | 12.83 | 0.60 |
| 5| 1199 | 41.97 | 15.07 | 0.65 |
| 10| 1978 | 53.23 | 21.56 | 0.82 |
| 28| 4694 | 95.26 | 45.27 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.08 | 9.09 | 0.69 |
| 2| 5939 | 35.76 | 12.01 | 0.79 |
| 3| 6064 | 45.18 | 15.17 | 0.89 |
| 4| 6292 | 54.78 | 18.49 | 1.00 |
| 5| 6425 | 64.10 | 21.56 | 1.11 |
| 6| 6679 | 77.43 | 26.23 | 1.26 |
| 7| 6542 | 75.55 | 25.36 | 1.23 |
| 8| 6904 | 85.87 | 29.01 | 1.36 |
| 9| 6920 | 98.40 | 33.07 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2160 | 7122 | 96.00 | 36.77 | 1.50 |


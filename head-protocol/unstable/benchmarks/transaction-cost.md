--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-03 16:10:54.672163654 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6035 | 13.01 | 4.14 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 99.33 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 41.24 | 11.91 | 0.60 |
| 4 | 227 | 858 | 48.27 | 14.00 | 0.68 |
| 5 | 284 | 969 | 62.51 | 17.78 | 0.83 |
| 6 | 339 | 1081 | 74.86 | 21.12 | 0.95 |
| 7 | 396 | 1192 | 77.02 | 22.20 | 0.98 |
| 8 | 451 | 1307 | 91.55 | 25.94 | 1.13 |
| 9 | 506 | 1414 | 99.25 | 28.35 | 1.22 |
| 10 | 563 | 1525 | 98.06 | 28.42 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1989 | 26.92 | 9.08 | 0.52 |
| 3| 2116 | 28.13 | 10.10 | 0.54 |
| 5| 2339 | 30.34 | 12.04 | 0.59 |
| 10| 3191 | 42.34 | 18.75 | 0.77 |
| 41| 7670 | 97.91 | 54.86 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.77 | 7.36 | 0.42 |
| 2| 760 | 24.08 | 8.40 | 0.44 |
| 3| 919 | 26.71 | 9.81 | 0.48 |
| 5| 1293 | 31.03 | 12.33 | 0.55 |
| 10| 2103 | 42.37 | 18.81 | 0.72 |
| 41| 6525 | 99.60 | 55.34 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.51 | 8.47 | 0.46 |
| 2| 865 | 29.94 | 9.83 | 0.50 |
| 3| 961 | 30.98 | 10.76 | 0.52 |
| 5| 1329 | 36.51 | 13.69 | 0.60 |
| 10| 2067 | 48.44 | 20.35 | 0.78 |
| 36| 5967 | 98.30 | 51.70 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 33.83 | 10.16 | 0.53 |
| 2| 881 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1269 | 42.68 | 15.29 | 0.66 |
| 10| 1969 | 53.50 | 21.63 | 0.83 |
| 30| 5032 | 99.69 | 47.81 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.08 | 9.08 | 0.69 |
| 2| 5928 | 35.88 | 12.06 | 0.79 |
| 3| 6170 | 45.90 | 15.45 | 0.90 |
| 4| 6310 | 55.01 | 18.53 | 1.01 |
| 5| 6360 | 62.82 | 21.09 | 1.09 |
| 6| 6654 | 75.43 | 25.44 | 1.24 |
| 7| 6598 | 79.70 | 26.81 | 1.28 |
| 8| 7027 | 94.68 | 31.93 | 1.45 |
| 9| 6894 | 95.16 | 32.03 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 58 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 571 | 6175 | 38.37 | 14.06 | 0.83 |
| 10 | 20 | 1137 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2220 | 7159 | 99.38 | 38.04 | 1.54 |


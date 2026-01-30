--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-30 04:00:57.719668547 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 227 | 858 | 54.09 | 15.42 | 0.74 |
| 5 | 284 | 969 | 62.51 | 17.78 | 0.83 |
| 6 | 339 | 1081 | 64.05 | 18.60 | 0.85 |
| 7 | 395 | 1192 | 82.70 | 23.47 | 1.04 |
| 8 | 450 | 1303 | 94.17 | 26.62 | 1.16 |
| 9 | 507 | 1418 | 96.30 | 27.53 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1988 | 26.58 | 9.01 | 0.52 |
| 3| 2013 | 25.91 | 9.48 | 0.52 |
| 5| 2438 | 32.20 | 12.57 | 0.61 |
| 10| 3091 | 39.55 | 17.96 | 0.74 |
| 41| 7806 | 99.49 | 55.27 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.37 | 0.42 |
| 2| 735 | 24.04 | 8.39 | 0.44 |
| 3| 828 | 24.02 | 9.01 | 0.45 |
| 5| 1368 | 32.20 | 12.65 | 0.56 |
| 10| 2008 | 38.80 | 17.84 | 0.68 |
| 43| 6770 | 98.63 | 56.47 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 784 | 30.91 | 10.06 | 0.51 |
| 3| 1007 | 31.57 | 10.95 | 0.53 |
| 5| 1164 | 33.51 | 12.79 | 0.56 |
| 10| 1985 | 47.55 | 20.07 | 0.77 |
| 34| 5830 | 95.62 | 49.66 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 874 | 36.64 | 11.62 | 0.57 |
| 3| 998 | 38.59 | 12.82 | 0.60 |
| 5| 1278 | 42.65 | 15.28 | 0.66 |
| 10| 2055 | 54.89 | 22.05 | 0.84 |
| 29| 4931 | 97.59 | 46.59 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.09 | 9.09 | 0.69 |
| 2| 5775 | 28.38 | 9.34 | 0.70 |
| 3| 6136 | 44.72 | 15.04 | 0.89 |
| 4| 6194 | 51.69 | 17.35 | 0.97 |
| 5| 6422 | 61.31 | 20.61 | 1.08 |
| 6| 6672 | 76.45 | 25.87 | 1.25 |
| 7| 6537 | 75.70 | 25.37 | 1.23 |
| 8| 6782 | 88.88 | 29.92 | 1.38 |
| 9| 6809 | 92.85 | 31.19 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |


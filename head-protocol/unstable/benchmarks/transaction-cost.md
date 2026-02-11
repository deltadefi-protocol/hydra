--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 07:56:15.945037991 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14283 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.09 | 11.64 | 0.59 |
| 4 | 225 | 858 | 52.26 | 14.96 | 0.72 |
| 5 | 282 | 974 | 62.58 | 17.82 | 0.83 |
| 6 | 339 | 1081 | 71.18 | 20.27 | 0.92 |
| 7 | 393 | 1192 | 85.86 | 24.14 | 1.07 |
| 8 | 449 | 1303 | 94.18 | 26.62 | 1.16 |
| 9 | 507 | 1418 | 93.87 | 27.00 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 23.92 | 7.60 | 0.48 |
| 2| 1943 | 25.84 | 8.78 | 0.51 |
| 3| 2124 | 28.06 | 10.08 | 0.54 |
| 5| 2407 | 31.63 | 12.41 | 0.60 |
| 10| 3244 | 42.97 | 18.91 | 0.78 |
| 38| 7298 | 94.12 | 51.80 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.32 | 0.41 |
| 2| 719 | 22.56 | 7.94 | 0.42 |
| 3| 906 | 25.10 | 9.32 | 0.46 |
| 5| 1351 | 31.95 | 12.60 | 0.56 |
| 10| 1980 | 38.72 | 17.80 | 0.68 |
| 41| 6677 | 96.85 | 54.67 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 869 | 32.08 | 11.03 | 0.53 |
| 5| 1282 | 34.97 | 13.23 | 0.58 |
| 10| 2113 | 45.39 | 19.53 | 0.75 |
| 37| 6160 | 99.69 | 52.80 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 825 | 35.85 | 11.38 | 0.56 |
| 3| 998 | 38.55 | 12.81 | 0.60 |
| 5| 1252 | 42.61 | 15.27 | 0.66 |
| 10| 1989 | 53.83 | 21.73 | 0.83 |
| 29| 4846 | 98.66 | 46.91 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.08 | 9.09 | 0.69 |
| 2| 5992 | 36.96 | 12.47 | 0.80 |
| 3| 6019 | 41.37 | 13.84 | 0.85 |
| 4| 6381 | 56.56 | 19.19 | 1.03 |
| 5| 6426 | 65.19 | 21.99 | 1.12 |
| 6| 6574 | 70.43 | 23.70 | 1.18 |
| 7| 6581 | 77.22 | 25.87 | 1.25 |
| 8| 6673 | 84.44 | 28.32 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7161 | 99.38 | 38.04 | 1.54 |


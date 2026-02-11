--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 04:35:15.073332979 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.75 | 4.04 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 751 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 858 | 53.97 | 15.37 | 0.73 |
| 5 | 281 | 969 | 59.40 | 17.06 | 0.80 |
| 6 | 340 | 1081 | 71.98 | 20.51 | 0.93 |
| 7 | 395 | 1192 | 79.32 | 22.71 | 1.01 |
| 8 | 451 | 1303 | 87.49 | 25.02 | 1.09 |
| 9 | 504 | 1414 | 95.51 | 27.28 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1752 | 23.30 | 7.41 | 0.47 |
| 2| 1983 | 26.50 | 8.99 | 0.52 |
| 3| 2112 | 28.10 | 10.10 | 0.54 |
| 5| 2440 | 32.19 | 12.57 | 0.61 |
| 10| 3212 | 41.70 | 18.56 | 0.76 |
| 40| 7701 | 99.64 | 54.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.80 | 7.36 | 0.41 |
| 2| 797 | 25.20 | 8.71 | 0.45 |
| 3| 874 | 25.05 | 9.30 | 0.46 |
| 5| 1134 | 28.11 | 11.50 | 0.51 |
| 10| 2018 | 41.18 | 18.51 | 0.71 |
| 42| 6655 | 98.08 | 55.64 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.47 | 8.46 | 0.46 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 868 | 32.09 | 11.03 | 0.53 |
| 5| 1237 | 36.99 | 13.77 | 0.60 |
| 10| 2024 | 47.63 | 20.09 | 0.77 |
| 35| 5799 | 94.94 | 50.05 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 895 | 37.13 | 12.38 | 0.58 |
| 5| 1153 | 41.26 | 14.85 | 0.64 |
| 10| 2031 | 54.17 | 21.84 | 0.83 |
| 28| 4727 | 95.85 | 45.41 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 26.97 | 9.06 | 0.69 |
| 2| 5889 | 32.41 | 10.83 | 0.75 |
| 3| 6098 | 42.53 | 14.27 | 0.87 |
| 4| 6151 | 50.29 | 16.84 | 0.95 |
| 5| 6412 | 60.78 | 20.51 | 1.07 |
| 6| 6648 | 74.02 | 25.01 | 1.22 |
| 7| 6856 | 84.53 | 28.58 | 1.34 |
| 8| 6612 | 83.62 | 27.98 | 1.32 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 283 | 6003 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-20 06:03:16.118250395 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | 5788da8969b01bb1d9fd7b78b0dcd988ef2b1d4519e0deae656cef53 | 12374 | 
| μHead | d81fa4e721cac05546c901514e27fad626a1f6a8e11b4d6113d85dee* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 10.74 | 3.42 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 15.14 | 4.81 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 18.29 | 5.75 | 0.36 |
| 2 | 114 | 640 | 24.18 | 7.58 | 0.43 |
| 3 | 171 | 747 | 31.58 | 9.81 | 0.51 |
| 4 | 226 | 858 | 38.68 | 11.97 | 0.59 |
| 5 | 284 | 974 | 45.22 | 13.96 | 0.66 |
| 6 | 339 | 1081 | 51.59 | 15.84 | 0.73 |
| 7 | 395 | 1192 | 62.61 | 19.07 | 0.85 |
| 8 | 449 | 1303 | 64.01 | 19.86 | 0.87 |
| 9 | 506 | 1414 | 70.23 | 21.67 | 0.94 |
| 10 | 560 | 1525 | 79.48 | 24.36 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 17.89 | 6.25 | 0.42 |
| 2| 1924 | 19.03 | 7.25 | 0.44 |
| 3| 2070 | 20.02 | 8.22 | 0.46 |
| 5| 2358 | 23.07 | 10.46 | 0.52 |
| 10| 3325 | 32.57 | 16.64 | 0.68 |
| 50| 9325 | 90.17 | 60.38 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 16.65 | 5.99 | 0.36 |
| 2| 808 | 18.67 | 7.25 | 0.39 |
| 3| 959 | 19.77 | 8.25 | 0.41 |
| 5| 1317 | 23.75 | 10.76 | 0.48 |
| 10| 2065 | 30.71 | 16.18 | 0.61 |
| 50| 7697 | 81.37 | 57.87 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 20.72 | 6.94 | 0.40 |
| 2| 789 | 23.31 | 8.36 | 0.43 |
| 3| 928 | 24.64 | 9.42 | 0.46 |
| 5| 1330 | 27.08 | 11.52 | 0.51 |
| 10| 1932 | 33.00 | 16.59 | 0.62 |
| 49| 7927 | 94.10 | 60.84 | 1.70 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 25.37 | 8.26 | 0.44 |
| 2| 854 | 27.41 | 9.55 | 0.48 |
| 3| 981 | 29.01 | 10.68 | 0.50 |
| 5| 1213 | 31.45 | 12.71 | 0.55 |
| 10| 1956 | 40.33 | 18.68 | 0.70 |
| 42| 6851 | 98.79 | 57.26 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 23.74 | 8.34 | 0.66 |
| 2| 5845 | 27.58 | 9.60 | 0.70 |
| 3| 6165 | 40.82 | 14.53 | 0.86 |
| 4| 6142 | 40.98 | 14.39 | 0.86 |
| 5| 6458 | 56.11 | 19.94 | 1.03 |
| 6| 6611 | 63.75 | 22.66 | 1.12 |
| 7| 6675 | 69.84 | 24.68 | 1.19 |
| 8| 6816 | 78.15 | 27.65 | 1.28 |
| 9| 7155 | 90.50 | 32.19 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.24 | 5.97 | 0.59 |
| 10 | 1 | 57 | 5869 | 18.63 | 6.58 | 0.61 |
| 10 | 10 | 567 | 6171 | 34.88 | 13.36 | 0.80 |
| 10 | 20 | 1138 | 6512 | 53.92 | 21.22 | 1.03 |
| 10 | 30 | 1707 | 6853 | 71.74 | 28.65 | 1.24 |
| 10 | 44 | 2503 | 7328 | 97.45 | 39.32 | 1.54 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-10 13:46:27.644763692 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.71 | 5.86 | 0.37 |
| 2 | 113 | 640 | 24.24 | 7.60 | 0.43 |
| 3 | 169 | 747 | 30.80 | 9.60 | 0.50 |
| 4 | 227 | 858 | 37.68 | 11.66 | 0.58 |
| 5 | 284 | 969 | 43.65 | 13.56 | 0.64 |
| 6 | 339 | 1081 | 49.59 | 15.38 | 0.71 |
| 7 | 395 | 1192 | 55.74 | 17.33 | 0.78 |
| 8 | 451 | 1303 | 66.23 | 20.34 | 0.89 |
| 9 | 504 | 1414 | 74.06 | 22.67 | 0.97 |
| 10 | 560 | 1525 | 91.41 | 27.49 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 17.89 | 6.25 | 0.42 |
| 2| 1984 | 19.74 | 7.47 | 0.45 |
| 3| 2068 | 20.33 | 8.30 | 0.47 |
| 5| 2386 | 23.30 | 10.52 | 0.52 |
| 10| 3133 | 29.25 | 15.65 | 0.64 |
| 50| 9502 | 90.35 | 60.50 | 1.73 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 16.64 | 5.98 | 0.36 |
| 2| 770 | 17.53 | 6.88 | 0.38 |
| 3| 992 | 19.89 | 8.28 | 0.41 |
| 5| 1297 | 22.84 | 10.49 | 0.47 |
| 10| 2030 | 29.62 | 15.84 | 0.59 |
| 50| 7932 | 84.13 | 58.69 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 21.91 | 7.28 | 0.41 |
| 2| 827 | 22.02 | 8.00 | 0.42 |
| 3| 931 | 24.61 | 9.41 | 0.46 |
| 5| 1164 | 25.33 | 10.96 | 0.49 |
| 10| 1967 | 35.47 | 17.31 | 0.65 |
| 50| 8172 | 97.11 | 62.43 | 1.74 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 25.34 | 8.25 | 0.44 |
| 2| 813 | 26.87 | 9.37 | 0.47 |
| 3| 964 | 28.47 | 10.50 | 0.50 |
| 5| 1331 | 32.53 | 13.07 | 0.57 |
| 10| 1967 | 40.25 | 18.66 | 0.70 |
| 43| 7012 | 99.79 | 58.21 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 23.77 | 8.34 | 0.66 |
| 2| 5929 | 31.33 | 11.05 | 0.74 |
| 3| 6050 | 36.08 | 12.67 | 0.80 |
| 4| 6189 | 45.62 | 16.07 | 0.91 |
| 5| 6425 | 55.01 | 19.55 | 1.02 |
| 6| 6496 | 60.36 | 21.33 | 1.08 |
| 7| 6662 | 69.82 | 24.68 | 1.19 |
| 8| 6956 | 82.75 | 29.24 | 1.34 |
| 9| 6923 | 84.63 | 29.97 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.59 | 5.75 | 0.58 |
| 10 | 1 | 56 | 5867 | 17.81 | 6.29 | 0.60 |
| 10 | 10 | 567 | 6171 | 34.05 | 13.07 | 0.79 |
| 10 | 20 | 1139 | 6513 | 52.27 | 20.64 | 1.01 |
| 10 | 40 | 2276 | 7192 | 89.57 | 36.08 | 1.45 |
| 10 | 45 | 2561 | 7362 | 98.69 | 39.87 | 1.56 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-30 11:19:02.254461117 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 24.69 | 7.71 | 0.43 |
| 3 | 170 | 747 | 30.69 | 9.55 | 0.50 |
| 4 | 227 | 862 | 39.24 | 12.05 | 0.59 |
| 5 | 283 | 969 | 44.22 | 13.65 | 0.65 |
| 6 | 339 | 1081 | 49.94 | 15.51 | 0.71 |
| 7 | 394 | 1192 | 55.06 | 17.27 | 0.77 |
| 8 | 449 | 1303 | 68.73 | 21.07 | 0.91 |
| 9 | 504 | 1414 | 74.02 | 22.75 | 0.97 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 18.05 | 6.29 | 0.42 |
| 2| 1945 | 19.14 | 7.28 | 0.44 |
| 3| 2011 | 19.59 | 8.08 | 0.46 |
| 5| 2387 | 23.15 | 10.48 | 0.52 |
| 10| 3121 | 29.97 | 15.85 | 0.64 |
| 50| 9449 | 90.72 | 60.59 | 1.74 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 16.79 | 6.02 | 0.36 |
| 2| 800 | 18.56 | 7.22 | 0.39 |
| 3| 958 | 20.63 | 8.50 | 0.42 |
| 5| 1208 | 22.06 | 10.27 | 0.46 |
| 10| 1973 | 28.65 | 15.55 | 0.58 |
| 50| 8253 | 89.67 | 60.34 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 21.93 | 7.29 | 0.41 |
| 2| 883 | 22.53 | 8.17 | 0.43 |
| 3| 953 | 25.23 | 9.61 | 0.47 |
| 5| 1213 | 25.82 | 11.12 | 0.49 |
| 10| 2066 | 33.95 | 16.91 | 0.64 |
| 49| 7845 | 98.57 | 62.03 | 1.74 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 25.37 | 8.26 | 0.44 |
| 2| 799 | 26.87 | 9.37 | 0.47 |
| 3| 988 | 28.91 | 10.65 | 0.50 |
| 5| 1310 | 32.61 | 13.09 | 0.57 |
| 10| 2112 | 41.73 | 19.15 | 0.72 |
| 41| 6992 | 98.78 | 56.65 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5797 | 23.81 | 8.35 | 0.66 |
| 2| 5893 | 30.44 | 10.69 | 0.73 |
| 3| 6143 | 39.68 | 14.05 | 0.84 |
| 4| 6255 | 47.29 | 16.76 | 0.93 |
| 5| 6554 | 57.18 | 20.31 | 1.05 |
| 6| 6498 | 61.07 | 21.67 | 1.09 |
| 7| 6533 | 66.02 | 23.34 | 1.14 |
| 8| 6739 | 76.85 | 27.19 | 1.26 |
| 9| 6779 | 78.58 | 27.71 | 1.28 |
| 10| 7068 | 99.99 | 34.93 | 1.52 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.41 | 6.04 | 0.59 |
| 10 | 1 | 57 | 5869 | 19.22 | 6.79 | 0.61 |
| 10 | 5 | 285 | 6005 | 26.03 | 9.66 | 0.69 |
| 10 | 10 | 569 | 6174 | 35.29 | 13.51 | 0.80 |
| 10 | 20 | 1137 | 6511 | 52.68 | 20.79 | 1.01 |
| 10 | 30 | 1708 | 6854 | 71.74 | 28.65 | 1.24 |
| 10 | 40 | 2275 | 7192 | 89.57 | 36.08 | 1.45 |
| 10 | 45 | 2558 | 7360 | 98.27 | 39.73 | 1.55 |


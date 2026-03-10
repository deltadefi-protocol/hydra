--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-10 14:38:53.807170957 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 15.07 | 4.78 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7644 | 29.18 | 9.20 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 25.17 | 7.82 | 0.44 |
| 3 | 170 | 747 | 30.69 | 9.55 | 0.50 |
| 4 | 227 | 858 | 36.76 | 11.44 | 0.57 |
| 5 | 283 | 969 | 45.06 | 13.94 | 0.66 |
| 6 | 338 | 1081 | 53.82 | 16.53 | 0.75 |
| 7 | 393 | 1196 | 55.82 | 17.30 | 0.78 |
| 8 | 448 | 1307 | 62.00 | 19.21 | 0.85 |
| 9 | 504 | 1414 | 73.33 | 22.55 | 0.97 |
| 10 | 560 | 1525 | 80.65 | 24.76 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 17.34 | 6.07 | 0.41 |
| 2| 1882 | 18.43 | 7.06 | 0.43 |
| 3| 2085 | 20.12 | 8.25 | 0.46 |
| 5| 2276 | 21.51 | 10.00 | 0.50 |
| 10| 3221 | 30.75 | 16.10 | 0.66 |
| 50| 9034 | 85.70 | 59.05 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 16.77 | 6.02 | 0.36 |
| 2| 700 | 16.79 | 6.67 | 0.36 |
| 3| 922 | 19.71 | 8.24 | 0.41 |
| 5| 1159 | 21.20 | 10.01 | 0.44 |
| 10| 2093 | 30.07 | 15.99 | 0.60 |
| 50| 8266 | 88.67 | 60.05 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 21.91 | 7.28 | 0.41 |
| 2| 837 | 22.04 | 8.00 | 0.42 |
| 3| 1004 | 23.58 | 9.13 | 0.45 |
| 5| 1174 | 27.29 | 11.54 | 0.51 |
| 10| 2070 | 36.98 | 17.81 | 0.67 |
| 50| 7957 | 99.96 | 63.11 | 1.76 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 25.34 | 8.25 | 0.44 |
| 2| 764 | 26.33 | 9.19 | 0.46 |
| 3| 1009 | 29.03 | 10.69 | 0.51 |
| 5| 1223 | 31.50 | 12.73 | 0.55 |
| 10| 2067 | 41.62 | 19.10 | 0.72 |
| 41| 6561 | 95.14 | 55.43 | 1.61 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 23.77 | 8.35 | 0.66 |
| 2| 5913 | 31.22 | 11.01 | 0.74 |
| 3| 6117 | 39.76 | 14.06 | 0.84 |
| 4| 6326 | 48.43 | 17.23 | 0.94 |
| 5| 6498 | 57.98 | 20.59 | 1.05 |
| 6| 6700 | 67.64 | 24.12 | 1.17 |
| 7| 6617 | 68.64 | 24.34 | 1.17 |
| 8| 6907 | 77.87 | 27.57 | 1.28 |
| 9| 7058 | 87.74 | 31.11 | 1.39 |
| 11| 7110 | 96.29 | 33.88 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.83 | 5.83 | 0.59 |
| 10 | 1 | 57 | 5868 | 18.39 | 6.50 | 0.60 |
| 10 | 5 | 285 | 6004 | 25.61 | 9.51 | 0.69 |
| 10 | 20 | 1139 | 6513 | 54.09 | 21.28 | 1.03 |
| 10 | 30 | 1707 | 6854 | 70.91 | 28.36 | 1.23 |
| 10 | 45 | 2563 | 7365 | 99.52 | 40.16 | 1.57 |


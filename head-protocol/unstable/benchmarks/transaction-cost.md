--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-30 07:32:59.213085013 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.58 | 5.86 | 0.63 |
| 10| 7651 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 113 | 640 | 24.62 | 7.68 | 0.43 |
| 3 | 171 | 747 | 30.91 | 9.64 | 0.50 |
| 4 | 226 | 858 | 36.74 | 11.46 | 0.57 |
| 5 | 283 | 969 | 46.79 | 14.35 | 0.67 |
| 6 | 338 | 1081 | 53.93 | 16.48 | 0.75 |
| 7 | 392 | 1192 | 64.45 | 19.55 | 0.86 |
| 8 | 449 | 1307 | 72.47 | 21.84 | 0.95 |
| 9 | 506 | 1414 | 73.78 | 22.60 | 0.97 |
| 10 | 560 | 1525 | 89.92 | 27.13 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 18.10 | 6.30 | 0.42 |
| 2| 1953 | 19.24 | 7.31 | 0.44 |
| 3| 2161 | 21.76 | 8.73 | 0.48 |
| 5| 2400 | 23.17 | 10.49 | 0.52 |
| 10| 3112 | 30.09 | 15.90 | 0.64 |
| 50| 9155 | 86.23 | 59.24 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 16.79 | 6.02 | 0.36 |
| 2| 750 | 17.53 | 6.87 | 0.37 |
| 3| 878 | 18.81 | 7.98 | 0.40 |
| 5| 1148 | 20.80 | 9.86 | 0.44 |
| 10| 2008 | 29.34 | 15.77 | 0.59 |
| 50| 8086 | 88.19 | 59.88 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 20.72 | 6.94 | 0.40 |
| 2| 849 | 23.82 | 8.53 | 0.44 |
| 3| 899 | 22.75 | 8.86 | 0.44 |
| 5| 1224 | 25.87 | 11.14 | 0.49 |
| 10| 1966 | 35.39 | 17.29 | 0.65 |
| 49| 7762 | 98.34 | 61.95 | 1.73 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 25.37 | 8.26 | 0.45 |
| 2| 765 | 26.33 | 9.19 | 0.46 |
| 3| 980 | 29.03 | 10.69 | 0.51 |
| 5| 1242 | 32.09 | 12.92 | 0.56 |
| 10| 2001 | 40.13 | 18.62 | 0.70 |
| 43| 6719 | 98.04 | 57.58 | 1.65 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 23.77 | 8.35 | 0.66 |
| 2| 5945 | 31.18 | 10.98 | 0.74 |
| 3| 6142 | 39.93 | 14.16 | 0.85 |
| 4| 6166 | 43.74 | 15.43 | 0.89 |
| 5| 6409 | 55.82 | 19.76 | 1.03 |
| 6| 6723 | 64.95 | 23.09 | 1.14 |
| 7| 6583 | 67.17 | 23.73 | 1.15 |
| 8| 6773 | 73.07 | 25.83 | 1.22 |
| 9| 6944 | 84.62 | 29.80 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.41 | 5.68 | 0.58 |
| 10 | 5 | 285 | 6004 | 26.68 | 9.89 | 0.70 |
| 10 | 10 | 570 | 6174 | 34.05 | 13.07 | 0.79 |
| 10 | 40 | 2274 | 7191 | 88.74 | 35.79 | 1.44 |
| 10 | 45 | 2561 | 7363 | 98.69 | 39.87 | 1.56 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-12 16:03:24.455174922 UTC |
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
| 1| 5837 | 10.95 | 3.49 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10045 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 526 | 18.67 | 5.84 | 0.37 |
| 2 | 114 | 640 | 24.08 | 7.54 | 0.43 |
| 3 | 171 | 747 | 30.16 | 9.44 | 0.49 |
| 4 | 226 | 858 | 37.79 | 11.68 | 0.58 |
| 5 | 281 | 969 | 43.48 | 13.52 | 0.64 |
| 6 | 339 | 1081 | 54.59 | 16.75 | 0.76 |
| 7 | 395 | 1192 | 62.84 | 19.08 | 0.85 |
| 8 | 449 | 1303 | 66.53 | 20.41 | 0.89 |
| 9 | 504 | 1414 | 68.07 | 21.19 | 0.92 |
| 10 | 560 | 1529 | 89.86 | 27.15 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 17.13 | 6.02 | 0.41 |
| 2| 1882 | 18.22 | 7.01 | 0.43 |
| 3| 2013 | 19.57 | 8.07 | 0.46 |
| 5| 2521 | 25.25 | 11.13 | 0.55 |
| 10| 3245 | 31.09 | 16.21 | 0.66 |
| 50| 9211 | 87.54 | 59.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 16.79 | 6.02 | 0.36 |
| 2| 741 | 17.50 | 6.88 | 0.37 |
| 3| 924 | 18.53 | 7.85 | 0.40 |
| 5| 1157 | 20.78 | 9.85 | 0.44 |
| 10| 1900 | 27.55 | 15.24 | 0.57 |
| 50| 8358 | 91.57 | 60.94 | 1.70 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 21.93 | 7.28 | 0.41 |
| 2| 798 | 23.31 | 8.36 | 0.43 |
| 3| 868 | 24.13 | 9.25 | 0.45 |
| 5| 1242 | 28.01 | 11.76 | 0.52 |
| 10| 2037 | 34.06 | 16.96 | 0.64 |
| 48| 7696 | 91.06 | 59.22 | 1.65 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 25.37 | 8.26 | 0.45 |
| 2| 807 | 26.92 | 9.38 | 0.47 |
| 3| 1000 | 29.03 | 10.69 | 0.51 |
| 5| 1348 | 33.18 | 13.27 | 0.57 |
| 10| 1854 | 39.23 | 18.32 | 0.68 |
| 42| 6791 | 99.13 | 57.35 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 23.67 | 8.32 | 0.66 |
| 2| 5894 | 30.36 | 10.66 | 0.73 |
| 3| 6086 | 38.87 | 13.73 | 0.83 |
| 4| 6283 | 47.53 | 16.81 | 0.93 |
| 5| 6337 | 55.00 | 19.42 | 1.01 |
| 6| 6525 | 64.14 | 22.73 | 1.12 |
| 7| 6808 | 72.71 | 25.84 | 1.22 |
| 8| 6961 | 83.12 | 29.57 | 1.34 |
| 9| 7110 | 96.68 | 33.95 | 1.49 |
| 10| 7115 | 98.85 | 34.67 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 25.44 | 9.45 | 0.69 |
| 10 | 10 | 570 | 6175 | 35.88 | 13.71 | 0.81 |
| 10 | 20 | 1136 | 6511 | 53.92 | 21.22 | 1.03 |
| 10 | 30 | 1709 | 6855 | 72.15 | 28.80 | 1.24 |
| 10 | 40 | 2278 | 7194 | 90.15 | 36.29 | 1.46 |
| 10 | 45 | 2562 | 7364 | 99.10 | 40.02 | 1.56 |


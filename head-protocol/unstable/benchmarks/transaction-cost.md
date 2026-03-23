--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 10:26:48.674124481 UTC |
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
| 1| 5840 | 10.95 | 3.49 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 113 | 636 | 25.20 | 7.82 | 0.44 |
| 3 | 171 | 747 | 30.75 | 9.60 | 0.50 |
| 4 | 225 | 858 | 38.55 | 11.92 | 0.59 |
| 5 | 283 | 969 | 43.12 | 13.49 | 0.64 |
| 6 | 339 | 1081 | 50.90 | 15.71 | 0.72 |
| 7 | 395 | 1192 | 64.21 | 19.43 | 0.86 |
| 8 | 450 | 1303 | 63.32 | 19.59 | 0.86 |
| 9 | 505 | 1414 | 73.66 | 22.71 | 0.97 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 17.84 | 6.24 | 0.42 |
| 2| 1883 | 18.43 | 7.06 | 0.43 |
| 3| 2098 | 21.09 | 8.53 | 0.47 |
| 5| 2434 | 23.94 | 10.72 | 0.53 |
| 10| 3051 | 28.98 | 15.55 | 0.63 |
| 50| 9076 | 85.27 | 58.94 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 16.79 | 6.02 | 0.36 |
| 2| 808 | 18.50 | 7.20 | 0.39 |
| 3| 952 | 19.74 | 8.25 | 0.41 |
| 5| 1263 | 21.55 | 10.08 | 0.45 |
| 10| 1961 | 28.67 | 15.55 | 0.58 |
| 50| 7746 | 84.37 | 58.72 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 21.91 | 7.28 | 0.41 |
| 2| 736 | 22.70 | 8.16 | 0.42 |
| 3| 927 | 24.67 | 9.43 | 0.46 |
| 5| 1347 | 27.62 | 11.70 | 0.52 |
| 10| 1961 | 33.38 | 16.73 | 0.63 |
| 49| 7836 | 99.03 | 62.18 | 1.74 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 25.34 | 8.25 | 0.44 |
| 2| 862 | 27.44 | 9.55 | 0.48 |
| 3| 959 | 28.42 | 10.49 | 0.50 |
| 5| 1208 | 31.50 | 12.73 | 0.55 |
| 10| 2094 | 41.33 | 19.01 | 0.71 |
| 42| 6903 | 98.81 | 57.24 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 20.21 | 6.95 | 0.61 |
| 2| 5941 | 31.28 | 11.02 | 0.74 |
| 3| 5996 | 36.19 | 12.72 | 0.80 |
| 4| 6333 | 47.78 | 16.93 | 0.94 |
| 5| 6403 | 54.03 | 19.14 | 1.01 |
| 6| 6576 | 60.90 | 21.58 | 1.09 |
| 7| 6630 | 68.09 | 24.04 | 1.17 |
| 8| 6909 | 82.26 | 28.97 | 1.33 |
| 9| 7086 | 92.95 | 32.80 | 1.45 |
| 10| 7105 | 99.71 | 34.81 | 1.52 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.66 | 6.12 | 0.59 |
| 10 | 1 | 57 | 5869 | 19.87 | 7.02 | 0.62 |
| 10 | 5 | 284 | 6003 | 25.85 | 9.60 | 0.69 |
| 10 | 10 | 570 | 6175 | 35.05 | 13.42 | 0.80 |
| 10 | 20 | 1143 | 6517 | 53.92 | 21.22 | 1.03 |
| 10 | 30 | 1707 | 6853 | 70.91 | 28.36 | 1.23 |
| 10 | 40 | 2273 | 7189 | 89.98 | 36.23 | 1.45 |
| 10 | 44 | 2504 | 7329 | 96.86 | 39.11 | 1.54 |


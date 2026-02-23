--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-23 15:01:12.57819676 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 25.24 | 7.85 | 0.44 |
| 3 | 170 | 747 | 32.38 | 10.03 | 0.52 |
| 4 | 227 | 858 | 37.34 | 11.57 | 0.57 |
| 5 | 281 | 969 | 43.68 | 13.57 | 0.64 |
| 6 | 338 | 1081 | 53.85 | 16.51 | 0.75 |
| 7 | 396 | 1192 | 63.70 | 19.31 | 0.86 |
| 8 | 451 | 1303 | 70.63 | 21.50 | 0.93 |
| 9 | 505 | 1414 | 71.24 | 21.93 | 0.95 |
| 10 | 560 | 1525 | 86.02 | 26.00 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 18.05 | 6.29 | 0.42 |
| 2| 1928 | 19.19 | 7.29 | 0.44 |
| 3| 2106 | 20.93 | 8.49 | 0.47 |
| 5| 2443 | 24.51 | 10.90 | 0.53 |
| 10| 3032 | 28.59 | 15.45 | 0.63 |
| 50| 9141 | 87.08 | 59.48 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 16.65 | 5.98 | 0.35 |
| 2| 817 | 18.67 | 7.26 | 0.39 |
| 3| 959 | 19.76 | 8.24 | 0.41 |
| 5| 1213 | 21.60 | 10.10 | 0.45 |
| 10| 1959 | 28.47 | 15.49 | 0.58 |
| 50| 7790 | 81.18 | 57.81 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 20.74 | 6.95 | 0.40 |
| 2| 797 | 23.31 | 8.36 | 0.43 |
| 3| 1007 | 23.88 | 9.23 | 0.45 |
| 5| 1233 | 28.01 | 11.76 | 0.52 |
| 10| 2077 | 36.94 | 17.80 | 0.67 |
| 49| 8195 | 96.54 | 61.59 | 1.73 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 25.34 | 8.25 | 0.45 |
| 2| 854 | 27.44 | 9.55 | 0.48 |
| 3| 938 | 28.42 | 10.49 | 0.50 |
| 5| 1335 | 32.56 | 13.07 | 0.57 |
| 10| 2032 | 40.95 | 18.88 | 0.71 |
| 42| 6739 | 96.94 | 56.65 | 1.64 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 20.21 | 6.95 | 0.61 |
| 2| 5961 | 31.35 | 11.04 | 0.75 |
| 3| 5946 | 35.39 | 12.39 | 0.79 |
| 4| 6335 | 48.52 | 17.23 | 0.95 |
| 5| 6537 | 57.26 | 20.40 | 1.05 |
| 6| 6632 | 65.19 | 23.13 | 1.14 |
| 7| 6534 | 67.14 | 23.65 | 1.15 |
| 8| 6760 | 80.37 | 28.41 | 1.30 |
| 9| 7105 | 98.16 | 34.01 | 1.50 |
| 10| 7170 | 95.86 | 33.77 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.66 | 6.12 | 0.59 |
| 10 | 1 | 57 | 5869 | 19.05 | 6.73 | 0.61 |
| 10 | 5 | 285 | 6005 | 26.68 | 9.89 | 0.70 |
| 10 | 10 | 569 | 6174 | 35.29 | 13.51 | 0.80 |
| 10 | 30 | 1705 | 6852 | 72.15 | 28.80 | 1.24 |
| 10 | 45 | 2561 | 7362 | 98.69 | 39.87 | 1.56 |


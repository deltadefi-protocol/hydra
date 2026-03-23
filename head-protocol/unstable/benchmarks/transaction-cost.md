--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 16:59:49.724816272 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 18.25 | 5.73 | 0.36 |
| 2 | 113 | 640 | 24.09 | 7.54 | 0.43 |
| 3 | 169 | 747 | 32.02 | 9.89 | 0.51 |
| 4 | 225 | 858 | 38.79 | 11.98 | 0.59 |
| 5 | 284 | 969 | 46.91 | 14.36 | 0.68 |
| 6 | 340 | 1081 | 53.05 | 16.22 | 0.74 |
| 7 | 395 | 1192 | 55.56 | 17.21 | 0.78 |
| 8 | 451 | 1303 | 70.11 | 21.41 | 0.93 |
| 9 | 506 | 1414 | 79.42 | 23.96 | 1.03 |
| 10 | 560 | 1525 | 81.26 | 24.83 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 17.89 | 6.25 | 0.42 |
| 2| 1974 | 19.90 | 7.51 | 0.45 |
| 3| 2188 | 21.52 | 8.68 | 0.48 |
| 5| 2417 | 23.25 | 10.53 | 0.52 |
| 10| 3284 | 31.85 | 16.42 | 0.67 |
| 50| 9404 | 90.74 | 60.56 | 1.73 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 16.79 | 6.02 | 0.36 |
| 2| 766 | 17.73 | 6.97 | 0.38 |
| 3| 1001 | 20.76 | 8.53 | 0.42 |
| 5| 1417 | 24.60 | 11.02 | 0.49 |
| 10| 1992 | 29.19 | 15.74 | 0.59 |
| 50| 8137 | 86.79 | 59.51 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 21.91 | 7.28 | 0.41 |
| 2| 819 | 21.99 | 7.99 | 0.42 |
| 3| 912 | 24.66 | 9.42 | 0.46 |
| 5| 1363 | 27.52 | 11.67 | 0.52 |
| 10| 1998 | 35.98 | 17.48 | 0.65 |
| 50| 8121 | 97.29 | 62.42 | 1.74 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 25.34 | 8.25 | 0.44 |
| 2| 854 | 27.44 | 9.55 | 0.48 |
| 3| 949 | 28.47 | 10.50 | 0.50 |
| 5| 1331 | 32.66 | 13.10 | 0.57 |
| 10| 2170 | 42.44 | 19.37 | 0.73 |
| 43| 6934 | 99.67 | 58.13 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 23.78 | 8.36 | 0.66 |
| 2| 5961 | 31.25 | 11.00 | 0.74 |
| 3| 5970 | 35.03 | 12.26 | 0.78 |
| 4| 6309 | 47.77 | 16.95 | 0.94 |
| 5| 6411 | 55.11 | 19.58 | 1.02 |
| 6| 6416 | 58.60 | 20.68 | 1.06 |
| 7| 6967 | 74.13 | 26.44 | 1.25 |
| 8| 6638 | 73.04 | 25.90 | 1.22 |
| 9| 7177 | 91.08 | 32.35 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.41 | 5.68 | 0.58 |
| 10 | 1 | 56 | 5867 | 19.05 | 6.73 | 0.61 |
| 10 | 5 | 284 | 6004 | 24.61 | 9.16 | 0.68 |
| 10 | 10 | 569 | 6174 | 34.88 | 13.36 | 0.80 |
| 10 | 20 | 1140 | 6515 | 53.51 | 21.08 | 1.02 |
| 10 | 30 | 1709 | 6855 | 71.33 | 28.51 | 1.23 |
| 10 | 40 | 2281 | 7198 | 90.81 | 36.52 | 1.46 |
| 10 | 43 | 2447 | 7294 | 95.04 | 38.36 | 1.52 |


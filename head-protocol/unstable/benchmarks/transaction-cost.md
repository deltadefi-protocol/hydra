--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-23 15:51:18.7174258 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6641 | 18.58 | 5.86 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 99.11 | 30.98 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.29 | 5.75 | 0.36 |
| 2 | 114 | 636 | 24.11 | 7.55 | 0.43 |
| 3 | 171 | 747 | 30.73 | 9.56 | 0.50 |
| 4 | 227 | 858 | 35.61 | 11.13 | 0.56 |
| 5 | 284 | 969 | 45.06 | 13.86 | 0.66 |
| 6 | 339 | 1085 | 50.00 | 15.49 | 0.71 |
| 7 | 396 | 1192 | 61.21 | 18.72 | 0.83 |
| 8 | 450 | 1303 | 71.28 | 21.66 | 0.94 |
| 9 | 505 | 1414 | 84.25 | 25.32 | 1.08 |
| 10 | 561 | 1525 | 86.59 | 26.17 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 17.34 | 6.07 | 0.41 |
| 2| 1954 | 18.98 | 7.24 | 0.44 |
| 3| 2055 | 20.07 | 8.23 | 0.46 |
| 5| 2342 | 22.35 | 10.25 | 0.51 |
| 10| 3146 | 30.14 | 15.91 | 0.65 |
| 50| 9263 | 88.65 | 59.97 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 16.64 | 5.98 | 0.36 |
| 2| 784 | 18.64 | 7.24 | 0.39 |
| 3| 917 | 19.63 | 8.21 | 0.41 |
| 5| 1203 | 21.46 | 10.07 | 0.45 |
| 10| 2112 | 30.71 | 16.20 | 0.61 |
| 50| 8293 | 91.23 | 60.81 | 1.69 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 21.93 | 7.29 | 0.41 |
| 2| 798 | 23.31 | 8.36 | 0.43 |
| 3| 976 | 25.18 | 9.59 | 0.47 |
| 5| 1219 | 27.96 | 11.75 | 0.51 |
| 10| 2164 | 37.70 | 18.03 | 0.68 |
| 50| 8377 | 98.99 | 63.03 | 1.77 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 24.80 | 8.08 | 0.44 |
| 2| 800 | 26.90 | 9.38 | 0.47 |
| 3| 938 | 28.47 | 10.50 | 0.50 |
| 5| 1315 | 32.66 | 13.10 | 0.57 |
| 10| 1954 | 40.20 | 18.64 | 0.70 |
| 41| 6751 | 97.38 | 56.14 | 1.64 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 23.71 | 8.33 | 0.66 |
| 2| 5916 | 30.29 | 10.63 | 0.73 |
| 3| 5968 | 35.04 | 12.25 | 0.78 |
| 4| 6297 | 47.16 | 16.73 | 0.93 |
| 5| 6402 | 52.69 | 18.70 | 0.99 |
| 6| 6456 | 59.46 | 20.97 | 1.07 |
| 7| 6700 | 66.10 | 23.39 | 1.15 |
| 8| 6920 | 79.72 | 28.27 | 1.30 |
| 9| 7014 | 87.67 | 30.97 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.66 | 6.12 | 0.59 |
| 10 | 1 | 57 | 5868 | 19.46 | 6.87 | 0.62 |
| 10 | 5 | 285 | 6004 | 25.61 | 9.51 | 0.69 |
| 10 | 44 | 2504 | 7328 | 97.69 | 39.40 | 1.55 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 17:22:33.870982601 UTC |
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
| 1| 5837 | 10.93 | 3.49 | 0.52 |
| 2| 6038 | 13.18 | 4.20 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 24.10 | 7.55 | 0.43 |
| 3 | 170 | 747 | 29.89 | 9.35 | 0.49 |
| 4 | 225 | 858 | 38.37 | 11.85 | 0.58 |
| 5 | 284 | 969 | 45.01 | 13.90 | 0.66 |
| 6 | 339 | 1081 | 49.70 | 15.44 | 0.71 |
| 7 | 393 | 1192 | 61.58 | 18.75 | 0.84 |
| 8 | 450 | 1303 | 70.74 | 21.70 | 0.94 |
| 9 | 505 | 1414 | 82.89 | 25.09 | 1.06 |
| 10 | 560 | 1525 | 96.84 | 29.21 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 18.05 | 6.29 | 0.42 |
| 2| 1999 | 19.77 | 7.48 | 0.45 |
| 3| 2109 | 21.09 | 8.53 | 0.47 |
| 5| 2429 | 23.91 | 10.71 | 0.53 |
| 10| 3153 | 30.26 | 15.94 | 0.65 |
| 50| 9508 | 91.61 | 60.83 | 1.75 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 16.77 | 6.02 | 0.36 |
| 2| 699 | 16.79 | 6.66 | 0.36 |
| 3| 895 | 18.53 | 7.85 | 0.40 |
| 5| 1359 | 24.27 | 10.93 | 0.48 |
| 10| 2004 | 29.88 | 15.95 | 0.59 |
| 50| 8085 | 87.03 | 59.55 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 21.91 | 7.28 | 0.41 |
| 2| 890 | 22.61 | 8.19 | 0.43 |
| 3| 1012 | 23.84 | 9.22 | 0.45 |
| 5| 1164 | 25.38 | 10.97 | 0.49 |
| 10| 2035 | 33.95 | 16.91 | 0.64 |
| 50| 8227 | 98.61 | 62.89 | 1.76 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 25.34 | 8.25 | 0.44 |
| 2| 890 | 27.49 | 9.57 | 0.48 |
| 3| 970 | 28.42 | 10.49 | 0.50 |
| 5| 1392 | 33.12 | 13.26 | 0.57 |
| 10| 2126 | 41.92 | 19.20 | 0.72 |
| 43| 7002 | 99.81 | 58.20 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 23.73 | 8.33 | 0.66 |
| 2| 5982 | 32.12 | 11.36 | 0.75 |
| 3| 5980 | 33.15 | 11.56 | 0.76 |
| 4| 6220 | 47.51 | 16.84 | 0.93 |
| 5| 6425 | 55.38 | 19.65 | 1.02 |
| 6| 6517 | 63.95 | 22.63 | 1.12 |
| 7| 6752 | 73.05 | 25.86 | 1.22 |
| 8| 6749 | 77.21 | 27.36 | 1.27 |
| 9| 7052 | 90.10 | 31.68 | 1.42 |
| 10| 7304 | 98.06 | 34.52 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6004 | 26.20 | 9.72 | 0.70 |
| 10 | 10 | 569 | 6174 | 34.05 | 13.07 | 0.79 |
| 10 | 20 | 1141 | 6515 | 53.09 | 20.93 | 1.02 |
| 10 | 40 | 2275 | 7192 | 89.98 | 36.23 | 1.45 |
| 10 | 44 | 2506 | 7331 | 96.45 | 38.97 | 1.53 |


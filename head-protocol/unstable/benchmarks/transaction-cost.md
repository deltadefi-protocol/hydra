--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-12 13:24:58.468754487 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6643 | 19.00 | 6.01 | 0.64 |
| 10| 7647 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.29 | 5.75 | 0.36 |
| 2 | 114 | 640 | 25.32 | 7.88 | 0.44 |
| 3 | 170 | 747 | 30.71 | 9.56 | 0.50 |
| 4 | 228 | 858 | 39.38 | 12.13 | 0.59 |
| 5 | 283 | 974 | 42.63 | 13.30 | 0.63 |
| 6 | 336 | 1081 | 52.10 | 16.05 | 0.73 |
| 7 | 395 | 1196 | 60.90 | 18.54 | 0.83 |
| 8 | 449 | 1303 | 77.00 | 23.01 | 1.00 |
| 9 | 506 | 1414 | 86.63 | 25.84 | 1.10 |
| 10 | 561 | 1529 | 88.10 | 26.70 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 17.89 | 6.25 | 0.42 |
| 2| 1989 | 19.74 | 7.47 | 0.45 |
| 3| 2182 | 21.71 | 8.72 | 0.48 |
| 5| 2341 | 22.46 | 10.27 | 0.51 |
| 10| 3086 | 29.20 | 15.64 | 0.63 |
| 50| 9015 | 85.49 | 58.99 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 16.65 | 6.00 | 0.35 |
| 2| 759 | 17.92 | 7.03 | 0.38 |
| 3| 933 | 19.83 | 8.28 | 0.41 |
| 5| 1289 | 23.63 | 10.74 | 0.48 |
| 10| 1956 | 28.50 | 15.50 | 0.58 |
| 50| 8060 | 85.72 | 59.17 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 20.74 | 6.95 | 0.40 |
| 2| 795 | 23.31 | 8.36 | 0.43 |
| 3| 899 | 22.78 | 8.87 | 0.44 |
| 5| 1284 | 28.55 | 11.94 | 0.52 |
| 10| 2032 | 36.25 | 17.58 | 0.66 |
| 50| 8264 | 97.03 | 62.42 | 1.75 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 25.37 | 8.26 | 0.44 |
| 2| 807 | 26.90 | 9.38 | 0.47 |
| 3| 1041 | 29.52 | 10.85 | 0.51 |
| 5| 1264 | 31.99 | 12.89 | 0.56 |
| 10| 2118 | 42.06 | 19.25 | 0.72 |
| 42| 6864 | 99.27 | 57.38 | 1.67 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 23.78 | 8.35 | 0.66 |
| 2| 6006 | 32.24 | 11.42 | 0.76 |
| 3| 6041 | 37.79 | 13.31 | 0.82 |
| 4| 6227 | 48.05 | 17.01 | 0.94 |
| 5| 6386 | 54.56 | 19.32 | 1.01 |
| 6| 6539 | 60.81 | 21.58 | 1.08 |
| 7| 6677 | 69.09 | 24.40 | 1.18 |
| 8| 6756 | 74.53 | 26.37 | 1.24 |
| 9| 7081 | 93.28 | 32.66 | 1.45 |
| 12| 7253 | 99.39 | 34.95 | 1.52 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.05 | 6.73 | 0.61 |
| 10 | 5 | 282 | 6001 | 25.85 | 9.60 | 0.69 |
| 10 | 20 | 1138 | 6512 | 52.68 | 20.79 | 1.01 |
| 10 | 30 | 1708 | 6855 | 71.91 | 28.71 | 1.24 |
| 10 | 45 | 2563 | 7364 | 98.69 | 39.87 | 1.56 |


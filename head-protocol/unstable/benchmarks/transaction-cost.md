--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-24 12:06:25.745895128 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 113 | 636 | 24.18 | 7.58 | 0.43 |
| 3 | 169 | 747 | 31.90 | 9.85 | 0.51 |
| 4 | 227 | 862 | 39.38 | 12.11 | 0.59 |
| 5 | 282 | 969 | 43.73 | 13.58 | 0.64 |
| 6 | 339 | 1081 | 49.39 | 15.44 | 0.71 |
| 7 | 394 | 1196 | 60.29 | 18.44 | 0.82 |
| 8 | 452 | 1303 | 72.71 | 21.86 | 0.95 |
| 9 | 506 | 1414 | 76.32 | 23.22 | 1.00 |
| 10 | 560 | 1525 | 95.65 | 28.69 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 17.89 | 6.25 | 0.42 |
| 2| 1985 | 19.70 | 7.46 | 0.45 |
| 3| 2015 | 19.34 | 8.01 | 0.45 |
| 5| 2400 | 23.04 | 10.46 | 0.52 |
| 10| 3155 | 30.05 | 15.89 | 0.65 |
| 50| 9206 | 88.50 | 59.92 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 16.61 | 5.98 | 0.36 |
| 2| 828 | 18.79 | 7.29 | 0.39 |
| 3| 895 | 18.55 | 7.85 | 0.40 |
| 5| 1288 | 23.74 | 10.75 | 0.48 |
| 10| 2085 | 29.80 | 15.90 | 0.60 |
| 50| 7966 | 85.46 | 59.11 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 21.91 | 7.28 | 0.41 |
| 2| 853 | 22.56 | 8.17 | 0.43 |
| 3| 1039 | 23.78 | 9.20 | 0.45 |
| 5| 1264 | 26.46 | 11.33 | 0.50 |
| 10| 1825 | 34.26 | 16.92 | 0.63 |
| 49| 7781 | 92.52 | 60.31 | 1.67 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 25.32 | 8.25 | 0.44 |
| 2| 765 | 26.36 | 9.20 | 0.46 |
| 3| 951 | 28.39 | 10.48 | 0.50 |
| 5| 1392 | 33.20 | 13.28 | 0.58 |
| 10| 1919 | 39.69 | 18.48 | 0.69 |
| 43| 6907 | 99.27 | 58.01 | 1.67 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 20.21 | 6.95 | 0.61 |
| 2| 5968 | 31.34 | 11.05 | 0.75 |
| 3| 5996 | 35.89 | 12.60 | 0.79 |
| 4| 6266 | 47.81 | 16.92 | 0.93 |
| 5| 6470 | 56.34 | 20.02 | 1.03 |
| 6| 6454 | 60.09 | 21.24 | 1.07 |
| 7| 6823 | 74.29 | 26.39 | 1.24 |
| 8| 6857 | 81.77 | 28.89 | 1.32 |
| 9| 7078 | 94.99 | 33.14 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 18.22 | 6.44 | 0.60 |
| 10 | 5 | 285 | 6004 | 25.85 | 9.60 | 0.69 |
| 10 | 10 | 569 | 6173 | 35.29 | 13.51 | 0.80 |
| 10 | 20 | 1138 | 6512 | 52.85 | 20.85 | 1.01 |
| 10 | 30 | 1709 | 6855 | 72.15 | 28.80 | 1.24 |
| 10 | 46 | 2616 | 7395 | 99.68 | 40.34 | 1.57 |


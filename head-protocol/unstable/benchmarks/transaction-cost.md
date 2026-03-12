--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-12 12:51:16.633066168 UTC |
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
| 2| 6037 | 13.18 | 4.20 | 0.55 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 113 | 636 | 24.61 | 7.68 | 0.43 |
| 3 | 171 | 747 | 30.26 | 9.48 | 0.50 |
| 4 | 227 | 858 | 36.83 | 11.47 | 0.57 |
| 5 | 284 | 969 | 47.36 | 14.53 | 0.68 |
| 6 | 339 | 1085 | 48.64 | 15.18 | 0.70 |
| 7 | 396 | 1196 | 55.14 | 17.17 | 0.77 |
| 8 | 450 | 1303 | 69.11 | 21.14 | 0.92 |
| 9 | 505 | 1414 | 72.69 | 22.27 | 0.96 |
| 10 | 560 | 1525 | 92.72 | 27.88 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 18.10 | 6.30 | 0.42 |
| 2| 1927 | 19.19 | 7.29 | 0.44 |
| 3| 2118 | 20.78 | 8.45 | 0.47 |
| 5| 2432 | 24.14 | 10.77 | 0.53 |
| 10| 3268 | 32.68 | 16.68 | 0.68 |
| 50| 9418 | 90.32 | 60.50 | 1.73 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 16.65 | 5.98 | 0.35 |
| 2| 765 | 17.75 | 6.98 | 0.38 |
| 3| 917 | 19.76 | 8.24 | 0.41 |
| 5| 1209 | 21.81 | 10.21 | 0.45 |
| 10| 1959 | 28.22 | 15.45 | 0.58 |
| 50| 8068 | 90.25 | 60.44 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 21.93 | 7.29 | 0.41 |
| 2| 781 | 23.26 | 8.34 | 0.43 |
| 3| 910 | 24.69 | 9.43 | 0.46 |
| 5| 1228 | 25.85 | 11.13 | 0.49 |
| 10| 1913 | 32.76 | 16.53 | 0.62 |
| 49| 7997 | 94.54 | 60.96 | 1.71 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 25.37 | 8.26 | 0.44 |
| 2| 848 | 27.44 | 9.55 | 0.48 |
| 3| 1022 | 28.95 | 10.66 | 0.51 |
| 5| 1340 | 32.92 | 13.18 | 0.57 |
| 10| 2158 | 42.10 | 19.27 | 0.72 |
| 41| 6877 | 98.79 | 56.63 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 23.77 | 8.34 | 0.66 |
| 2| 5879 | 28.50 | 9.97 | 0.71 |
| 3| 6012 | 36.18 | 12.70 | 0.80 |
| 4| 6333 | 48.38 | 17.18 | 0.94 |
| 5| 6382 | 55.03 | 19.47 | 1.02 |
| 6| 6578 | 66.04 | 23.42 | 1.14 |
| 7| 6812 | 70.60 | 25.01 | 1.20 |
| 8| 6906 | 84.06 | 29.50 | 1.35 |
| 9| 7138 | 90.23 | 32.04 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.24 | 5.97 | 0.59 |
| 10 | 1 | 57 | 5868 | 19.22 | 6.79 | 0.61 |
| 10 | 5 | 284 | 6003 | 25.03 | 9.31 | 0.68 |
| 10 | 10 | 569 | 6173 | 34.05 | 13.07 | 0.79 |
| 10 | 20 | 1138 | 6512 | 54.33 | 21.37 | 1.03 |
| 10 | 30 | 1709 | 6855 | 71.33 | 28.51 | 1.23 |
| 10 | 45 | 2561 | 7362 | 99.10 | 40.02 | 1.56 |


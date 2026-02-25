--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 16:54:35.378846117 UTC |
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
| 1| 5836 | 11.02 | 3.52 | 0.52 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.84 | 4.71 | 0.58 |
| 5| 6643 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.29 | 5.75 | 0.36 |
| 2 | 114 | 636 | 24.11 | 7.55 | 0.43 |
| 3 | 171 | 747 | 29.97 | 9.38 | 0.49 |
| 4 | 226 | 858 | 39.44 | 12.14 | 0.59 |
| 5 | 282 | 969 | 42.56 | 13.26 | 0.63 |
| 6 | 339 | 1085 | 54.39 | 16.59 | 0.76 |
| 7 | 395 | 1192 | 54.67 | 17.09 | 0.77 |
| 8 | 451 | 1303 | 65.24 | 20.14 | 0.88 |
| 9 | 506 | 1414 | 72.25 | 22.25 | 0.96 |
| 10 | 561 | 1525 | 82.27 | 25.20 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 18.05 | 6.29 | 0.42 |
| 2| 1882 | 18.43 | 7.06 | 0.43 |
| 3| 2124 | 21.07 | 8.52 | 0.48 |
| 5| 2340 | 22.56 | 10.30 | 0.51 |
| 10| 3316 | 32.23 | 16.55 | 0.68 |
| 50| 9325 | 90.86 | 60.62 | 1.73 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 16.65 | 5.99 | 0.35 |
| 2| 776 | 17.91 | 7.02 | 0.38 |
| 3| 946 | 19.45 | 8.15 | 0.41 |
| 5| 1167 | 21.05 | 9.95 | 0.44 |
| 10| 2106 | 30.93 | 16.24 | 0.61 |
| 50| 8076 | 90.65 | 60.56 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 20.72 | 6.94 | 0.40 |
| 2| 907 | 22.61 | 8.19 | 0.43 |
| 3| 1070 | 24.37 | 9.39 | 0.46 |
| 5| 1321 | 27.03 | 11.51 | 0.51 |
| 10| 1970 | 33.48 | 16.76 | 0.63 |
| 50| 7989 | 94.60 | 61.58 | 1.71 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 24.80 | 8.08 | 0.44 |
| 2| 872 | 27.44 | 9.55 | 0.48 |
| 3| 1013 | 28.93 | 10.66 | 0.51 |
| 5| 1245 | 32.10 | 12.92 | 0.56 |
| 10| 1957 | 40.13 | 18.62 | 0.69 |
| 43| 6774 | 97.68 | 57.54 | 1.65 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 23.82 | 8.35 | 0.66 |
| 2| 6024 | 32.24 | 11.41 | 0.76 |
| 3| 5989 | 36.03 | 12.66 | 0.80 |
| 4| 6282 | 47.91 | 16.96 | 0.94 |
| 5| 6259 | 49.15 | 17.31 | 0.95 |
| 6| 6545 | 62.96 | 22.32 | 1.11 |
| 7| 6703 | 74.94 | 26.50 | 1.24 |
| 8| 6999 | 87.09 | 30.59 | 1.38 |
| 9| 6957 | 88.46 | 31.20 | 1.40 |
| 10| 7208 | 91.06 | 32.25 | 1.44 |
| 11| 7161 | 96.17 | 33.99 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.83 | 5.83 | 0.59 |
| 10 | 1 | 57 | 5868 | 19.05 | 6.73 | 0.61 |
| 10 | 10 | 569 | 6173 | 35.47 | 13.57 | 0.81 |
| 10 | 20 | 1136 | 6511 | 53.92 | 21.22 | 1.03 |
| 10 | 30 | 1706 | 6852 | 71.91 | 28.71 | 1.24 |
| 10 | 40 | 2280 | 7196 | 89.98 | 36.23 | 1.46 |
| 10 | 45 | 2556 | 7358 | 98.45 | 39.79 | 1.56 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-20 05:34:46.086920126 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6645 | 18.79 | 5.94 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 114 | 636 | 24.61 | 7.68 | 0.43 |
| 3 | 170 | 751 | 29.97 | 9.38 | 0.49 |
| 4 | 226 | 858 | 38.25 | 11.80 | 0.58 |
| 5 | 281 | 969 | 47.06 | 14.39 | 0.68 |
| 6 | 339 | 1081 | 54.44 | 16.60 | 0.76 |
| 7 | 396 | 1192 | 63.95 | 19.45 | 0.86 |
| 8 | 451 | 1303 | 69.11 | 21.05 | 0.92 |
| 9 | 506 | 1414 | 83.85 | 25.26 | 1.07 |
| 10 | 560 | 1529 | 95.54 | 28.68 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 18.10 | 6.30 | 0.42 |
| 2| 1882 | 18.48 | 7.08 | 0.43 |
| 3| 2105 | 20.73 | 8.44 | 0.47 |
| 5| 2317 | 22.33 | 10.24 | 0.51 |
| 10| 3239 | 31.93 | 16.44 | 0.67 |
| 50| 9228 | 89.46 | 60.20 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 16.61 | 5.97 | 0.36 |
| 2| 745 | 17.77 | 6.98 | 0.38 |
| 3| 915 | 18.55 | 7.85 | 0.40 |
| 5| 1233 | 21.55 | 10.08 | 0.45 |
| 10| 1931 | 28.22 | 15.44 | 0.57 |
| 50| 8034 | 86.67 | 59.44 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 21.88 | 7.28 | 0.41 |
| 2| 847 | 22.56 | 8.17 | 0.43 |
| 3| 1006 | 25.70 | 9.77 | 0.47 |
| 5| 1218 | 27.94 | 11.74 | 0.51 |
| 10| 2047 | 34.10 | 16.95 | 0.64 |
| 50| 8070 | 95.08 | 61.79 | 1.72 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 25.32 | 8.25 | 0.44 |
| 2| 868 | 27.41 | 9.55 | 0.48 |
| 3| 937 | 28.44 | 10.50 | 0.50 |
| 5| 1315 | 32.63 | 13.09 | 0.57 |
| 10| 2031 | 40.77 | 18.83 | 0.70 |
| 42| 6962 | 99.57 | 57.46 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 23.71 | 8.32 | 0.66 |
| 2| 5968 | 31.31 | 11.02 | 0.75 |
| 3| 6109 | 38.87 | 13.75 | 0.83 |
| 4| 6379 | 48.00 | 17.07 | 0.94 |
| 5| 6482 | 56.29 | 20.00 | 1.03 |
| 6| 6583 | 61.74 | 21.92 | 1.10 |
| 7| 6650 | 70.03 | 24.78 | 1.19 |
| 8| 7187 | 87.62 | 31.05 | 1.40 |
| 9| 7073 | 86.88 | 30.84 | 1.39 |
| 10| 7176 | 99.54 | 35.02 | 1.52 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.83 | 5.83 | 0.58 |
| 10 | 1 | 57 | 5868 | 19.46 | 6.87 | 0.62 |
| 10 | 5 | 284 | 6003 | 25.85 | 9.60 | 0.69 |
| 10 | 10 | 567 | 6171 | 35.47 | 13.57 | 0.81 |
| 10 | 20 | 1137 | 6511 | 52.68 | 20.79 | 1.01 |
| 10 | 30 | 1707 | 6853 | 70.91 | 28.36 | 1.23 |
| 10 | 40 | 2280 | 7197 | 88.74 | 35.79 | 1.44 |
| 10 | 45 | 2559 | 7360 | 99.52 | 40.16 | 1.57 |


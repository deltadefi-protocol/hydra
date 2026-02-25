--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 09:27:57.982667959 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.88 | 4.72 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 18.67 | 5.84 | 0.37 |
| 2 | 114 | 640 | 24.10 | 7.55 | 0.43 |
| 3 | 170 | 751 | 30.09 | 9.43 | 0.49 |
| 4 | 225 | 858 | 36.18 | 11.32 | 0.56 |
| 5 | 282 | 974 | 44.26 | 13.68 | 0.65 |
| 6 | 340 | 1081 | 54.32 | 16.57 | 0.76 |
| 7 | 393 | 1192 | 56.78 | 17.55 | 0.79 |
| 8 | 451 | 1307 | 73.30 | 22.14 | 0.96 |
| 9 | 505 | 1414 | 73.62 | 22.54 | 0.97 |
| 10 | 560 | 1525 | 82.35 | 25.21 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 17.84 | 6.24 | 0.42 |
| 2| 1944 | 19.19 | 7.29 | 0.44 |
| 3| 2112 | 20.94 | 8.49 | 0.47 |
| 5| 2388 | 22.99 | 10.44 | 0.52 |
| 10| 3135 | 30.33 | 15.96 | 0.65 |
| 50| 9656 | 93.41 | 61.41 | 1.77 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 16.79 | 6.03 | 0.36 |
| 2| 768 | 17.51 | 6.87 | 0.38 |
| 3| 828 | 17.86 | 7.63 | 0.39 |
| 5| 1350 | 23.71 | 10.76 | 0.48 |
| 10| 1961 | 29.58 | 15.84 | 0.59 |
| 50| 8027 | 86.96 | 59.52 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 20.72 | 6.94 | 0.40 |
| 2| 774 | 23.23 | 8.34 | 0.43 |
| 3| 868 | 24.12 | 9.25 | 0.45 |
| 5| 1339 | 26.93 | 11.48 | 0.51 |
| 10| 2077 | 34.51 | 17.09 | 0.64 |
| 49| 7839 | 99.74 | 62.39 | 1.75 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 25.37 | 8.26 | 0.44 |
| 2| 887 | 27.44 | 9.55 | 0.48 |
| 3| 937 | 28.39 | 10.48 | 0.50 |
| 5| 1370 | 33.08 | 13.24 | 0.57 |
| 10| 2097 | 41.38 | 19.02 | 0.71 |
| 42| 6832 | 97.84 | 56.95 | 1.65 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 23.73 | 8.33 | 0.66 |
| 2| 5893 | 30.31 | 10.64 | 0.73 |
| 3| 6098 | 37.10 | 13.09 | 0.81 |
| 4| 6345 | 48.87 | 17.35 | 0.95 |
| 5| 6410 | 55.94 | 19.88 | 1.03 |
| 6| 6690 | 65.08 | 23.18 | 1.14 |
| 7| 6776 | 73.56 | 26.10 | 1.23 |
| 8| 6784 | 82.82 | 28.90 | 1.33 |
| 9| 7135 | 88.07 | 31.26 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.83 | 5.83 | 0.59 |
| 10 | 5 | 285 | 6004 | 26.27 | 9.74 | 0.70 |
| 10 | 10 | 568 | 6173 | 35.47 | 13.57 | 0.81 |
| 10 | 20 | 1139 | 6514 | 54.33 | 21.37 | 1.03 |
| 10 | 30 | 1708 | 6854 | 70.91 | 28.36 | 1.23 |
| 10 | 40 | 2278 | 7195 | 89.57 | 36.08 | 1.45 |
| 10 | 45 | 2560 | 7362 | 99.69 | 40.22 | 1.57 |


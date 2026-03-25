--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-25 04:12:01.022697964 UTC |
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
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 24.74 | 7.72 | 0.43 |
| 3 | 170 | 747 | 32.21 | 9.97 | 0.52 |
| 4 | 225 | 858 | 39.43 | 12.14 | 0.59 |
| 5 | 283 | 969 | 44.64 | 13.78 | 0.65 |
| 6 | 339 | 1085 | 49.45 | 15.38 | 0.71 |
| 7 | 393 | 1196 | 56.43 | 17.51 | 0.79 |
| 8 | 449 | 1303 | 68.87 | 21.02 | 0.92 |
| 9 | 504 | 1418 | 80.18 | 24.29 | 1.04 |
| 10 | 560 | 1529 | 84.14 | 25.61 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 17.84 | 6.24 | 0.42 |
| 2| 1883 | 18.48 | 7.08 | 0.43 |
| 3| 2141 | 21.09 | 8.53 | 0.48 |
| 5| 2275 | 21.49 | 9.99 | 0.50 |
| 10| 3342 | 32.13 | 16.53 | 0.68 |
| 50| 9048 | 85.18 | 58.91 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 16.61 | 5.98 | 0.36 |
| 2| 793 | 18.72 | 7.27 | 0.39 |
| 3| 874 | 19.04 | 8.03 | 0.40 |
| 5| 1140 | 20.78 | 9.86 | 0.44 |
| 10| 2015 | 31.16 | 16.29 | 0.61 |
| 50| 8184 | 90.35 | 60.47 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 21.91 | 7.28 | 0.41 |
| 2| 893 | 22.53 | 8.17 | 0.43 |
| 3| 902 | 22.78 | 8.87 | 0.44 |
| 5| 1248 | 26.36 | 11.30 | 0.50 |
| 10| 1893 | 34.64 | 17.06 | 0.64 |
| 49| 7819 | 98.23 | 61.91 | 1.73 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 25.34 | 8.25 | 0.44 |
| 2| 764 | 26.31 | 9.19 | 0.46 |
| 3| 941 | 28.42 | 10.49 | 0.50 |
| 5| 1200 | 31.56 | 12.74 | 0.55 |
| 10| 2008 | 40.52 | 18.74 | 0.70 |
| 42| 6932 | 99.20 | 57.38 | 1.67 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 23.67 | 8.32 | 0.66 |
| 2| 6043 | 32.23 | 11.41 | 0.76 |
| 3| 6227 | 40.78 | 14.50 | 0.86 |
| 4| 6232 | 46.64 | 16.50 | 0.92 |
| 5| 6274 | 49.17 | 17.32 | 0.95 |
| 6| 6524 | 61.09 | 21.66 | 1.09 |
| 7| 6764 | 72.08 | 25.59 | 1.21 |
| 8| 6733 | 73.35 | 25.93 | 1.23 |
| 9| 6992 | 87.60 | 30.82 | 1.39 |
| 10| 7262 | 98.38 | 34.80 | 1.52 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.00 | 5.54 | 0.58 |
| 10 | 1 | 57 | 5868 | 18.80 | 6.64 | 0.61 |
| 10 | 10 | 570 | 6174 | 34.88 | 13.36 | 0.80 |
| 10 | 30 | 1709 | 6855 | 72.57 | 28.94 | 1.25 |
| 10 | 45 | 2559 | 7360 | 99.27 | 40.08 | 1.57 |


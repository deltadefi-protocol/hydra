--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 16:29:51.388469508 UTC |
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
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 99.33 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 114 | 636 | 24.62 | 7.68 | 0.43 |
| 3 | 169 | 751 | 29.99 | 9.38 | 0.49 |
| 4 | 227 | 858 | 38.72 | 11.94 | 0.59 |
| 5 | 283 | 969 | 43.05 | 13.37 | 0.64 |
| 6 | 340 | 1081 | 54.18 | 16.60 | 0.76 |
| 7 | 395 | 1196 | 54.98 | 17.09 | 0.77 |
| 8 | 449 | 1303 | 72.42 | 22.03 | 0.95 |
| 9 | 505 | 1418 | 75.01 | 22.99 | 0.98 |
| 10 | 560 | 1525 | 90.08 | 27.07 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 18.10 | 6.30 | 0.42 |
| 2| 1974 | 19.69 | 7.46 | 0.45 |
| 3| 2070 | 20.23 | 8.27 | 0.46 |
| 5| 2360 | 22.97 | 10.44 | 0.51 |
| 10| 3034 | 28.77 | 15.49 | 0.63 |
| 50| 9331 | 89.54 | 60.24 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 16.81 | 6.02 | 0.36 |
| 2| 766 | 17.86 | 7.01 | 0.38 |
| 3| 908 | 18.58 | 7.86 | 0.40 |
| 5| 1354 | 24.32 | 10.96 | 0.49 |
| 10| 1924 | 27.83 | 15.29 | 0.57 |
| 50| 8036 | 85.82 | 59.20 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 20.74 | 6.95 | 0.40 |
| 2| 812 | 21.97 | 7.98 | 0.42 |
| 3| 1047 | 24.48 | 9.42 | 0.46 |
| 5| 1194 | 27.34 | 11.55 | 0.51 |
| 10| 2060 | 36.88 | 17.78 | 0.67 |
| 50| 7923 | 94.91 | 61.68 | 1.71 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 25.37 | 8.26 | 0.44 |
| 2| 761 | 26.36 | 9.20 | 0.46 |
| 3| 969 | 28.39 | 10.48 | 0.50 |
| 5| 1224 | 31.45 | 12.71 | 0.55 |
| 10| 2116 | 41.59 | 19.10 | 0.72 |
| 43| 6757 | 97.64 | 57.51 | 1.65 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 23.81 | 8.36 | 0.66 |
| 2| 5885 | 28.47 | 9.96 | 0.71 |
| 3| 6015 | 35.93 | 12.61 | 0.80 |
| 4| 6210 | 47.62 | 16.85 | 0.93 |
| 5| 6567 | 57.42 | 20.40 | 1.05 |
| 6| 6682 | 64.81 | 23.13 | 1.13 |
| 7| 6560 | 67.37 | 23.73 | 1.15 |
| 8| 6632 | 72.33 | 25.57 | 1.21 |
| 9| 7037 | 88.41 | 31.38 | 1.40 |
| 10| 6847 | 84.80 | 29.82 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 16.59 | 5.75 | 0.58 |
| 10 | 1 | 57 | 5869 | 19.05 | 6.73 | 0.61 |
| 10 | 5 | 284 | 6004 | 26.85 | 9.95 | 0.70 |
| 10 | 30 | 1706 | 6852 | 71.74 | 28.65 | 1.24 |
| 10 | 45 | 2559 | 7360 | 99.69 | 40.22 | 1.57 |


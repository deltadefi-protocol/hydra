--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 10:58:05.230928867 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 113 | 636 | 24.09 | 7.54 | 0.43 |
| 3 | 170 | 747 | 29.87 | 9.34 | 0.49 |
| 4 | 227 | 858 | 39.00 | 11.99 | 0.59 |
| 5 | 282 | 974 | 43.14 | 13.40 | 0.64 |
| 6 | 338 | 1081 | 53.18 | 16.25 | 0.74 |
| 7 | 395 | 1196 | 60.54 | 18.55 | 0.83 |
| 8 | 449 | 1303 | 63.46 | 19.53 | 0.86 |
| 9 | 507 | 1414 | 80.78 | 24.51 | 1.04 |
| 10 | 560 | 1525 | 98.91 | 29.56 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 17.84 | 6.24 | 0.42 |
| 2| 1916 | 18.98 | 7.24 | 0.44 |
| 3| 2056 | 20.26 | 8.28 | 0.46 |
| 5| 2430 | 23.91 | 10.71 | 0.53 |
| 10| 3235 | 31.02 | 16.17 | 0.66 |
| 50| 9327 | 90.40 | 60.47 | 1.73 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 16.81 | 6.02 | 0.36 |
| 2| 723 | 16.75 | 6.64 | 0.37 |
| 3| 830 | 17.83 | 7.65 | 0.39 |
| 5| 1217 | 21.57 | 10.08 | 0.45 |
| 10| 2015 | 29.80 | 15.92 | 0.59 |
| 50| 8130 | 88.46 | 59.99 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 21.93 | 7.29 | 0.41 |
| 2| 786 | 23.29 | 8.35 | 0.43 |
| 3| 865 | 24.05 | 9.23 | 0.45 |
| 5| 1231 | 27.88 | 11.73 | 0.51 |
| 10| 2013 | 34.13 | 16.96 | 0.64 |
| 49| 7828 | 93.52 | 60.62 | 1.69 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 25.37 | 8.26 | 0.44 |
| 2| 823 | 26.92 | 9.38 | 0.47 |
| 3| 937 | 28.47 | 10.50 | 0.50 |
| 5| 1199 | 31.45 | 12.71 | 0.55 |
| 10| 1942 | 39.90 | 18.55 | 0.69 |
| 42| 6887 | 99.22 | 57.39 | 1.67 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 23.71 | 8.34 | 0.66 |
| 2| 6005 | 32.24 | 11.41 | 0.76 |
| 3| 6085 | 38.81 | 13.71 | 0.83 |
| 4| 6188 | 43.52 | 15.31 | 0.88 |
| 5| 6433 | 55.25 | 19.58 | 1.02 |
| 6| 6517 | 63.51 | 22.44 | 1.11 |
| 7| 6599 | 66.24 | 23.39 | 1.14 |
| 8| 7022 | 78.86 | 28.05 | 1.30 |
| 9| 7117 | 94.68 | 33.38 | 1.47 |
| 10| 7075 | 91.46 | 32.24 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.24 | 5.97 | 0.59 |
| 10 | 1 | 57 | 5869 | 18.22 | 6.44 | 0.60 |
| 10 | 10 | 568 | 6173 | 34.88 | 13.36 | 0.80 |
| 10 | 30 | 1710 | 6856 | 71.50 | 28.57 | 1.24 |
| 10 | 40 | 2273 | 7189 | 89.74 | 36.14 | 1.45 |
| 10 | 46 | 2618 | 7396 | 99.69 | 40.34 | 1.57 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-24 03:17:46.239400276 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.84 | 4.71 | 0.58 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.71 | 5.86 | 0.37 |
| 2 | 114 | 636 | 24.18 | 7.58 | 0.43 |
| 3 | 170 | 747 | 31.30 | 9.71 | 0.51 |
| 4 | 227 | 858 | 39.62 | 12.19 | 0.60 |
| 5 | 283 | 969 | 43.37 | 13.49 | 0.64 |
| 6 | 338 | 1081 | 52.97 | 16.24 | 0.74 |
| 7 | 393 | 1192 | 63.31 | 19.23 | 0.85 |
| 8 | 448 | 1303 | 64.42 | 19.94 | 0.87 |
| 9 | 505 | 1414 | 72.85 | 22.40 | 0.96 |
| 10 | 560 | 1525 | 90.26 | 27.31 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 17.89 | 6.25 | 0.42 |
| 2| 1988 | 19.95 | 7.52 | 0.45 |
| 3| 2124 | 20.99 | 8.50 | 0.47 |
| 5| 2570 | 25.47 | 11.19 | 0.55 |
| 10| 3103 | 29.41 | 15.69 | 0.64 |
| 50| 9531 | 93.09 | 61.28 | 1.76 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 16.77 | 6.01 | 0.36 |
| 2| 741 | 17.51 | 6.87 | 0.37 |
| 3| 964 | 19.81 | 8.26 | 0.41 |
| 5| 1259 | 22.76 | 10.49 | 0.47 |
| 10| 2109 | 30.99 | 16.26 | 0.61 |
| 50| 8282 | 89.23 | 60.23 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 21.91 | 7.28 | 0.41 |
| 2| 894 | 22.53 | 8.17 | 0.43 |
| 3| 996 | 23.81 | 9.21 | 0.45 |
| 5| 1220 | 27.91 | 11.74 | 0.51 |
| 10| 2018 | 36.03 | 17.49 | 0.66 |
| 48| 7646 | 96.66 | 60.80 | 1.71 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 25.32 | 8.25 | 0.44 |
| 2| 812 | 26.92 | 9.38 | 0.47 |
| 3| 938 | 28.42 | 10.49 | 0.50 |
| 5| 1267 | 32.12 | 12.92 | 0.56 |
| 10| 1963 | 40.51 | 18.74 | 0.70 |
| 41| 6886 | 98.62 | 56.58 | 1.66 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 23.78 | 8.35 | 0.66 |
| 2| 5978 | 32.27 | 11.41 | 0.76 |
| 3| 6132 | 39.79 | 14.08 | 0.84 |
| 4| 6330 | 48.82 | 17.33 | 0.95 |
| 5| 6400 | 55.34 | 19.63 | 1.02 |
| 6| 6384 | 59.17 | 20.85 | 1.06 |
| 7| 6674 | 71.33 | 25.16 | 1.20 |
| 8| 6973 | 80.04 | 28.37 | 1.31 |
| 9| 7037 | 85.99 | 30.53 | 1.37 |
| 11| 6983 | 93.55 | 32.85 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5868 | 19.05 | 6.73 | 0.61 |
| 10 | 5 | 283 | 6002 | 25.03 | 9.31 | 0.68 |
| 10 | 10 | 568 | 6172 | 34.88 | 13.36 | 0.80 |
| 10 | 20 | 1137 | 6512 | 51.85 | 20.50 | 1.00 |
| 10 | 30 | 1708 | 6854 | 71.33 | 28.51 | 1.23 |
| 10 | 45 | 2562 | 7363 | 98.69 | 39.87 | 1.56 |


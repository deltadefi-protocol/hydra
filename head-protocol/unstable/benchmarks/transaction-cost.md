--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-24 12:26:01.641805179 UTC |
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
| 1| 5840 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 113 | 636 | 24.10 | 7.55 | 0.43 |
| 3 | 171 | 747 | 30.06 | 9.42 | 0.49 |
| 4 | 226 | 858 | 38.49 | 11.88 | 0.58 |
| 5 | 281 | 969 | 47.00 | 14.38 | 0.68 |
| 6 | 337 | 1085 | 49.66 | 15.37 | 0.71 |
| 7 | 394 | 1192 | 56.81 | 17.55 | 0.79 |
| 8 | 450 | 1303 | 66.53 | 20.47 | 0.89 |
| 9 | 504 | 1418 | 72.23 | 22.15 | 0.96 |
| 10 | 560 | 1525 | 89.13 | 26.91 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 17.89 | 6.25 | 0.42 |
| 2| 1926 | 19.19 | 7.29 | 0.44 |
| 3| 2069 | 20.05 | 8.23 | 0.46 |
| 5| 2493 | 24.59 | 10.92 | 0.54 |
| 10| 3195 | 30.93 | 16.15 | 0.66 |
| 50| 9335 | 89.70 | 60.30 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 16.81 | 6.02 | 0.36 |
| 2| 846 | 18.65 | 7.25 | 0.39 |
| 3| 902 | 18.62 | 7.88 | 0.40 |
| 5| 1232 | 21.55 | 10.08 | 0.45 |
| 10| 2009 | 29.18 | 15.70 | 0.59 |
| 50| 8126 | 87.86 | 59.80 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 20.72 | 6.94 | 0.40 |
| 2| 733 | 22.72 | 8.17 | 0.42 |
| 3| 952 | 23.29 | 9.04 | 0.45 |
| 5| 1248 | 27.94 | 11.74 | 0.52 |
| 10| 1994 | 33.51 | 16.76 | 0.63 |
| 50| 7975 | 95.85 | 61.98 | 1.72 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 25.34 | 8.25 | 0.44 |
| 2| 816 | 26.92 | 9.38 | 0.47 |
| 3| 997 | 28.98 | 10.67 | 0.51 |
| 5| 1208 | 31.43 | 12.71 | 0.55 |
| 10| 1975 | 40.15 | 18.63 | 0.70 |
| 43| 6972 | 99.84 | 58.21 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 23.78 | 8.36 | 0.66 |
| 2| 6019 | 32.11 | 11.36 | 0.76 |
| 3| 6040 | 38.13 | 13.42 | 0.82 |
| 4| 6142 | 42.59 | 14.96 | 0.87 |
| 5| 6387 | 55.57 | 19.68 | 1.02 |
| 6| 6666 | 65.39 | 23.18 | 1.14 |
| 7| 6745 | 71.71 | 25.42 | 1.21 |
| 8| 6945 | 83.12 | 29.39 | 1.34 |
| 9| 6873 | 88.09 | 30.71 | 1.39 |
| 11| 7135 | 98.96 | 34.62 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 17.98 | 6.35 | 0.60 |
| 10 | 5 | 285 | 6005 | 25.85 | 9.60 | 0.69 |
| 10 | 10 | 570 | 6175 | 35.29 | 13.51 | 0.80 |
| 10 | 30 | 1707 | 6854 | 71.33 | 28.51 | 1.23 |
| 10 | 44 | 2507 | 7331 | 97.28 | 39.26 | 1.54 |


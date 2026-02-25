--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 09:39:05.109183719 UTC |
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
| 1| 5836 | 10.67 | 3.39 | 0.52 |
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.48 | 4.58 | 0.57 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14285 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 114 | 636 | 25.17 | 7.82 | 0.44 |
| 3 | 171 | 747 | 30.77 | 9.59 | 0.50 |
| 4 | 225 | 858 | 36.44 | 11.39 | 0.56 |
| 5 | 283 | 969 | 47.56 | 14.61 | 0.68 |
| 6 | 340 | 1081 | 50.73 | 15.67 | 0.72 |
| 7 | 395 | 1192 | 60.94 | 18.63 | 0.83 |
| 8 | 450 | 1303 | 69.18 | 21.24 | 0.92 |
| 9 | 505 | 1414 | 70.18 | 21.70 | 0.94 |
| 10 | 560 | 1525 | 86.24 | 25.96 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 18.10 | 6.30 | 0.42 |
| 2| 1952 | 18.96 | 7.24 | 0.44 |
| 3| 2013 | 19.31 | 8.00 | 0.45 |
| 5| 2318 | 22.30 | 10.23 | 0.51 |
| 10| 3124 | 30.04 | 15.89 | 0.65 |
| 50| 9291 | 89.90 | 60.31 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 16.64 | 5.98 | 0.36 |
| 2| 726 | 16.72 | 6.64 | 0.37 |
| 3| 963 | 19.74 | 8.24 | 0.41 |
| 5| 1290 | 23.03 | 10.56 | 0.47 |
| 10| 1860 | 27.02 | 15.04 | 0.56 |
| 50| 7952 | 85.72 | 59.19 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 21.93 | 7.29 | 0.41 |
| 2| 783 | 23.31 | 8.36 | 0.43 |
| 3| 960 | 23.29 | 9.04 | 0.45 |
| 5| 1168 | 27.42 | 11.57 | 0.51 |
| 10| 1828 | 34.11 | 16.88 | 0.63 |
| 48| 7872 | 93.49 | 60.00 | 1.68 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 25.34 | 8.25 | 0.44 |
| 2| 863 | 27.49 | 9.57 | 0.48 |
| 3| 1011 | 28.98 | 10.67 | 0.51 |
| 5| 1310 | 32.61 | 13.09 | 0.57 |
| 10| 2243 | 43.52 | 19.73 | 0.74 |
| 43| 6800 | 98.87 | 57.85 | 1.67 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 23.75 | 8.33 | 0.66 |
| 2| 5961 | 31.26 | 11.01 | 0.74 |
| 3| 6035 | 39.02 | 13.77 | 0.83 |
| 4| 6213 | 45.98 | 16.21 | 0.91 |
| 5| 6495 | 57.85 | 20.57 | 1.05 |
| 6| 6510 | 59.44 | 20.94 | 1.07 |
| 7| 6836 | 73.11 | 26.10 | 1.23 |
| 8| 6827 | 78.22 | 27.73 | 1.28 |
| 9| 7213 | 96.20 | 34.01 | 1.49 |
| 10| 7061 | 93.58 | 32.97 | 1.45 |
| 11| 7112 | 98.46 | 34.62 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.24 | 5.97 | 0.59 |
| 10 | 5 | 284 | 6003 | 26.44 | 9.80 | 0.70 |
| 10 | 10 | 570 | 6174 | 35.88 | 13.71 | 0.81 |
| 10 | 20 | 1139 | 6514 | 53.68 | 21.14 | 1.02 |
| 10 | 40 | 2281 | 7198 | 89.98 | 36.23 | 1.46 |
| 10 | 44 | 2505 | 7329 | 96.86 | 39.11 | 1.54 |


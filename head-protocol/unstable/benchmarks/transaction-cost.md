--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-25 04:47:03.116227139 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.25 | 5.74 | 0.36 |
| 2 | 114 | 636 | 24.11 | 7.55 | 0.43 |
| 3 | 169 | 747 | 31.55 | 9.80 | 0.51 |
| 4 | 226 | 858 | 37.16 | 11.55 | 0.57 |
| 5 | 282 | 974 | 45.79 | 14.08 | 0.66 |
| 6 | 341 | 1081 | 49.71 | 15.38 | 0.71 |
| 7 | 395 | 1196 | 61.05 | 18.71 | 0.83 |
| 8 | 448 | 1303 | 67.53 | 20.62 | 0.90 |
| 9 | 504 | 1414 | 77.15 | 23.50 | 1.01 |
| 10 | 561 | 1525 | 81.60 | 24.92 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 18.05 | 6.29 | 0.42 |
| 2| 1946 | 19.16 | 7.29 | 0.44 |
| 3| 2167 | 21.64 | 8.71 | 0.48 |
| 5| 2381 | 22.99 | 10.44 | 0.52 |
| 10| 3118 | 29.69 | 15.76 | 0.64 |
| 50| 9307 | 89.18 | 60.12 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 16.81 | 6.02 | 0.36 |
| 2| 769 | 17.77 | 6.99 | 0.38 |
| 3| 951 | 19.84 | 8.28 | 0.41 |
| 5| 1285 | 23.09 | 10.56 | 0.47 |
| 10| 1861 | 27.04 | 15.05 | 0.56 |
| 50| 7897 | 84.66 | 58.85 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 21.93 | 7.29 | 0.41 |
| 2| 812 | 21.97 | 7.98 | 0.42 |
| 3| 957 | 23.24 | 9.03 | 0.45 |
| 5| 1272 | 26.44 | 11.32 | 0.50 |
| 10| 1871 | 34.73 | 17.08 | 0.64 |
| 50| 7745 | 98.81 | 62.69 | 1.74 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 25.34 | 8.25 | 0.44 |
| 2| 814 | 26.92 | 9.38 | 0.47 |
| 3| 991 | 28.98 | 10.67 | 0.50 |
| 5| 1351 | 33.15 | 13.26 | 0.57 |
| 10| 2025 | 40.36 | 18.70 | 0.70 |
| 43| 6983 | 99.09 | 57.98 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 23.77 | 8.34 | 0.66 |
| 2| 5937 | 31.31 | 11.02 | 0.74 |
| 3| 6100 | 38.88 | 13.75 | 0.83 |
| 4| 6142 | 45.91 | 16.18 | 0.91 |
| 5| 6492 | 56.60 | 20.06 | 1.04 |
| 6| 6460 | 61.38 | 21.62 | 1.09 |
| 7| 6624 | 69.35 | 24.43 | 1.18 |
| 8| 6743 | 73.38 | 25.95 | 1.23 |
| 9| 7136 | 94.39 | 33.17 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.24 | 5.97 | 0.59 |
| 10 | 1 | 56 | 5867 | 17.81 | 6.29 | 0.60 |
| 10 | 5 | 285 | 6005 | 26.68 | 9.89 | 0.70 |
| 10 | 10 | 569 | 6173 | 35.71 | 13.65 | 0.81 |
| 10 | 20 | 1138 | 6513 | 53.09 | 20.93 | 1.02 |
| 10 | 40 | 2278 | 7195 | 89.57 | 36.08 | 1.45 |
| 10 | 46 | 2617 | 7395 | 99.27 | 40.19 | 1.57 |


--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-11 08:25:43.166739816 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 10.69 | 3.40 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6243 | 14.72 | 4.66 | 0.58 |
| 5| 6645 | 18.62 | 5.87 | 0.64 |
| 10| 7651 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.33 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 41.35 | 11.98 | 0.60 |
| 4 | 226 | 858 | 50.84 | 14.60 | 0.70 |
| 5 | 281 | 969 | 62.76 | 17.90 | 0.83 |
| 6 | 337 | 1081 | 66.35 | 19.19 | 0.87 |
| 7 | 394 | 1192 | 78.33 | 22.38 | 1.00 |
| 8 | 451 | 1303 | 92.12 | 26.13 | 1.14 |
| 9 | 504 | 1414 | 95.98 | 27.51 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.40 | 8.39 | 0.49 |
| 3| 2106 | 28.39 | 10.16 | 0.55 |
| 5| 2342 | 30.00 | 11.96 | 0.58 |
| 10| 3199 | 43.18 | 18.96 | 0.78 |
| 39| 7367 | 94.52 | 52.54 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 693 | 22.58 | 7.94 | 0.42 |
| 3| 1045 | 27.89 | 10.12 | 0.49 |
| 5| 1181 | 29.07 | 11.77 | 0.52 |
| 10| 1928 | 38.29 | 17.70 | 0.67 |
| 41| 6443 | 94.32 | 53.91 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.47 | 8.46 | 0.46 |
| 2| 864 | 29.97 | 9.84 | 0.50 |
| 3| 1002 | 33.43 | 11.45 | 0.55 |
| 5| 1331 | 35.76 | 13.47 | 0.59 |
| 10| 2094 | 45.46 | 19.55 | 0.75 |
| 37| 6115 | 99.18 | 52.60 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.79 | 10.15 | 0.53 |
| 2| 803 | 35.92 | 11.40 | 0.56 |
| 3| 966 | 37.88 | 12.61 | 0.59 |
| 5| 1288 | 43.25 | 15.47 | 0.67 |
| 10| 2070 | 54.92 | 22.08 | 0.84 |
| 28| 4710 | 95.71 | 45.38 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5886 | 32.41 | 10.84 | 0.75 |
| 3| 6139 | 46.20 | 15.57 | 0.91 |
| 4| 6299 | 54.05 | 18.26 | 1.00 |
| 5| 6355 | 58.33 | 19.59 | 1.04 |
| 6| 6510 | 73.07 | 24.64 | 1.20 |
| 7| 6744 | 83.51 | 28.09 | 1.32 |
| 8| 6845 | 92.58 | 31.22 | 1.42 |
| 9| 6801 | 93.08 | 31.19 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.05 | 6.02 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6856 | 80.67 | 30.67 | 1.32 |
| 10 | 37 | 2106 | 7091 | 94.39 | 36.12 | 1.49 |


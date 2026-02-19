--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-19 03:58:01.105285299 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.76 | 4.67 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10081 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 226 | 858 | 47.83 | 13.90 | 0.67 |
| 5 | 284 | 969 | 63.97 | 18.12 | 0.84 |
| 6 | 338 | 1081 | 67.52 | 19.40 | 0.88 |
| 7 | 395 | 1192 | 78.32 | 22.34 | 1.00 |
| 8 | 449 | 1303 | 80.94 | 23.45 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.47 | 8.70 | 0.50 |
| 3| 2067 | 27.06 | 9.80 | 0.53 |
| 5| 2398 | 31.17 | 12.28 | 0.60 |
| 10| 3066 | 39.75 | 18.01 | 0.74 |
| 40| 7700 | 99.03 | 54.50 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.80 | 7.37 | 0.42 |
| 2| 751 | 23.58 | 8.24 | 0.43 |
| 3| 965 | 26.16 | 9.62 | 0.47 |
| 5| 1268 | 31.30 | 12.39 | 0.55 |
| 10| 1892 | 37.43 | 17.43 | 0.66 |
| 39| 6484 | 98.54 | 53.79 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.47 | 8.46 | 0.46 |
| 2| 823 | 29.18 | 9.60 | 0.49 |
| 3| 1052 | 32.37 | 11.19 | 0.54 |
| 5| 1281 | 37.54 | 13.95 | 0.61 |
| 10| 2040 | 44.98 | 19.39 | 0.74 |
| 36| 6292 | 99.94 | 52.24 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 33.83 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 938 | 37.95 | 12.63 | 0.59 |
| 5| 1254 | 42.68 | 15.29 | 0.66 |
| 10| 1989 | 53.20 | 21.55 | 0.82 |
| 28| 4521 | 92.20 | 44.35 | 1.41 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 26.96 | 9.06 | 0.69 |
| 2| 5959 | 36.92 | 12.46 | 0.80 |
| 3| 6108 | 44.53 | 14.97 | 0.89 |
| 4| 6312 | 52.35 | 17.66 | 0.98 |
| 5| 6318 | 59.02 | 19.78 | 1.05 |
| 6| 6554 | 74.01 | 24.97 | 1.22 |
| 7| 6698 | 83.09 | 27.94 | 1.32 |
| 8| 6830 | 91.50 | 30.76 | 1.41 |
| 9| 6933 | 96.48 | 32.47 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.44 | 14.43 | 0.84 |
| 10 | 30 | 1707 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2159 | 7121 | 96.44 | 36.92 | 1.51 |


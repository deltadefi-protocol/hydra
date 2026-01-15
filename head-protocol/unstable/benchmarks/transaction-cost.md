--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-15 16:10:02.613124928 UTC |
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
| 1| 5834 | 10.26 | 3.25 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7651 | 29.49 | 9.31 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.79 | 12.56 | 0.63 |
| 4 | 226 | 858 | 49.70 | 14.35 | 0.69 |
| 5 | 284 | 969 | 64.02 | 18.14 | 0.84 |
| 6 | 337 | 1081 | 73.40 | 20.84 | 0.94 |
| 7 | 395 | 1192 | 75.00 | 21.67 | 0.96 |
| 8 | 451 | 1303 | 84.59 | 24.27 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1985 | 26.55 | 9.00 | 0.52 |
| 3| 2172 | 28.85 | 10.31 | 0.55 |
| 5| 2459 | 31.95 | 12.51 | 0.61 |
| 10| 3275 | 42.79 | 18.89 | 0.78 |
| 39| 7482 | 97.49 | 53.39 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 811 | 25.39 | 8.78 | 0.45 |
| 3| 900 | 25.14 | 9.33 | 0.46 |
| 5| 1267 | 30.06 | 12.06 | 0.54 |
| 10| 2084 | 41.57 | 18.60 | 0.71 |
| 40| 6429 | 94.81 | 53.40 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.54 | 8.47 | 0.46 |
| 2| 733 | 30.27 | 9.86 | 0.50 |
| 3| 955 | 33.09 | 11.34 | 0.54 |
| 5| 1130 | 35.60 | 13.34 | 0.58 |
| 10| 2182 | 46.77 | 19.95 | 0.77 |
| 38| 6124 | 98.89 | 53.16 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 849 | 36.64 | 11.62 | 0.57 |
| 3| 954 | 37.95 | 12.63 | 0.59 |
| 5| 1263 | 42.64 | 15.28 | 0.66 |
| 10| 2086 | 54.47 | 21.93 | 0.84 |
| 29| 5001 | 98.88 | 46.97 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.00 | 9.07 | 0.69 |
| 2| 5905 | 32.64 | 10.90 | 0.75 |
| 3| 6039 | 43.79 | 14.69 | 0.88 |
| 4| 6240 | 55.01 | 18.52 | 1.00 |
| 5| 6246 | 55.57 | 18.58 | 1.01 |
| 6| 6746 | 76.97 | 26.00 | 1.26 |
| 7| 6664 | 80.00 | 26.95 | 1.28 |
| 8| 6865 | 88.66 | 29.82 | 1.38 |
| 9| 6832 | 91.27 | 30.63 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6004 | 29.28 | 10.41 | 0.73 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.68 | 37.80 | 1.53 |


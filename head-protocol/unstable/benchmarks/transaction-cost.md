--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-12 10:29:46.595242532 UTC |
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
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 171 | 747 | 43.79 | 12.52 | 0.63 |
| 4 | 227 | 858 | 52.73 | 15.10 | 0.72 |
| 5 | 282 | 974 | 62.91 | 17.94 | 0.83 |
| 6 | 338 | 1081 | 75.19 | 21.24 | 0.96 |
| 7 | 394 | 1192 | 74.30 | 21.37 | 0.96 |
| 8 | 450 | 1303 | 93.52 | 26.51 | 1.15 |
| 9 | 507 | 1414 | 98.99 | 28.23 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.29 | 7.69 | 0.48 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2083 | 27.32 | 9.86 | 0.53 |
| 5| 2400 | 31.05 | 12.25 | 0.60 |
| 10| 3131 | 41.16 | 18.39 | 0.75 |
| 41| 7698 | 98.53 | 55.03 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.38 | 0.42 |
| 2| 762 | 24.25 | 8.44 | 0.44 |
| 3| 939 | 26.84 | 9.83 | 0.48 |
| 5| 1252 | 31.23 | 12.38 | 0.55 |
| 10| 1937 | 38.52 | 17.75 | 0.67 |
| 40| 6492 | 96.20 | 53.78 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 854 | 29.90 | 9.82 | 0.50 |
| 3| 944 | 30.94 | 10.75 | 0.52 |
| 5| 1230 | 37.10 | 13.79 | 0.60 |
| 10| 2022 | 45.27 | 19.48 | 0.75 |
| 36| 6172 | 99.04 | 51.94 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 943 | 37.80 | 12.59 | 0.59 |
| 5| 1154 | 41.22 | 14.85 | 0.64 |
| 10| 2108 | 55.34 | 22.20 | 0.85 |
| 29| 4883 | 98.06 | 46.72 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.09 | 9.09 | 0.69 |
| 2| 5871 | 32.49 | 10.85 | 0.75 |
| 3| 6179 | 46.50 | 15.73 | 0.91 |
| 4| 6350 | 56.21 | 18.97 | 1.02 |
| 5| 6431 | 61.93 | 20.83 | 1.08 |
| 6| 6335 | 61.17 | 20.41 | 1.07 |
| 7| 6878 | 83.78 | 28.26 | 1.33 |
| 8| 6963 | 94.93 | 32.07 | 1.45 |
| 9| 6969 | 99.31 | 33.50 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |


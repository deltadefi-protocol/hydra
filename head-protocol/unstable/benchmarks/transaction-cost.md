--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-13 06:00:02.938936437 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.72 | 4.03 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 29.30 | 9.24 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.42 | 11.99 | 0.60 |
| 4 | 225 | 858 | 52.18 | 14.91 | 0.72 |
| 5 | 285 | 969 | 60.70 | 17.34 | 0.81 |
| 6 | 338 | 1081 | 75.06 | 21.17 | 0.96 |
| 7 | 393 | 1192 | 87.28 | 24.70 | 1.09 |
| 8 | 451 | 1307 | 99.03 | 27.88 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.00 | 7.62 | 0.48 |
| 2| 1883 | 24.80 | 8.49 | 0.49 |
| 3| 2013 | 25.95 | 9.49 | 0.52 |
| 5| 2275 | 28.93 | 11.66 | 0.57 |
| 10| 3082 | 39.74 | 18.01 | 0.74 |
| 41| 7603 | 95.96 | 54.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 857 | 24.07 | 9.03 | 0.45 |
| 5| 1279 | 31.23 | 12.38 | 0.55 |
| 10| 1830 | 36.50 | 17.17 | 0.65 |
| 41| 6752 | 99.36 | 55.36 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.87 | 10.05 | 0.51 |
| 3| 969 | 33.43 | 11.44 | 0.55 |
| 5| 1275 | 34.85 | 13.20 | 0.58 |
| 10| 2147 | 46.35 | 19.82 | 0.76 |
| 36| 5996 | 99.03 | 51.90 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 815 | 35.85 | 11.38 | 0.56 |
| 3| 954 | 37.91 | 12.62 | 0.59 |
| 5| 1348 | 43.35 | 15.49 | 0.67 |
| 10| 2088 | 54.50 | 21.95 | 0.84 |
| 29| 4721 | 96.39 | 46.21 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.05 | 9.07 | 0.69 |
| 2| 5866 | 34.92 | 11.66 | 0.77 |
| 3| 6041 | 43.71 | 14.68 | 0.88 |
| 4| 6275 | 54.95 | 18.46 | 1.00 |
| 5| 6377 | 62.42 | 20.99 | 1.09 |
| 6| 6568 | 71.46 | 24.04 | 1.19 |
| 7| 6763 | 85.38 | 28.87 | 1.35 |
| 8| 6936 | 94.57 | 31.90 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1711 | 6857 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2221 | 7160 | 99.82 | 38.19 | 1.55 |


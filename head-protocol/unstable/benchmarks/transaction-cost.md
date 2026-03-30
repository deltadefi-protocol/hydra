--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-30 09:24:37.15461215 UTC |
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
| 2| 6035 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.52 | 5.84 | 0.63 |
| 10| 7647 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 18.67 | 5.84 | 0.37 |
| 2 | 113 | 636 | 25.24 | 7.85 | 0.44 |
| 3 | 170 | 751 | 32.10 | 9.93 | 0.51 |
| 4 | 227 | 862 | 37.03 | 11.54 | 0.57 |
| 5 | 283 | 969 | 43.77 | 13.56 | 0.64 |
| 6 | 338 | 1081 | 53.63 | 16.38 | 0.75 |
| 7 | 393 | 1192 | 62.01 | 18.93 | 0.84 |
| 8 | 451 | 1303 | 65.25 | 20.10 | 0.88 |
| 9 | 505 | 1414 | 77.40 | 23.48 | 1.01 |
| 10 | 560 | 1525 | 89.63 | 27.11 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 18.05 | 6.29 | 0.42 |
| 2| 1943 | 19.19 | 7.29 | 0.44 |
| 3| 2136 | 20.91 | 8.48 | 0.47 |
| 5| 2480 | 24.77 | 10.97 | 0.54 |
| 10| 3116 | 29.94 | 15.85 | 0.64 |
| 50| 9107 | 86.65 | 59.37 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 16.78 | 6.02 | 0.36 |
| 2| 834 | 18.50 | 7.21 | 0.39 |
| 3| 970 | 19.33 | 8.08 | 0.41 |
| 5| 1142 | 20.80 | 9.86 | 0.44 |
| 10| 2010 | 30.39 | 16.08 | 0.60 |
| 50| 8586 | 92.80 | 61.30 | 1.72 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 710 | 20.69 | 6.94 | 0.40 |
| 2| 826 | 23.85 | 8.54 | 0.44 |
| 3| 983 | 25.20 | 9.60 | 0.47 |
| 5| 1317 | 26.95 | 11.49 | 0.51 |
| 10| 1941 | 32.87 | 16.56 | 0.62 |
| 50| 7878 | 93.58 | 61.30 | 1.69 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 25.34 | 8.25 | 0.45 |
| 2| 833 | 26.90 | 9.38 | 0.47 |
| 3| 991 | 28.98 | 10.67 | 0.50 |
| 5| 1289 | 32.61 | 13.09 | 0.56 |
| 10| 2159 | 42.62 | 19.42 | 0.73 |
| 42| 7054 | 99.56 | 57.48 | 1.68 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 23.77 | 8.34 | 0.66 |
| 2| 5820 | 27.62 | 9.61 | 0.70 |
| 3| 5950 | 33.25 | 11.60 | 0.76 |
| 4| 6152 | 43.68 | 15.39 | 0.88 |
| 5| 6391 | 53.47 | 18.91 | 1.00 |
| 6| 6562 | 63.51 | 22.47 | 1.11 |
| 7| 6853 | 74.21 | 26.27 | 1.24 |
| 8| 6827 | 83.43 | 29.20 | 1.34 |
| 9| 6969 | 84.39 | 29.87 | 1.35 |
| 10| 7083 | 93.24 | 33.07 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 16.41 | 5.68 | 0.58 |
| 10 | 1 | 57 | 5868 | 18.22 | 6.44 | 0.60 |
| 10 | 10 | 568 | 6172 | 35.47 | 13.57 | 0.81 |
| 10 | 20 | 1134 | 6508 | 52.27 | 20.64 | 1.01 |
| 10 | 40 | 2272 | 7189 | 90.81 | 36.52 | 1.46 |
| 10 | 45 | 2559 | 7360 | 99.10 | 40.02 | 1.56 |


--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-01-12 13:01:30.632622988 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 5.781586853 |
| _P99_ | 8.883881669999992ms |
| _P95_ | 6.9659329ms |
| _P50_ | 5.5941790000000005ms |
| _Number of Invalid txs_ | 0 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 34.205784542 |
| _P99_ | 50.85858807ms |
| _P95_ | 44.84818825ms |
| _P50_ | 33.231341ms |
| _Number of Invalid txs_ | 0 |
      

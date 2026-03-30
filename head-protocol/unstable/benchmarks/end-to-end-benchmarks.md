--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-03-30 07:37:43.500133133 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 4.935785376 |
| _P99_ | 9.575704759999999ms |
| _P95_ | 6.598710150000003ms |
| _P50_ | 4.636279ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 1 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 41.855629316 |
| _P99_ | 62.42307274999998ms |
| _P95_ | 57.16589269999999ms |
| _P50_ | 40.963102ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 3 |
      

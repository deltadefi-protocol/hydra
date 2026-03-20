--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-03-20 06:08:24.726334627 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 5.731767733 |
| _P99_ | 7.859183859999991ms |
| _P95_ | 7.081322600000001ms |
| _P50_ | 5.5262605ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 1 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 41.045114181 |
| _P99_ | 67.39277589999999ms |
| _P95_ | 58.91529479999999ms |
| _P50_ | 40.166362500000005ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 3 |
      

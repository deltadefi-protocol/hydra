--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-03-23 10:31:25.497331444 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 4.725296600 |
| _P99_ | 6.2708346299999995ms |
| _P95_ | 5.8133664ms |
| _P50_ | 4.5683229999999995ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 1 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 27.932997248 |
| _P99_ | 42.87803251ms |
| _P95_ | 37.496969299999996ms |
| _P50_ | 26.617825500000002ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 3 |
      

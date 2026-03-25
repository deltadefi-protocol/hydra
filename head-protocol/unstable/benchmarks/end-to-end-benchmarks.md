--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-03-25 04:17:12.376643268 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 5.826088306 |
| _P99_ | 7.947168659999992ms |
| _P95_ | 7.095959250000001ms |
| _P50_ | 5.6333ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 1 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 36.479034048 |
| _P99_ | 66.26831419999998ms |
| _P95_ | 55.886125449999994ms |
| _P50_ | 34.233638ms |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 3 |
      

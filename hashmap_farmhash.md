```bash
Running ./build-release/build_subfolder/performance/jrm-hashmap_farmhash
Run on (2 X 2300.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.10, 0.06, 0.01
--------------------------------------------------------------------
Benchmark                          Time             CPU   Iterations
--------------------------------------------------------------------
BM_tsl_hopscotch_native         11.6 ns         11.6 ns     60546922
BM_tsl_hopscotch_farmhash       14.4 ns         14.4 ns     48839236
```

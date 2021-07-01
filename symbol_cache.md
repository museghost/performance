```bash
Running ./build-release/build_subfolder/performance/traderpp-symbol_cache
Run on (2 X 2300.08 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.29, 0.55, 0.69
-------------------------------------------------------------------------
Benchmark                               Time             CPU   Iterations
-------------------------------------------------------------------------
BM_global_symbol_cache               18.1 ns         18.1 ns     38768260
BM_global_symbol_cache_reverse       10.4 ns         10.4 ns     66888858
BM_symbol_cache                      18.0 ns         18.0 ns     38913760
BM_symbol_cache_reverse              10.4 ns         10.4 ns     67162351
```

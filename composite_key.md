* just add up


```bash
Running ./build-release/build_subfolder/performance/jrm-composite-key
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 0.12, 0.13, 0.14
--------------------------------------------------------------------------------
Benchmark                                      Time             CPU   Iterations
--------------------------------------------------------------------------------
BM_find_composite_key_hopscotch_map/0       15.1 ns         15.1 ns     46220811
BM_mp_inplace_format_to_n/0                 64.3 ns         64.3 ns     10931943
BM_ticker_memcpy/0                          4.47 ns         4.47 ns    156397748
BM_ticker_assign/0                          4.47 ns         4.47 ns    156692124
```

* quasar's hash_combine x 3

```bash
Running ./build-release/build_subfolder/performance/jrm-composite-key
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 1.27, 0.96, 0.50
--------------------------------------------------------------------------------
Benchmark                                      Time             CPU   Iterations
--------------------------------------------------------------------------------
BM_find_composite_key_hopscotch_map/0       17.7 ns         17.7 ns     39631723
BM_mp_inplace_format_to_n/0                 64.1 ns         64.1 ns     10923187
BM_ticker_memcpy/0                          4.47 ns         4.47 ns    156626199
BM_ticker_assign/0                          4.47 ns         4.47 ns    156636964
```

* std::memcmp with lhr.size() and quasar's hash_combine x 3

```bash
Running ./build-release/build_subfolder/performance/jrm-composite-key
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 0.16, 0.50, 0.52
--------------------------------------------------------------------------------
Benchmark                                      Time             CPU   Iterations
--------------------------------------------------------------------------------
BM_find_composite_key_hopscotch_map/0       22.5 ns         22.3 ns     31297900
BM_mp_inplace_format_to_n/0                 63.9 ns         63.9 ns     10961508
BM_ticker_memcpy/0                          4.49 ns         4.48 ns    156425803
BM_ticker_assign/0                          4.48 ns         4.48 ns    156409899
```

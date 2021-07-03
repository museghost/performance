```bash
Running ./build-release/build_subfolder/performance/jrm-hashmap
Run on (2 X 2300.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.00, 0.00, 0.00
--------------------------------------------------------------------------
Benchmark                                Time             CPU   Iterations
--------------------------------------------------------------------------
BM_for_range_bypass_key_int64_t       3942 ns         3942 ns       137486
BM_for_range_key_classA              11609 ns        11607 ns        59612
```

```bash
Running ./build-release/build_subfolder/performance/jrm-hashmap
Run on (2 X 2300.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.17, 0.07, 0.02
--------------------------------------------------------------------------
Benchmark                                Time             CPU   Iterations
--------------------------------------------------------------------------
BM_lookup_key_int64_t                 2.31 ns         2.31 ns    303327270
BM_lookup_key_bypass_int64_t          2.27 ns         2.27 ns    307806674
BM_for_range_bypass_key_int64_t      10128 ns        10128 ns        69960
BM_for_range_key_classA               4421 ns         4421 ns       149192
```

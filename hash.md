```bash
Running ./build-release/build_subfolder/performance/jrm-hashing
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
BM_xxh64                              17.0 ns         17.0 ns     41780366
BM_farmhash_64                        13.1 ns         13.1 ns     53537228
BM_std_hash                           11.2 ns         11.2 ns     62610417
BM_string_hash_fmt_buffer             98.0 ns         98.0 ns      7156342
BM_string_hash_fmt_buffer_clear       96.7 ns         96.7 ns      7246773
BM_string_hash_fmt                     147 ns          147 ns      4774772
```

```bash
Running ./build-release/build_subfolder/performance/jrm-hashing
Run on (2 X 2300.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.15, 0.05, 0.01
--------------------------------------------------------------------------
Benchmark                                Time             CPU   Iterations
--------------------------------------------------------------------------
BM_xxh64                              16.8 ns         16.8 ns     41781667
BM_farmhash_64                        10.4 ns         10.4 ns     67130855
BM_std_hash                           11.2 ns         11.2 ns     62581514
BM_string_hash_fmt_buffer             99.2 ns         99.2 ns      7062569
BM_string_hash_fmt_buffer_clear       97.8 ns         97.8 ns      7162473
BM_string_hash_fmt                     147 ns          147 ns      4778990
BM_string_hash_fmt_move                150 ns          150 ns      4695353
```



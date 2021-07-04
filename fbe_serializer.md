```bash
Running ./build-release/build_subfolder/performance/traderpp-serialization
Run on (2 X 2300.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.01, 0.06, 0.08
-------------------------------------------------------------------
Benchmark                         Time             CPU   Iterations
-------------------------------------------------------------------
BM_encode_fbe_char_array       75.6 ns         75.6 ns      9337286
BM_decode_fbe_char_array       44.8 ns         44.8 ns     15642657
BM_encode_fbe_string           24.5 ns         24.5 ns     26475824
BM_decode_fbe_string           19.0 ns         19.0 ns     36764479
```

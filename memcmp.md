* mp::inplace_string<8>;


```bash
2021-12-25T14:37:25+00:00
Running ./build-release/build_subfolder/performance/jrm-memcmp
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 0.01, 0.23, 0.26
----------------------------------------------------------------
Benchmark                      Time             CPU   Iterations
----------------------------------------------------------------
BM_inplace_string_cmp       4.51 ns         4.51 ns    153377650
BM_int64_cmp               0.780 ns        0.780 ns    897398713
BM_int16_cmp               0.753 ns        0.753 ns    932863021
```

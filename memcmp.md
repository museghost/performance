* mp::inplace_string<8>;
* mp::inplace_string<16>;


```bash
2021-12-25T14:41:02+00:00
Running ./build-release/build_subfolder/performance/jrm-memcmp
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 0.37, 0.27, 0.27
------------------------------------------------------------------
Benchmark                        Time             CPU   Iterations
------------------------------------------------------------------
BM_inplace_string8_cmp        5.22 ns         5.22 ns    134357645
BM_inplace_string16_cmp       4.53 ns         4.53 ns    154730190
BM_int64_cmp                 0.754 ns        0.754 ns    929530895
BM_int16_cmp                 0.761 ns        0.761 ns    907576847
```

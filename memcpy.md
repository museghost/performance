```bash
2021-10-24T07:39:13+00:00
Running ./build-release/build_subfolder/performance/jrm-memcpy
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.45, 0.21, 0.10
--------------------------------------------------------------------------
Benchmark                Time             CPU   Iterations UserCounters...
--------------------------------------------------------------------------
BM_memcpy/32          4.10 ns         4.10 ns    170857988 bytes_per_second=7.27697G/s
BM_memcpy/64          4.47 ns         4.47 ns    156707426 bytes_per_second=13.3392G/s
BM_memcpy/128         6.33 ns         6.33 ns    110519376 bytes_per_second=18.8357G/s
BM_memcpy/256         20.3 ns         20.3 ns     34503945 bytes_per_second=11.7467G/s
BM_memcpy/512         8.93 ns         8.93 ns     78337135 bytes_per_second=53.3847G/s
BM_memcpy/1024        20.0 ns         20.0 ns     35046490 bytes_per_second=47.6984G/s
BM_memcpy/4096         105 ns          105 ns      6641192 bytes_per_second=36.1966G/s
BM_memcpy/8192         189 ns          189 ns      3700862 bytes_per_second=40.3315G/s
BM_memmove/32         3.73 ns         3.72 ns    188074711 bytes_per_second=8.00686G/s
BM_memmove/64         6.55 ns         6.55 ns    156495943 bytes_per_second=9.10624G/s
BM_memmove/128        6.33 ns         6.33 ns    110532573 bytes_per_second=18.8253G/s
BM_memmove/256        6.70 ns         6.70 ns    104473988 bytes_per_second=35.5594G/s
BM_memmove/512        8.94 ns         8.94 ns     78350238 bytes_per_second=53.3584G/s
BM_memmove/1024       20.0 ns         20.0 ns     35033526 bytes_per_second=47.7029G/s
BM_memmove/4096        105 ns          105 ns      6631717 bytes_per_second=36.1936G/s
BM_memmove/8192        189 ns          189 ns      3699970 bytes_per_second=40.301G/s
```

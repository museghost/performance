```bash
Running ./build-release/build_subfolder/performance/jrm-memcpy
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.07, 0.02, 0.00
--------------------------------------------------------------------------
Benchmark                Time             CPU   Iterations UserCounters...
--------------------------------------------------------------------------
BM_memcpy/32          4.10 ns         4.10 ns    170933012 bytes_per_second=7.27212G/s
BM_memcpy/64          4.47 ns         4.47 ns    156713091 bytes_per_second=13.3375G/s
BM_memcpy/128         6.34 ns         6.34 ns    110620313 bytes_per_second=18.8169G/s
BM_memcpy/256         20.3 ns         20.3 ns     34515931 bytes_per_second=11.7534G/s
BM_memcpy/512         8.94 ns         8.94 ns     78338480 bytes_per_second=53.3652G/s
BM_memcpy/1024        18.0 ns         18.0 ns     38856639 bytes_per_second=52.9801G/s
BM_memcpy/8192         709 ns          709 ns       988843 bytes_per_second=10.7667G/s
BM_memmove/32         3.72 ns         3.72 ns    188035629 bytes_per_second=8.00132G/s
BM_memmove/64         4.47 ns         4.47 ns    156712436 bytes_per_second=13.3437G/s
BM_memmove/128        6.33 ns         6.33 ns    110627569 bytes_per_second=18.8215G/s
BM_memmove/256        6.70 ns         6.70 ns    104482332 bytes_per_second=35.5798G/s
BM_memmove/512        8.94 ns         8.94 ns     78379200 bytes_per_second=53.3642G/s
BM_memmove/1024       18.0 ns         18.0 ns     38901422 bytes_per_second=52.969G/s
BM_memmove/8192        710 ns          710 ns       988530 bytes_per_second=10.7488G/s
```

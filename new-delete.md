# mimalloc 1.7.2 (256 bytes)

```bash
2021-11-21T04:58:20+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_mimalloc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.84, 0.65, 0.29
-----------------------------------------------------------------
Benchmark                       Time             CPU   Iterations
-----------------------------------------------------------------
BM_allocation_mimalloc       45.3 ns         45.3 ns     15449613
```

# libstdc++ (256 bytes, ubuntu 16.04, gcc-8.2)

```bash
ubuntu@ap-kr-dev-x008:~/project/jrm$ ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
2021-11-21T05:01:01+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.40, 0.48, 0.28
----------------------------------------------------------------
Benchmark                      Time             CPU   Iterations
----------------------------------------------------------------
BM_allocation_libstdc        116 ns          116 ns      6039887
```

# mimalloc 1.7.2 

## 128 bytes

```bash
ubuntu@ap-kr-dev-x008:~/project/jrm$ ./build-release/build_subfolder/performance/jrm-new_delete_mimalloc
2021-11-21T05:24:23+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_mimalloc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.45, 0.18, 0.12
-----------------------------------------------------------------
Benchmark                       Time             CPU   Iterations
-----------------------------------------------------------------
BM_allocation_mimalloc       36.2 ns         36.2 ns     19320588
```

## 256 bytes

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

## 512 bytes

```bash
ubuntu@ap-kr-dev-x008:~/project/jrm$ ./build-release/build_subfolder/performance/jrm-new_delete_mimalloc
2021-11-21T05:22:08+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_mimalloc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.26, 0.12, 0.10
-----------------------------------------------------------------
Benchmark                       Time             CPU   Iterations
-----------------------------------------------------------------
BM_allocation_mimalloc       58.6 ns         58.6 ns     11952134
```

# libstdc++ (ubuntu 16.04, gcc-8.2)

## 128 bytes

```bash
ubuntu@ap-kr-dev-x008:~/project/jrm$ ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
2021-11-21T05:24:16+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.40, 0.17, 0.11
----------------------------------------------------------------
Benchmark                      Time             CPU   Iterations
----------------------------------------------------------------
BM_allocation_libstdc       97.9 ns         97.9 ns      7141822
```

## 256 bytes
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

## 512 bytes

```bash
ubuntu@ap-kr-dev-x008:~/project/jrm$ ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
2021-11-21T05:22:16+00:00
Running ./build-release/build_subfolder/performance/jrm-new_delete_libstdc
Run on (2 X 2300.06 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 46080 KiB (x1)
Load Average: 0.30, 0.13, 0.10
----------------------------------------------------------------
Benchmark                      Time             CPU   Iterations
----------------------------------------------------------------
BM_allocation_libstdc        128 ns          128 ns      5482626
```

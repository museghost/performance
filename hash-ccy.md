* using 8ytes only

```c++
std::string title{"Xa8FF393"};
```

```bash
Running ./build-release/build_subfolder/performance/jrm-hashing-ccy
Run on (2 X 2400.05 MHz CPU s)
CPU Caches:
  L1 Data 32 KiB (x2)
  L1 Instruction 32 KiB (x2)
  L2 Unified 256 KiB (x2)
  L3 Unified 30720 KiB (x1)
Load Average: 0.19, 0.13, 0.05
---------------------------------------------------------
Benchmark               Time             CPU   Iterations
---------------------------------------------------------
BM_xxh64             6.34 ns         6.34 ns    110334105
BM_farmhash_64       7.64 ns         7.64 ns     92763513
BM_std_hash          4.85 ns         4.85 ns    144275725
```


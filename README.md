# Benchmarks of [QuantumClifford.jl](https://github.com/QuantumSavory/QuantumClifford.jl)

Overall performance (mean log of execution time of all benchmarks):

![](./benchmarks0.png)

- the column gives how many threads were used;
- the color gives the julia version;
- the x axis is the QuantumClifford verion;
- the y axis is the mean-log-time (lower is better; one unit represents speedup by a factor of 10; log scale)

### Execution time benchmarks

<details>
<summary>
Benchmark results at finer granularity (groups) 
</summary>
<img src="./benchmarks1.png">
</details>

<details>
<summary>
Benchmark results at even finer granularity (sub-groups) 
</summary>
<img src="./benchmarks2.png">
</details>

<details>
<summary>
All benchmark results
</summary>
The y axis is time in nano-seconds. Lower is better.<br>
<img src="./benchmarks3.png">
</details>

### Allocation benchmarks

<details>
<summary>
Allocation benchmarks
</summary>
The y axis is number of allocations. Lower is better.<br>
<img src="./benchmarks3_allocs.png">
</details>

### TTFX benchmarks

Time to import, time to run a typical task, and their sum total.<br>
<img src="./benchmarks_ttfx.png">

The [benchmarking code](https://github.com/QuantumSavory/QuantumClifford.jl/blob/master/benchmark/benchmarks.jl)
and the [plotting routines](https://github.com/QuantumSavory/QuantumClifford.jl/blob/master/benchmark/plotbenchmarks.jl)
are available in the [QuantumClifford.jl repository](https://github.com/QuantumSavory/QuantumClifford.jl/blob/master/benchmark/plotbenchmarks.jl).

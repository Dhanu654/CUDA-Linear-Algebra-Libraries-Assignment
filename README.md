# CUDA-Linear-Algebra-Libraries-Assignment
### Aim
To implement and analyze linear algebra operations using CUDA with different memory models (global, shared, constant, and register memory) to optimize GPU performance.

### Procedure
Developed CUDA kernels for vector and matrix operations using various memory types.

Modified host code to allocate and transfer data appropriately.

Measured execution times for each memory model variant.

Followed Google C++ Style Guide and added command-line arguments for flexible execution.

Tested on large input data to evaluate performance and correctness.
### Outcome
This project highlighted the performance differences between CUDA memory types. Using shared memory led to faster execution by reducing access latency, while constant and register memory proved effective in cases with repeated data usage. The implementation also reinforced best practices in CUDA programming such as efficient memory management and synchronization. Overall, the project provided practical insights into GPU optimization techniques for linear algebra workloads.



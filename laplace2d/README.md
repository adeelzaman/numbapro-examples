# Laplace 2D 

Implements jacobian relaxation on 4096x4096 matrices.

- laplace2d.py: naive implementation; very slow.
- laplace2d-numba.py: numba implementation.
- laplace2d-numbapro-gpu.py: naive numbapro cuda implementation.
- laplace2d-numbapro-gpu-smem.py: shared memory version of cuda implementation.
- laplace2d-numbapro-gpu-improve.py: shared memory + inline reduction on cuda.

Each script is runnable.

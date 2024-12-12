# HPC and optimization seminar

We explore how to use Scalene, a profiler that provides insights into the resource usage of our jobs. We explain how to use SLURM on the Proteus cluster to efficiently submit jobs to different nodes and GPUs. Finally, we explain how to use an optimized high-performance quantum circuit simulator, QSim, on a heterogenous cluster on multi-CPUs and GPUs.

## 1. Scalene

Repository: https://github.com/plasma-umass/scalene

Scalene is a high-performance CPU, GPU and memory profiler for Python. You can use Scalene at the command line of your terminal (recommended), or as a Visual Studio Code extension. See more info in [scalene_command_line](scalene_command_line.md).

## 2. Slurm

The scheduler decides where and when jobs are executed. Slurm is the scheduler used in PROTEUS. The job parameters are specified through a job description file or directly from the command line, such as the executable name and working directory, hardware requirements (number of processors, required memory and disk space, etc.), and the maximum execution time.

PROTEUS user manual: https://proteus.ugr.es/docs/manual-uso/

## 3. Qsim

[Qsim exemple](Qsim_seminar.ipynb)

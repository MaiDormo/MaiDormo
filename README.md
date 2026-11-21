# Elia Gatti

M.S. Computer Science at the University of Trento (expected March 2027).
GPU, HPC and distributed systems. EU citizen, available March 2027.

## Thesis (in progress)

**dist-patoh**: a distributed multi-GPU hypergraph partitioner in C++20, CUDA and MPI. It splits
massive, irregular sparse graphs across GPUs while balancing compute and minimising cross-node
communication. The multilevel pipeline covers parallel coarsening, recursive k-way partitioning
and local refinement. Code private during thesis writing; public release after submission.

## Recently

Software Engineer Intern at [Bitmovin](https://bitmovin.com) (Jun–Sep 2026). Co-built
[KAIROS](https://kairosapp.tech), AI highlight detection and segmentation for sports, news and
podcasts: live/VOD, sport understanding, orchestration, and a public MCP API.

## Work worth reading

- [cuda-SpMV](https://github.com/MaiDormo/cuda-SpMV): hybrid adaptive A30 kernel combining
  thread-per-row and warp-per-row CSR; diagnosed the overscheduling failure that motivated the
  thesis
- [parallel-mst](https://github.com/MaiDormo/parallel-mst): MPI+OpenMP Borůvka MST for dense graphs
  with a flat symmetric adjacency matrix and mmap I/O; measured 2-32 rank scaling on one 64-core node
- [distributed-storage-system](https://github.com/MaiDormo/distributed-storage-system):
  Akka/Java 21 key-value store with consistent hashing, N/W/R quorums and node-failure recovery
- [DWT-SVD-watermarking](https://github.com/MaiDormo/DWT-SVD-watermarking): 1st of 11 teams,
  CTM Challenge 2025
- [mpeg-dash-analysis](https://github.com/MaiDormo/mpeg-dash-analysis): bachelor's thesis:
  MPEG-DASH under simulated (Mininet) and real (AWS) networks

## Tools

C, C++17/20, CUDA, Go, Python, Java | MPI, OpenMP, Slurm, CMake, cuSPARSE | Linux, Docker, Terraform,
GCP, PostgreSQL, Git

## Contact

[maidormo.github.io](https://maidormo.github.io) | [LinkedIn](https://www.linkedin.com/in/elia-gatti) | elia.gatti01@gmail.com

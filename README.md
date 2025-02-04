# CUDA MODE Resource Stream

Here you find a collection of CUDA related material (books, papers, blog-post, youtube videos, tweets, implementations etc.). We also collect information to higher level tools for performance optimization and kernel development like [Triton](https://triton-lang.org) and `torch.compile()` ... whatever makes the GPUs go brrrr. 

You know a great resource we should add? Please see [How to contribute](#how-to-contribute).

## 1st Contact with CUDA
- [An Easy Introduction to CUDA C and C++](https://developer.nvidia.com/blog/easy-introduction-cuda-c-and-c/)
- [CUDA Toolkit Documentation ](https://docs.nvidia.com/cuda/)
- Basic terminology: Thread block, Warp, Streaming Multiprocessor: [Wiki: Thread Block](https://en.wikipedia.org/wiki/Thread_block_(CUDA_programming)), [A tour of CUDA](https://tbetcke.github.io/hpc_lecture_notes/cuda_introduction.html)
- [GPU Performance Background User's Guide](https://docs.nvidia.com/deeplearning/performance/dl-performance-gpu-background/index.html)


## Papers, Case Studies
- [A Case Study in CUDA Kernel Fusion: Implementing FlashAttention-2 on NVIDIA Hopper Architecture using the CUTLASS Library](https://arxiv.org/abs/2312.11918)
- [How to Optimize a CUDA Matmul Kernel for cuBLAS-like Performance: a Worklog](https://siboehm.com/articles/22/CUDA-MMM)


## Books
- [Programming Massively Parallel Processors: A Hands-on Approach](https://www.amazon.com/Programming-Massively-Parallel-Processors-Hands/dp/0323912311)


## Tri Dao Fan Section
- [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention)
- [state-spaces/mamba](https://github.com/state-spaces/mamba)


## Practice
- [Sasha Rush's GPU Puzzles](https://github.com/srush/GPU-Puzzles)


## PyTorch Highlights
- [Accelerating Generative AI with PyTorch: Segment Anything, Fast](https://pytorch.org/blog/accelerating-generative-ai/)
- [Accelerating Generative AI with PyTorch II: GPT, Fast](https://pytorch.org/blog/accelerating-generative-ai-2/)
- [PyTorch Compiler Troubleshooting](https://github.com/pytorch/pytorch/blob/main/docs/source/torch.compiler_troubleshooting.rst)


## Code / Libs
- [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass)


## Essentials
- [Triton compiler tutorials](https://triton-lang.org/main/getting-started/tutorials/index.html)
- [CUDA C++ Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)
- [pybind11 documentation](https://pybind11.readthedocs.io/en/stable/)
- [NVIDIA Tensor Core Programming](https://leimao.github.io/blog/NVIDIA-Tensor-Core-Programming/)
- [GPU Programming: When, Why and How?](https://enccs.github.io/gpu-programming/#)
- [How CUDA Programming Works | GTC 2022](https://youtu.be/n6M8R8-PlnE?si=cJ4dWtpYaPoIuJ0q)


# News
- [SemiAnalysis](https://www.semianalysis.com/)


## Hardware Architecture
- [NVIDIA H100 Whitepaper](https://resources.nvidia.com/en-us-tensor-core/gtc22-whitepaper-hopper)
- [NVIDIA GH200 Whitepaper](https://resources.nvidia.com/en-us-grace-cpu/nvidia-grace-hopper)
- [AMD CDNA 2 (MI200) Whitepaper](https://www.amd.com/content/dam/amd/en/documents/instinct-business-docs/white-papers/amd-cdna2-white-paper.pdf)
- [AMD MI300X Data Sheet](https://www.amd.com/content/dam/amd/en/documents/instinct-tech-docs/data-sheets/amd-instinct-mi300x-data-sheet.pdf)


## How to contribute
To share interesting CUDA related links please create a pull request for this file. See [editing files](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files) in the github documentation.

Or contact us on the **CUDA MODE** discord server: invitation link TBD

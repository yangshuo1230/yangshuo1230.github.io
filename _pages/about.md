---
permalink: /
title: "Shuo Yang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am Shuo Yang, an undergraduate student in Microelectronics at the School of Integrated Circuits, Shanghai Jiao Tong University, and currently a research assistant at the ICRG Lab.

My research interests lie in high-performance computing architectures, near-memory computing, and hardware-software co-design. I am particularly interested in architecture optimization for RAG systems, long-context inference, and vector retrieval workloads, with the goal of improving throughput, energy efficiency, and scalability through algorithm-hardware co-design.

Education
======
- Shanghai Jiao Tong University, B.Eng. in Microelectronics
- 2023.09 - 2028.06 (expected)
- GPA: 4.07 / 4.30
- Rank: 1 / 89

Honors and Awards
======
- National Scholarship (top 2%)
- Shanghai Jiao Tong University A Scholarship
- Merit Student of Shanghai Jiao Tong University
- First Prize, Shandong Province, National Olympiad in Informatics, 2021

Selected Achievements
======
- ISCA 2026 (accepted): NasZip, an NDP-accelerated approximate nearest neighbor retrieval framework, co-first author
- ICCAD (under review): EstAtt, linear-complexity attention via sign-based estimation

Research Experience
======
NasZip: NDP-Accelerated ANNS for RAG Systems
- 2025.03 - 2026.03
- ICRG Lab & Lenovo
- Led the design of a hardware-software co-optimized framework for ANNS retrieval bottlenecks in RAG systems, introducing a statistical-PCA-based feature-level early-exit method and dynamic floating-point compression that reduced memory traffic by 50% without recall loss.
- Designed data-aware neighbor mapping and a local caching mechanism to remove cross-channel communication overhead and improve subchannel parallelism by 3.2x.
- Built an end-to-end prototype that achieved 10.6x speedup over a CPU baseline on six benchmark datasets, outperformed the SOTA NDP baseline ANSMET by 1.54x, and improved energy efficiency by 18.5% over NVIDIA A100.

EstAtt: Linear-Complexity Attention via Sign-Based Estimation
- 2025.09 - present
- ICRG Lab
- Under review at ICCAD.
- Proposed a sign-driven semantic distance estimation method with LUT-based fast filtering, reducing attention complexity from O(N^2) to linear.
- Designed an NDP-oriented VPE architecture with sign/value-separated mapping, reducing communication overhead by 60%.
- Demonstrated support for 1M-token long-context inference, with 3x higher decoding throughput than a GPU baseline and less than 1% accuracy loss.

NeuraLock: IP-Protection for Edge DNN via Model Locking
- 2025.11 - present
- ICRG Lab
- Built a model-locking protection framework that uses parameter-bit locking and authorization keys so unauthorized devices only produce invalid outputs.
- Developed a lightweight hardware unlocking module with a homomorphic GEMM core and a PUF-based key translator, adding only 10.8% LUT overhead with zero inference latency loss.

Technical Skills
======
- Architecture: CPU/GPU/NDP architecture design, memory hierarchy optimization, dataflow scheduling, pipeline design, RTL development, and performance modeling.
- Algorithm-hardware co-design: ANNS, attention sparsification, quantization and compression, and mapping algorithmic properties to hardware primitives.
- Development stack: Python, C++, Verilog, Chisel, PyTorch, CUDA, Triton, Git, Linux, Cadence, and Vivado.
- Domain knowledge: LLM inference, RAG systems, KV cache management, HNSW, and GANNS-style graph retrieval algorithms.

Contact
======
- Email: yangshuo1230@sjtu.edu.cn
- GitHub: [@yangshuo1230](https://github.com/yangshuo1230)
- Phone: (+86) 176-6261-8985

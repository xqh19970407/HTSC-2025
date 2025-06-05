# HTSC-2025
We present HTSC-2025, an open-source benchmark of ambient-pressure high-Tc superconductors predicted from 2023–2025, designed to standardize AI evaluation and accelerate physics-informed superconductor discovery.

### Crystalline materials included in the HTSC-2025 benchmark

| Material Class     | Avg Tc (K) | Max Tc Formula     | Space Group  | Max Tc (K) | Count |
|--------------------|------------|---------------------|---------------|------------|--------|
| X2YH6              | 55.4       | Mg2IrH6             | Fm-3m         | 160        | 19     |
| LaH10              | 53.0       | KPbB6C6             | Pm-3          | 88         | 12     |
| X2YMH6             | 35.5       | Na2LiAgH6           | Fm-3m         | 86         | 23     |
| MXH3               | 35.3       | SrAuH3              | Pm-3m         | 132        | 15     |
| M3XH8              | 20.4       | Mg3OsH8             | Pm-3m         | 73         | 18     |
| Others             | 7.9        | MgB2                | P63/mmc       | 39.0       | 53     |
| **Total**          | **27.3**   | **Mg2IrH6**         | **Fm-3m**     | **160**    | **140** |

We were invited by Hugging Face to share our work on their platform. The paper is now available on the Hugging Face Papers website: [https://huggingface.co/papers/2506.03837](https://huggingface.co/papers/2506.03837).
Additionally, the **HTSC-2025** benchmark dataset can be conveniently accessed via the Hugging Face Datasets Hub: [https://huggingface.co/datasets/xiao-qi/HTSC-2025](https://huggingface.co/datasets/xiao-qi/HTSC-2025).

### Citation

If you use the HTSC-2025 dataset in your research, please cite our work:

```bibtex
@misc{han2025htsc2025benchmarkdatasetambientpressure,
  title={HTSC-2025: A Benchmark Dataset of Ambient-Pressure High-Temperature Superconductors for AI-Driven Critical Temperature Prediction}, 
  author={Xiao-Qi Han and Ze-Feng Gao and Xin-De Wang and Zhenfeng Ouyang and Peng-Jie Guo and Zhong-Yi Lu},
  year={2025},
  eprint={2506.03837},
  archivePrefix={arXiv},
  primaryClass={cond-mat.supr-con},
  url={https://arxiv.org/abs/2506.03837}, 
}


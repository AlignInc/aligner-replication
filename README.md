# Aligner-Reproduced

[Align-Inc](https://www.alignllm.com) uses the *Aligner* technology developed by Peking University, training a lightweight Aligner based on Gemma-2B, and applying it to our specific business practices. Notably, the Aligner we replicated achieved marvelous results on AlpacaEval. See below for details.

## Results
<div align=center>
<img src="https://github.com/AlignInc/aligner-replication/blob/master/aligner.jpg" width="70%">
</div>


Using the techniques mentioned in the paper, we trained *Aligner* based on [Gemma-2B](https://huggingface.co/google/gemma-2b) and successfully improved the performance of [Qwen-72B-Chat](https://huggingface.co/Qwen/Qwen1.5-72B-Chat) and [Claude3-Opus](https://www.anthropic.com/news/claude-3-family) on [AlpacaEval](https://tatsu-lab.github.io/alpaca_eval/). After being corrected by our *Aligner* model, Qwen-72B-Chat's win rate rose to <span style="color: red;"> **31.77%** </span> and the LC win rate was enhanced to <span style="color: red;"> **36.72%** </span>, with its responses averaging <span style="color: red;"> **1812** </span> tokens, whereas the win rate of Claude3-Opus was enhanced to <span style="color: red;"> **34.46%** </span> and the LC win rate was enhanced to <span style="color: red;"> **41.82%** </span>, with an average response length of <span style="color: red;"> **1669** </span> tokens.

## Citing *Aligner*

This repository is **the reproduction of the paper** - [<em>Aligner</em>: Achieving Efficient Alignment through Weak-to-Strong Correction](https://arxiv.org/pdf/2402.02416.pdf). You can cite it in your publications if you find *Aligner* useful.


```bibtex
@article{ji2024aligner,
  title={Aligner: Achieving efficient alignment through weak-to-strong correction},
  author={Ji, Jiaming and Chen, Boyuan and Lou, Hantao and Hong, Donghai and Zhang, Borong and Pan, Xuehai and Dai, Juntao and Yang, Yaodong},
  journal={arXiv preprint arXiv:2402.02416},
  year={2024}
}
```

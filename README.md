# torch-models
Learning by implementing papers

# Basics
## Generative Models
- [Variational Autoencoder, 2013](https://arxiv.org/abs/1312.6114): With ELBO
- [Masked Autoregressive Flow, 2018](https://arxiv.org/abs/1705.07057)

### Transformer Models
- [GPT2, 2019](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
- [ColBERT, 2020](https://arxiv.org/abs/2004.12832)
- [Coconut](https://arxiv.org/pdf/2412.06769), [sample code](https://github.com/lucidrains/coconut-pytorch/blob/main/coconut_pytorch/coconut.py)
- Combine Whisper with Qwen 7b

## Reinforcement Learning
- Reinforce
- [On-policy DPO, Tulu 3](https://arxiv.org/pdf/2411.15124), [code](https://github.com/allenai/open-instruct)
- [Reinforcement on Verifiable Reward (RLVR), Tulu 3](https://arxiv.org/pdf/2411.15124), [code](https://github.com/allenai/open-instruct)
- [free process rewards without process labels](https://arxiv.org/pdf/2412.01981)

## ICL
- ICLR: [In-context Learning of Representations](https://arxiv.org/pdf/2501.00070)

## Training

### C/CUDA
- [llm.c](https://github.com/karpathy/llm.c/blob/master/train_gpt2.c)
- [llm.cu](https://github.com/karpathy/llm.c/blob/master/train_gpt2.cu)

### Distributed Computing
- [picotron](https://github.com/huggingface/picotron)

---

## Project Ideas
- Turn an LLM into a Speech to Speech Model
- Test Time Training
# Key-value memory in the brain

This is the official code repository for the paper:

[Key-value memory in the brain](https://arxiv.org/abs/2501.02950v1)

### Contents

This repository contains three notebooks we used to run the simulations and generate the figures presented in the paper.

* Figure 1A: [`2classes_key_value_optimization.ipynb`](https://github.com/kazuki-irie/kv-memory-brain/blob/master/2classes_key_value_optimization.ipynb)
* Figure 1B: [`3classes_key_value_optimization.ipynb`](https://github.com/kazuki-irie/kv-memory-brain/blob/master/3classes_key_value_optimization.ipynb)
* Figure 2: [`Forgetting_and_recovery.ipynb`](https://github.com/kazuki-irie/kv-memory-brain/blob/master/Forgetting_and_recovery.ipynb)

### Requirements

* We used the free version of Google Colab to run all the simulations.
* The "Forgetting and recovery" notebook used a T4 GPU (freely accessible on Google Colab, as of December 2024), while others used only a CPU.
* Our results were produced using: `Python 3.10.12` and `PyTorch 2.5.1+cu121`

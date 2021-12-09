# ml-and-math-in-for-nlp
An evolving notes on machine learning and mathematical techniques in and for Natural Language Processing.



## Collection of papers by topic


### Statistical Principle Based Learning

> density/distribution estimation over structures, generative story

- [Minimax and Neyman–Pearson Meta-Learning for Outlier Languages](https://aclanthology.org/2021.findings-acl.106.pdf), `Neyman-Pearson`

### Latent Variable Model and its Solution

- [Learning Opinion Summarizers by Selecting Informative Reviews](https://arxiv.org/pdf/2109.04325.pdf), Ivan Titov's group. `REINFORCE` `amortized varitional inference`
- [Sequence-to-Sequence Learning with Latent Neural Grammars](https://arxiv.org/abs/2109.01135), Yoon Kim. `likelihood bounding`
- [Structured Reordering for Modeling Latent Alignments in Sequence Transduction](https://arxiv.org/abs/2106.03257), Ivan Titov's group. `marginalization`


### Feature Selection

- [Rare Feature Selection in High Dimensions](https://arxiv.org/pdf/1803.06675.pdf), `lasso`


### Sampling and Search Techniques

- [Determinantal Beam Search](https://arxiv.org/abs/2106.07400), Ryan Cotterell's group. `beam search`
- [Mode recovery in neural autoregressive sequence modeling](https://aclanthology.org/2021.spnlp-1.5.pdf), Kyunghyun Cho's group. `sampling`
- [Parallel and Flexible Sampling from Autoregressive Models via Langevin Dynamics]()
- [Searching for More Efficient Dynamic Programs](https://arxiv.org/pdf/2109.06966.pdf), Jason Eisner et al. `dp`



### Information Theory

- [What Context Features Can Transformer Language Models Use?](https://arxiv.org/abs/2106.08367), Jacob Andreas's group. `V-information`
- [Conditional probing: measuring usable information beyond a baseline](https://arxiv.org/pdf/2109.09234.pdf), Percy Liang's group. `V-information`
- [On the Complexity and Typology of Inflectional Morphological Systems](https://arxiv.org/pdf/1807.02747.pdf), Ryan Cotterell. `complexity measure`
- [On Homophony and Renyi Entropy](https://arxiv.org/pdf/2109.13766.pdf), Ryan Cotterell et al. `entropy`


### Geometry

- [The Low-Dimensional Linear Geometry of Contextualized Word Representations](), Jacob Andreas's group.
- [On Isotropy Calibration of Transformers](https://arxiv.org/pdf/2109.13304.pdf), ETH's group.



### Discrete optimization

> submodular, Gumbel-Softmax

- [Towards Dynamic Computation Graphs via Sparse Latent Structure](https://arxiv.org/abs/1809.00653), `emnlp2018` [marginalize](https://vene.ro/talks/21-marginalize.pdf).
- [Differentiable Perturb-and-Parse: Semi-Supervised Parsing with a Structured Variational Autoencoder](https://arxiv.org/abs/1807.09875), `iclr2019`
- [Backpropagating through Structured Argmax using a SPIGOT](https://aclanthology.org/P18-1173/), `acl2018`
- [Implicit MLE: Backpropagating Through Discrete Exponential Family Distributions](https://arxiv.org/pdf/2106.01798.pdf), Oct. 27 2021. `nips2021` [code](https://github.com/uclnlp/torch-imle)
- [Argmax Flows and Multinomial Diffusion: Learning Categorical Distributions](https://arxiv.org/pdf/2102.05379.pdf), Oct. 22 2021.

### Learning Paradigms

#### Reinforcement Learning

- [Learning Natural Language Generation from Scratch](https://arxiv.org/pdf/2109.09371.pdf), DeepMind.
- [Batch size-invariance for policy optimization](https://arxiv.org/pdf/2110.00641.pdf), `ppo`.

# Summer 2023 Reading Group

## Goals. 
  1. create a strong background required for research in ML Efficiency
  2. Get aquanited with promising approaches for ML Efficiency
  3. Formulate new ideas to work on in Fall'23

## List of readings

|        **Paper**        | **Read by** | **Presenter** | **Presentation date** |
|:-----------------------:|:-----------:|:-------------:|:---------------------:|
| [High Dimensional Spaces](https://www.cs.cmu.edu/~venkatg/teaching/CStheory-infoage/chap1-high-dim-space.pdf) ( [slides](https://docs.google.com/presentation/d/1SR3UXdEe5lOt92YrFixN9HNsBYloNsoZigLBoe_zlCc/edit?usp=sharing) ) |     All     |  Aditya |          06/13/2023          |
|||||
| [Survey on Quantization methods](https://arxiv.org/pdf/2103.13630.pdf) ( [slides](https://docs.google.com/presentation/d/1P1saT0cNrDkpbGwzQKQZDF6jU9h0uhEK92P2wcMO2HM/edit?usp=sharing)) | Kevin, Aditya       | Kevin              |     06/20/2023  |
| [Transformer full stack optimization](https://arxiv.org/pdf/2302.14017.pdf) ( [slides](https://docs.google.com/presentation/d/1QYrTFgImQodIdMBzH_l5tIiyijYf68lXlVD6T-j-76M/edit?usp=sharing) ) | Ben, Gaurav             | Ben              |   06/20/2023 |
| [Survey on Model compression methods](https://ieeexplore.ieee.org/abstract/document/9043731) ( [slides](https://docs.google.com/presentation/d/1Z5BIwrF0vlWZKSt0iDdcYbSfr_ySxJ6aGqavJGUoWbM/edit?usp=sharing))| Apoorv             | Apoorv              |   06/20/2023 |
|||||
| LTH and follow ups ([D1](https://arxiv.org/abs/1803.03635), [D2](https://arxiv.org/pdf/1903.01611.pdf), [D3](https://arxiv.org/pdf/2009.08576.pdf))([slides](https://docs.google.com/presentation/d/1mpRZAj-AlJQCfFeN8L2-9TuZ3C13OUYtYOMw4WvnVxc/edit?usp=sharing))| Aditya | Aditya              |   06/27/2023 |
| [NLP+retrival : Prompt survey](https://dl.acm.org/doi/pdf/10.1145/3560815) ([slides](https://rice-my.sharepoint.com/:p:/g/personal/gg29_rice_edu/Eaci6xgwT-VBjQ0Ym4SKzbcBO4eUBWuc_qNqjLDjYMO_rw?e=gEBf5b))                       |  Gaurav           |   Gaurav            | 06/27/2023   |
| Distributed mean estimation ([slides](https://docs.google.com/presentation/d/1ondtXk95JLTL_hDF_oWRpm_ceoO-mLKAKgbeABK5ka0/edit?usp=sharing)) | Ben | Ben              |   07/05/2023 |
| Sparsity based efficiency in ML ([slides](https://docs.google.com/presentation/d/1zpDMFGuhKoGC7mktG0wbbOWb8H7yiuAbAyF6xqdzG4Y/edit?usp=sharing)) | Apoorv, Masa | Apoorv              |   07/11/2023 |
|  NLP+Retreival: RETRO([slides](https://docs.google.com/presentation/d/1NQCymCq4SwIyzbtet92QugfgVLZg5OrH/edit?usp=sharing&ouid=115359150026898235727&rtpof=true&sd=true))               |  Atishay, Jonah           |   Atishay            | 07/11/2023  |
| Efficient attention ([slides](https://docs.google.com/presentation/d/1aly0sMN2WxFLAGbD0eyjtP1HL-xCMjimk3LWFzfOYHQ/edit?usp=sharing))           |  Kevin           |   Kevin            | 07/14/2023  |
|  Pruning ( one shot pruning, layer collapse & IMP) ([slides](https://docs.google.com/presentation/d/1mpRZAj-AlJQCfFeN8L2-9TuZ3C13OUYtYOMw4WvnVxc/edit?usp=sharing), second half)           |  Aditya           |   Aditya            | 07/18/2023  |
|  Knowledge content of Language models ([slides-tba]())     |  Gaurav           |   Gaurav            | 07/18/2023  |
|  TBD (aditya is OOO)              |  Ben           |   Ben            | 07/25/2023  |
|  TBD (aditya is OOO)            |  Kevin           |   Kevin            | 07/25/2023  |
|  TBD            |  Atishay, Jonah           |   Atishay            | 08/01/2023  |
|  TBD            |  Apoorv, Masa           |   Apoorv            | 08/01/2023  |
|  Wrap up and next edition |  ---        |   Aditya          | 08/08/2023  |

## Themes (Ignore the order of papers)

## Surveys
1. Transformer full stack optimization &#x2705;
2. Survey on Quantization methods &#x2705;
3. Survey on Model compression methods &#x2705;
4. Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing &#x2705;

## A. Sparsity based efficiency in ML ( Dr. Chris Re's body of work )
1. 	Monarch: Expressive Structured Matrices for Efficient and Accurate Training
2. Pixelated Butterfly: Simple and Efficient Sparses Training for Neural Network Models 
3. Deja Vu: Contextual Sparsity for Efficient LLMs at Inference Time &#x2705;
4. Scatterbrain: Unifying Sparse and Low-rank Attention &#x2705;
5. Mongoose: A Learnable LSH Framework for Efficient Neural Network Training.

## B. Efficient Attention
1. FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness  &#x2705;
2. Efficiently Modeling Long Sequences with Structured State Spaces &#x2705;
3. Simple Hardware-Efficient Long Convolutions for Sequence Modeling.

## C. Distributed ML
1. THC: Accelerating Distributed Deep Learning Using Tensor Homomorphic Compression
2. Eden: Communication-efficient and robust distributed mean estimation for federated learning
3. QUICK-FL: Quick Unbiased Compression for Federated Learning
4. Drive: One-bit distributed mean estimation &#x2705;
5. Optimizing the communication-accuracy tradeoff in federated learning with Rate distortion theory &#x2705;

## D. Pruning
1. The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks &#x2705;
2. Stabilizing the Lottery Ticket Hypothesis / The Lottery Ticket Hypothesis at Scale &#x2705;
3. The Early Phase of Neural Network Training
4. Pruning Neural Networks at Initialization: Why are We Missing the Mark? &#x2705;
5. The Effect of Data Dimensionality on Neural Network Prunability
6. Pruning neural networks without any data by iteratively conserving synaptic flow &#x2705;
7. https://hanlab.mit.edu/files/course/slides/MIT-TinyML-Lec03-Pruning-I.pdf (only criteria) &#x2705;


## E. NLP + retreival 
1. Language Models as Knowledge Bases?  &#x2705;
2. How Much Knowledge Can You Pack Into the Parameters of a Language Model?  &#x2705;
3. Atlas: Few-shot Learning with Retrieval Augmented Language Models
4. RETRO Improving Language Models by Retrieving from Trillions of Tokens &#x2705;
5. REALM: Retrieval-Augmented Language Model Pre-Training
6. Language Models as Knowledge Bases? [1909.01066] Language Models as Knowledge Bases? (arxiv.org)
7. Transformer Memory as a Differentiable Search Index
8. QUANTIFYING MEMORIZATION ACROSS NEURAL LANGUAGE MODELS  &#x2705;
9. Extracting Training Data from Large Language Models Extracting Training Data from Large Language Models  &#x2705;
10. GENERALIZATION THROUGH MEMORIZATION: NEAREST NEIGHBOR LANGUAGE MODELS
11. Emergent and Predictable Memorization in Large Language Models

### Other interesting links

1. [Interactive linear algebra](https://textbooks.math.gatech.edu/ila/)
2. [Plot 3D graphs online](https://www.geogebra.org/)
3. [Plot 2D graphs online](https://www.desmos.com/calculator)

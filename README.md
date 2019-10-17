
# Awesome-AGI-Paper
**Our dream is creating real AI who is suitable for all domains, here are some papers we high recommanded**
## Representation learning

### AutoEncoder
   - [**Auto-Encoding Variational Bayes**](https://arxiv.org/abs/1312.6114)[`ORIGINAL`]
   - [**vq-vae2**](https://github.com/rosinality/vq-vae-2-pytorch) [`SOTA`]
   - [**Adversarial Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical  Flow and Motion Segmentation**](https://github.com/anuragranj/cc)
#### Disentangled-representations
   - [**Learning Disentangled Joint Continuous and Discrete Representations**](https://arxiv.org/pdf/1804.00104.pdf)
   - [**Understanding disentangling in β-VAE**](https://arxiv.org/pdf/1804.03599.pdf)
   - [**Isolating Sources of Disentanglement in VAEs**](https://arxiv.org/pdf/1802.04942.pdf)
   - [**Ladder Variational Autoencoders**](https://arxiv.org/pdf/1602.02282.pdf)
### GAN
- [**f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization**](https://arxiv.org/abs/1606.00709)
- [**INFO-GAN**](https://arxiv.org/abs/1606.03657)
- [**WGAN**](https://arxiv.org/abs/1701.07875)
- [**Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks**](https://arxiv.org/pdf/1703.10593.pdf)
## DRL
### Task-Agnostic Reinforcement Learning
 - [ Workshop at ICLR, 06 May 2019, New Orleans Building agents that explore and learn in the absence of rewards](https://tarl2019.github.io/)[`24papers`]
 ### Successor Representations
   - [**Predicting the Future with Multi-scale Successor Representations**](https://www.biorxiv.org/content/10.1101/449470v1.full#ref-39)
### OPTIONS SKILL
   - Learning Abstract Options
   - Successor Options: An Option Discovery Framework for Reinforcement Learning
### Model base
   - [**LEARNING AWARENESS MODELS**](https://arxiv.org/pdf/1804.06318.pdf) *ICLR 2018* 
   - [**Curiosity-driven Exploration by Self-supervised Prediction**](https://pathak22.github.io/noreward-rl/resources/icml17.pdf) *ICML 2017* [`curiosity`][`ICM`]
   - [**Learning Latent Dynamics for Planning from Pixels**](https://arxiv.org/pdf/1811.04551.pdf) *ICML 2018* [`MPC`][`VAE`]  [`planet`]
   - [**Dynamics-Aware Unsupervised Discovery of Skills**](https://arxiv.org/pdf/1907.01657.pdf)
   - [**INFOBOT**](https://openreview.net/pdf?id=rJg8yhAqKm) 
   - [**EMI**](https://arxiv.org/abs/1810.01176) 
   - [**Unsupervised Discovery of Decision States for Transfer in Reinforcement Learning**](https://arxiv.org/abs/1907.10580)
### Model free
   - [**TRPO**](https://arxiv.org/abs/1506.02438)
   - [**PPO**](https://arxiv.org/abs/1707.06347)
   - [**DDPG**](https://arxiv.org/abs/1509.02971)
   - [**TD3**](https://arxiv.org/abs/1802.09477)
   - [**SAC**](https://arxiv.org/abs/1801.01290)
   - [**RECURRENT REINFORCEMENT LEARNING:A HYBRID APPROACH**](https://arxiv.org/pdf/1509.03044.pdf)
### Meta learning
   - [**MBMPO**](https://arxiv.org/abs/1809.05214)
## Memory
### HUBE
   - [**A BIOLOGICALLY INSPIRED VISUAL WORKING MEMORY FOR DEEP NETWORKS**](https://github.com/JingbinLiu/STAWM)
### NTM
   - [**Learning to Remember More with Less Memorization**](https://arxiv.org/abs/1901.01347/)
### Episode memory
   - [**Learning to Learn without Forgetting by Maximizing Transfer and Minimizing Interference**](https://github.com/mattriemer/mer)
### Association memory
   - [**Dense Associative Memory is Robust to Adversarial Inputs**](https://arxiv.org/abs/1701.00939)
### Few shot learning
   - [**Meta-Transfer Learning for Few-Shot Learning**](https://arxiv.org/abs/1812.02391)

## Mutual infomation
- [**Unsupervised Discovery of Decision States for Transfer in Reinforcement Learning**](https://arxiv.org/abs/1907.10580)
- [**Dynamics-Aware Unsupervised Discovery of Skills**](https://arxiv.org/pdf/1907.01657.pdf)   

- [**Contrastive Bidirectional Transformer for Temporal Representation Learning**]

- [**Contrastive Multiview Coding**]
- Infobot 
- DIM 
- cpc
- EMI
- MINE

- [**Learning Belief Representations for Imitation Learning in POMDPs**](https://github.com/tgangwani/BMIL)

- INFORMATION ASYMMETRY IN KL-REGULARIZED RL    

- Exploiting Hierarchy for Learning and Transfer in KL-regularized RL

- Learning to Share and Hide Intentions using Information Regularization

## General
- [**THE THERMODYNAMICS OF MACHINE LEARNING**](https://arxiv.org/abs/1807.04162)

# Key point
### Curiosity-driven Exploration by Self-supervised Prediction
Learning a predictor and use predict error as internal reward, and they jointly train an inverse dynamics model for encoder, who project observation to a space that is invariant to parts of the environment that do not affect the agent or task. 

<img src="https://github.com/createamind/Awesome-AGI-Paper/blob/master/img/ICM_min-d1e454752470ec66bea6561d61f2d369d9d8f7fad92c0a3dcdc69614e5dd1f96.png" width="700" style="display:inline"/>

### EMI
* Learn the representation of states and the action such that the representation of the corresponding next state following linear dynamics
* Intrinsic reward augmentation
* https://github.com/snu-mllab/EMI

### THE THERMODYNAMICS OF MACHINE LEARNING
In this work we offer an information-theoretic framework for representation learn- ing that connects with a wide class of existing objectives in machine learning. We develop a formal correspondence between this work and thermodynamics and dis- cuss its implications.

### RECURRENT REINFORCEMENT LEARNING:A HYBRID APPROACH
propose a new family of hybrid models that combines the strength of
both supervised learning (SL) and reinforcement learning (RL), trained in a joint
fashion: The SL component can be a recurrent neural networks (RNN) or its long
short-term memory (LSTM) version, which is equipped with the desired property
of being able to capture long-term dependency on history, thus providing an effective
way of learning the representation of hidden states. The RL component
is a deep Q-network (DQN) that learns to optimize the control for maximizing
long-term rewards. Extensive experiments in a direct mailing campaign problem
demonstrate the effectiveness and advantages of the proposed approach
<img src="https://static.dingtalk.com/media/lALPDgQ9rDbF0TbNAYbNA4Q_900_390.png_620x10000q90g.jpg?auth_bizType=IM&auth_bizEntity=%7B%22cid%22%3A%22133885220%3A447781637%22%2C%22msgId%22%3A%221660320396044%22%7D&open_id=133885220" width="700" style="display:inline"/>

### Dynamics-Aware Unsupervised Discovery of Skills
Graphical models, Information Bottleneck and Unsupervised Skill Learning

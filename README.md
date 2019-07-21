
# Awesome-AGI-Paper
**Our dream is to create real AI who is suitable for all domains, here are some papers we high recommanded**
## Representation learning
### Autoencoder
   - [**vqvae2**](https://github.com/rosinality/vq-vae-2-pytorch) [`SOTA`]
   - [**Adversarial Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical  Flow and Motion Segmentation**](https://github.com/anuragranj/cc)
### GAN
- [**f-GAN: Training Generative Neural Samplers using Variational Divergence Minimization**](https://arxiv.org/abs/1606.00709)
## DRL
### Model base
   - [**LEARNING AWARENESS MODELS**](https://arxiv.org/pdf/1804.06318.pdf) *ICLR 2018* 
   - [**Curiosity-driven Exploration by Self-supervised Prediction**](https://pathak22.github.io/noreward-rl/resources/icml17.pdf) *ICML 2017* [`curiosity`][`ICM`]
   - [**Learning Latent Dynamics for Planning from Pixels**](https://arxiv.org/pdf/1811.04551.pdf) *ICML 2018* [`MPC`][`VAE`]  [`planet`]
   - [**Dynamics-Aware Unsupervised Discovery of Skills**](https://arxiv.org/pdf/1907.01657.pdf)   Graphical models, Information Bottleneck and Unsupervised Skill Learning
   - [**INFOBOT**](https://openreview.net/pdf?id=rJg8yhAqKm) 
   - [**EMI**](https://arxiv.org/abs/1810.01176) 
### Model free
   - [**TRPO**](https://arxiv.org/abs/1506.02438)
   - [**PPO**](https://arxiv.org/abs/1707.06347)
   - [**DDPG**](https://arxiv.org/abs/1509.02971)
   - [**TD3**](https://arxiv.org/abs/1802.09477)
   - [**SAC**](https://arxiv.org/abs/1801.01290)
## Meta learning
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

## Key point
### Curiosity-driven Exploration by Self-supervised Prediction
Learning a predictor and use predict error as internal reward, and they jointly train an inverse dynamics model for encoder, who project observation to a space that is invariant to parts of the environment that do not affect the agent or task. 

<img src="https://github.com/createamind/Awesome-AGI-Paper/blob/master/img/ICM_min-d1e454752470ec66bea6561d61f2d369d9d8f7fad92c0a3dcdc69614e5dd1f96.png" width="350" style="display:inline"/>

### EMI
* Learn the representation of states and the action such that the representation of the corresponding next state following linear dynamics
* Intrinsic reward augmentation
* https://github.com/snu-mllab/EMI

# mutual infomation

##
###
- [**Dynamics-Aware Unsupervised Discovery of Skills**](https://arxiv.org/pdf/1907.01657.pdf)   Graphical models, Information Bottleneck and Unsupervised Skill Learning

- Contrastive Bidirectional Transformer for Temporal Representation Learning

- Contrastive Multiview Coding 

- infobot DIM cpc；EMI；MINE

- soft q -mutual info；；

- https://github.com/tgangwani/BMIL    Learning Belief Representations for Imitation Learning in POMDPs

- INFORMATION ASYMMETRY IN KL-REGULARIZED RL      model free MI; model base MI  ???

- Exploiting Hierarchy for Learning and Transfer in KL-regularized RL

- Learning to Share and Hide Intentions using Information Regularization

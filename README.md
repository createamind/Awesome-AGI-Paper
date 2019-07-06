# Awesome-AGI-Paper
## Representation learning
### autoencoder
   - [**vqvae2**](https://github.com/rosinality/vq-vae-2-pytorch)
   - [**Adversarial Collaboration: Joint Unsupervised Learning of Depth, Camera Motion, Optical  Flow and Motion Segmentation**](https://github.com/anuragranj/cc)
###
## DRL
### model base
   - [**LEARNING AWARENESS MODELS**](https://arxiv.org/pdf/1804.06318.pdf) *ICLR 2018* 
   - [**Curiosity-driven Exploration by Self-supervised Prediction**](https://pathak22.github.io/noreward-rl/resources/icml17.pdf) *ICML 2017* [`curiosity`]
   - [**Learning Latent Dynamics for Planning from Pixels**](https://arxiv.org/pdf/1811.04551.pdf) *ICML 2018* [`MPC`][`VAE`]
   - [**Dynamics-Aware Unsupervised Discovery of Skills**](https://arxiv.org/pdf/1907.01657.pdf)   Graphical models, Information Bottleneck and Unsupervised Skill
Learning
### model free
   - [**sac**]()
   - [**ppo**]()
   - [****]()
## Meta learning
   - [****]()
## Memory
### hube
   - [**A BIOLOGICALLY INSPIRED VISUAL WORKING MEMORY FOR DEEP NETWORKS**](https://github.com/JingbinLiu/STAWM)
### NTM
   - [**Learning to Remember More with Less Memorization**](https://arxiv.org/abs/1901.01347/)
### episode mem 
   - [**Learning to Learn without Forgetting by Maximizing Transfer and Minimizing Interference**](https://github.com/mattriemer/mer)
### association mem
   - [****]()
## one shot

# Key point
- [**LEARNING AWARENESS MODELS**]
Learning a predictor and use predict error as internal reward, and they jointly train an inverse dynamics model for encoder, who project observation to a space that is invariant to parts of the environment that do not affect the agent or task. 

<img src="https://github.com/createamind/Awesome-AGI-Paper/blob/master/img/ICM_min-d1e454752470ec66bea6561d61f2d369d9d8f7fad92c0a3dcdc69614e5dd1f96.png" width="350" style="display:inline"/>

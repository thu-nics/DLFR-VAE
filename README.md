# DLFR-VAE: Dynamic Latent Frame Rate VAE for Video Generation

Dynamic Latent Frame Rate VAE (DLFR-VAE) is a training-free paradigm that utilizes adaptive temporal compression in latent space. While existing video generative models apply fixed compression rates via pretrained VAE, we observe that real-world video content exhibits significant temporal non-uniformity, with high-motion segments containing more information than static scenes. Based on this insight, DLFR-VAE dynamically adjusts the latent frame rate according to content complexity. Specifically, DLFR-VAE comprises two core innovations: 1. A Dynamic Latent Frame Rate Scheduler that partitions videos into temporal chunks and adaptively determines optimal frame rates based on information-theoretic content complexity. 2. A training-free adaptation mechanism that transforms pretrained VAE architectures into a dynamic VAE capable of processing features with variable frame rates. Our simple yet effective DLFR-VAE can function as a plug-and-play module, seamlessly integrating with existing video generation models and accelerating the video generation process. [Paper link](http://arxiv.org/abs/2502.11897).

# TODO List
- Demo show
- Release DLFR HunyuanVideo VAE
- Release HunyuanVideo Generation with VAE Decoder

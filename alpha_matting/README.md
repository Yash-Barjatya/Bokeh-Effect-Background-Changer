This folder contains the code for the matting module 

**Deatils** - 

The matting network takes as input an RGB image (𝐶) and a coarse trimap of the foreground (𝑇 ).A multi-task encoder-decoder architecture (U-Net [Ronneberger et al. 2015]) is then used to predict a refined trimap 𝑇ˆ, the alpha channel 𝛼, and the foreground 𝐹.

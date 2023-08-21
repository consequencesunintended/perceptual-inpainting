# The Role of Chromatic Stimuli in Modulating Perceptual Inpainting within the Visual Cortex

We employ a third party [pre-trained facial segmentation](https://github.com/zllrunning/face-parsing.PyTorch) model to integrate grids of varying sizes. These grids distinctly colour the face and the background using only red [0,0,175] and blue [255,0,0] hues. By doing so, we aim to investigate how these chromatic stimuli, in conjunction with spatial elements like grid size, influence the brain's capacity for perceptual inpainting

What presents itself as a colourisation model is in fact an overlay on a segmentation model that draws diagonal red and blue lines  on the relevant image. This allows the visual cortex to inpaint the associated colours. To exaggerate the effects, the model changes the grid size every 2 frames, iterating through 100, 50, 25, and 10 grid sizes.


https://github.com/consequencesunintended/perceptual-inpainting/assets/44167267/ea0abc22-463e-4f0b-b0bc-08c0c996ff71


https://github.com/consequencesunintended/perceptual-inpainting/assets/44167267/6f9a6d2a-983a-4e69-b0fe-e5e22c5184fc


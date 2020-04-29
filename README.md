# UNet-PyTorch
My final attempt and implementation of the UNet architecture in PyTorch (seeing as not many stable and simple implementations are available online). 


Inspired by the model architecute diagram given at https://pytorch.org/hub/mateuszbuda_brain-segmentation-pytorch_unet/, but made to fit for images of (3, 512, 512) size. 



![UNet Architecture](https://pytorch.org/assets/images/unet_brain_mri.png)


This is only the model architecture as Python script, and in no way a fully-usable package to implement UNet for production. Feel free to use the architecture in your own way. All you'll need to do is make sure your input image is (3, 512, 512), and you should get an output of segmentation map of (1, 512, 512).


Note: generalized architecture with customizable input sizes coming soon!

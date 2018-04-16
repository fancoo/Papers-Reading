# Papers-Reading
My Papers reading notes, along with my personal summary about each paper, so there may exist lots of mistakes, I really appreciate you to point out.

## Contents
### Neural Style Transfer
- [x] [Neural Style Transfer: A Review](https://github.com/fancoo/Papers-Reading/blob/master/Neural-Style-Transfer/Neural%20Style%20Transfer-A%20Review.pdf) :star::star::star::star:
	* Investigate the works of Neural Style Transfer till May of 2016.
- [ ] [Demystifying Neural Style Transfer](https://arxiv.org/abs/1701.01036)
	* Prove that matching the Gram matrices is actually equivalent to minimize the Maximum Mean Discrepancy(MMD) with second order polynomial kernel.
	* Try out for different kernels and parameters.
- [ ] [Fast Patch-based Style Transfer of Arbitrary Style](https://arxiv.org/abs/1612.04337)
	* A more advanced version of "Fast" Neural Style Transfer that can run in real-time and applies to infinite kind of styles.
	* The drawback is the quality of stylized images is worse than "Fast" Neural Style which yet can only applies to finite styles.

### Generative Model
- [x] [Pixel Recurrent Neural Networks(Best Paper of ICML2016)](https://github.com/fancoo/Papers-Reading/blob/master/Generative-Model/Pixel%20Recurrent%20Neural%20Networks.pdf)
	* I quickly skimmed this paper, it introduced a new method to generate image pixel by pixel with sequence model, which means **you can only predict current pixel by it's previous pixels.**
	* The loss curve is much more smooth and interpretatable than GAN.
- [ ] [Conditional Image Generation with PixelCNN Decoders](https://arxiv.org/abs/1606.05328)
- [ ] [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499)

## License
This project is licensed under the terms of the MIT license.



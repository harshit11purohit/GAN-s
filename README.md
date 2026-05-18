"# GAN-s" 
# GAN-s

A comprehensive repository exploring various Generative Adversarial Network (GAN) architectures implemented on the MNIST dataset to track how generative architectural designs evolved.

---

### Notebook Breakdown

#### [Vanilla_GAN_MNIST.ipynb](./Vanilla_GAN_MNIST.ipynb)
* Implements the original 2014 framework using simple fully-connected (dense) layers for both the Generator and Discriminator.
* Demonstrates the fundamental adversarial minimax game theory mechanics on basic handwritten digit shapes.

#### [DCGAN_MNIST.ipynb](./DCGAN_MNIST.ipynb)
* Replaces standard dense networks with deep spatial layers utilizing transposed convolutions, batch normalization, and LeakyReLU activations.
* Provides a significantly more stable training landscape that drastically sharpens structural image quality.

#### [Conditional_GAN_MNIST.ipynb](./Conditional_GAN_MNIST.ipynb)
* Introduces target label embeddings to pass numeric class requirements (digits 0–9) directly into both networks alongside the raw features.
* Allows developers to actively control the precise digit category the Generator manufactures rather than relying on random noise output.

#### [CycleGAN_MNIST.ipynb](./CycleGAN_MNIST.ipynb)
* Features an unpaired image-to-image translation layout to convert imagery characteristics across separate visual domains without exact matched sets.
* Utilizes a dual-generator architecture governed by structural cycle-consistency loss functions to retain original patterns across translation cycles.

#### [StyleGAN_Inspired_MNIST.ipynb](./StyleGAN_Inspired_MNIST.ipynb)
* Drops standard latent vector inputs in favor of a specialized mapping network that injects visual attributes at varying resolution depths.
* Provides unparalleled control over high-, mid-, and fine-frequency style attributes for highly detailed image manipulation.

#### [Text_to_Image_GAN_MNIST.ipynb](./Text_to_Image_GAN_MNIST.ipynb)
* Combines natural language processing concepts with generative layers by accepting encoded textual prompt descriptions as inputs.
* Conditions the spatial image creation pipeline to render numeric visual outputs that explicitly align with specified semantic string prompts.

#### [GAN's_Types.ipynb](./GAN's_Types.ipynb)
* Serves as a central, comprehensive theoretical study tracking the underlying mathematical evolutions across unique GAN variants.
* Analyzes core historical issues like vanishing gradients and mode collapse alongside their respective architectural engineering fixes.
# GAN_Tensorflow
Generative Adversarial Networks using Tensorflow
GANs are designed to mimic any distribution of data. That is, GANs can be taught to create worlds eerily similar to our own in any domain: images, music, speech, prose.“Generator” generates fake data, and the detective is called the “Discriminator”, which is responsible for classifying the output of the generator as fake or real.

Complications of GAN:
Computationally Expensive: GANs are computationally expensive, in the sense that, they require high-powered GPU’s to produce good results.
Discriminator overpowering Generator:Sometimes the discriminator begins to classify all generated examples as fake due to the slightest differences. So, to rectify this, make the output of the discriminator unscaled instead of sigmoid(which produces only zero or one).
Mode Collapse: The generator discovers some potential weakness in the discriminator and exploits that weakness to continually produce a similar example regardless of variation in input.

The code is an implmentation on MINST dataset.

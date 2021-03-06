
#### [Three Approaches to Generative Models](https://blog.openai.com/generative-models/)

- [Generative Adversarial Networks (GANs)]
  - [Different Versions of GANs](#different-versions-of-gans)
  - [GANs Comparision](#gans-comparision)
  - [GANs Survey for Vision](#gans-survey-for-vision)
  - [Variants of GAN Architecture](#variants-of-gan-architecture)
  - [GAN Value Functions](#gan-value-functions)
  - [References](#references)
  - [Paper Review](#paper-review)
- [Variational Autoencoders (VAEs)]
  - [Autoencoders](https://github.com/gopala-kr/autoencoders)
- [Autoregressive models]
  - [EX: PixelRNN]


[Back to top](#three-approaches-to-generative-models)

-----------

#### Different Versions of GANs

[Back to top](#three-approaches-to-generative-models)

*(I have listed below GANs based on their [timelines](https://github.com/dongb5/GAN-Timeline), since from GANs inception(Jun 2014))*

  - [DCGANs]
  - [cGANs]
  - [InfoGANs]
  - [Wasserstein GANs]
  - [LAPGAN]
  - [GRAN ]
  - [BiGANs]
  - [f-GAN]
  - [CoGAN]
  - [EBGAN]
  - [iGAN]
  - [SeqGAN]
  - [RenderGAN]
  - [VGAN]
  - [LSGANs]
  - [IcGAN]
  - [TGAN]
  - [SAD-GAN]
  - [C-RNN-GAN]
  - [AANs]
  - [StackGAN]
  - [SGAN]
  - [SalGAN]
  - [AdaGAN]
  - [GLS-GAN]
  - [ArtGAN]
  - [BS-GAN]
  - [AM-GAN]
  - [Triple-GAN]
  - [DiscoGAN]
  - [SEGAN]
  - [CVAE-GAN]
  - [SeGAN]
  - [CycleGAN]
  - [BEGAN]
  - [MidiNet]
  - [Semi-Latent GAN]
  - [DualGAN]
  - [A-Fast-RCNN]
  - [MAGAN]
  - [Gang of GANs]
  - [Softmax GAN]
  - [Show, Adapt and Tell]
  - [Geometric GAN]
  - [GeneGAN]
  - [Flow-GAN]
  - [SegAN]
  - [DeLiGAN]
  - [StackGAN]
  - [Flow-GAN]
  - [GraphGAN]
  - [MuseGAN]
  - [OptionGAN]
  - [RAN4IQA]
  - [Show, Reward and Tell]



More GANs -->  [The GAN Zoo](https://github.com/hindupuravinash/the-gan-zoo)

----------------

##### GANs Comparision

[Back to top](#three-approaches-to-generative-models)

![gan_comparsion](https://github.com/gopala-kr/GANs/blob/master/res/img/gan_comparsion.PNG)

------------

##### GANs Survey for Vision

[Back to top](#three-approaches-to-generative-models)

![gan_image_1](https://github.com/gopala-kr/GANs/blob/master/res/img/gan_image_3.PNG)


![gan_image_2](https://github.com/gopala-kr/GANs/blob/master/res/img/gan_image_4.PNG)

---------
##### Variants of GAN Architecture

[Back to top](#three-approaches-to-generative-models)


<img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/etc/GAN_structure.png' height = '600px'>

---------------

![Computation](https://www.researchgate.net/profile/Kunfeng_Wang/publication/319869547/figure/fig3/AS:660911190716417@1534584915656/Computation-procedures-and-structures-of-some-GAN-variants-a-GAN-1-WGAN-31.png)

------



#### GAN Value Functions

[Back to top](#three-approaches-to-generative-models)


*Name* | *Paper Link* | *Value Function*
:---: | :---: | :--- |
**GAN** | [Arxiv](https://arxiv.org/abs/1406.2661) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/GAN.png' height = '70px'>
**LSGAN**| [Arxiv](https://arxiv.org/abs/1611.04076) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/LSGAN.png' height = '70px'>
**WGAN**| [Arxiv](https://arxiv.org/abs/1701.07875) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/WGAN.png' height = '105px'>
**WGAN_GP**| [Arxiv](https://arxiv.org/abs/1704.00028) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/WGAN_GP.png' height = '70px'>
**DRAGAN**| [Arxiv](https://arxiv.org/abs/1705.07215) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/DRAGAN.png' height = '70px'>
**CGAN**| [Arxiv](https://arxiv.org/abs/1411.1784) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/CGAN.png' height = '70px'>
**infoGAN**| [Arxiv](https://arxiv.org/abs/1606.03657) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/infoGAN.png' height = '70px'>
**ACGAN**| [Arxiv](https://arxiv.org/abs/1610.09585) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/ACGAN.png' height = '70px'>
**EBGAN**| [Arxiv](https://arxiv.org/abs/1609.03126) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/EBGAN.png' height = '70px'>
**BEGAN**| [Arxiv](https://arxiv.org/abs/1702.08431) | <img src = 'https://github.com/hwalsuklee/tensorflow-generative-model-collections/blob/master/assets/equations/BEGAN.png' height = '105px'>  


---------------

#### References

[Back to top](#three-approaches-to-generative-models)

- Generative Adversarial Networks: An Overview [[arXiv]](https://arxiv.org/abs/1710.07035)
- [NIPS 2016 Tutorial:
Generative Adversarial Networks](https://arxiv.org/pdf/1701.00160.pdf)
- [Survey on Generative Adversarial Networks](https://pdfs.semanticscholar.org/0e1b/15ee5b4eec9b19eae9ae973a2ddc64f6cc72.pdf)
- [Comparative Study on Generative Adversarial Networks](https://arxiv.org/pdf/1801.04271.pdf)
- [GAN Lab: Understanding Complex Deep Generative Models using
Interactive Visual Experimentation](https://arxiv.org/pdf/1809.01587v1.pdf)
- [A Survey of Image Synthesis and Editing with Generative Adversarial
Networks](https://cg.cs.tsinghua.edu.cn/people/~kun/papers/gan_survey_final.pdf)
- [OpenAI: Generative Models](https://blog.openai.com/generative-models/)
- [Generative models](https://storage.googleapis.com/ml4a.github.io/Slides_06/assets/player/KeynoteDHTMLPlayer.html#0)
- [Adversarial Examples: Attacks and Defenses for Deep Learning](https://arxiv.org/pdf/1712.07107.pdf)
- [Generative Adversarial Nets for Information Retrieval: Fundamentals and Advances](https://arxiv.org/abs/1806.03577v1)
- [The GAN Landscape: Losses, Architectures, Regularization, and Normalization](https://arxiv.org/abs/1807.04720v1)
- [A Tale of Three Probabilistic Families: Discriminative, Descriptive
and Generative Models](https://arxiv.org/pdf/1810.04261v1.pdf)


-----------
#### Paper Review

[Back to top](#three-approaches-to-generative-models)

- [GAN-theory-and-ml](https://github.com/gopala-kr/GANs/blob/master/GAN-theory-and-ml.md)
- [GAN-ref-implementations](https://github.com/gopala-kr/GANs/blob/master/GAN-ref-implementations.md)
- [GAN-applications](https://github.com/gopala-kr/GANs/blob/master/GAN-applications.md)
- [GANs for vision](https://github.com/gopala-kr/GANs/blob/master/GAN-vision.md)

------------

_**Maintainer**_

Gopala KR / @gopala-kr

--------------

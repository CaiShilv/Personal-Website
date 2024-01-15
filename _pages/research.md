---
permalink: /research/
title: "Research"
layout: single
author_profile: true
---



## Papers
**Shilv Cai, Liqun Chen, Zhijun Zhang, Xiangyun Zhao, Jiahuan Zhou, Yuxin Peng, Luxin Yan, Sheng Zhong, and Xu Zou. I2C: Invertible Continuous Codec for High-Fidelity Variable-Rate Image Compression. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2024 (Accepted).**


<p style="text-align: justify;">
Abstract: Lossy image compression is a fundamental technology in media transmission and storage. Variable-rate approaches have recently gained much attention to avoid the usage of a set of different models for compressing images at different rates. During the media sharing, multiple re-encodings with different rates would be inevitably executed. However, existing Variational Autoencoder (VAE)-based approaches would be readily corrupted in such circumstances, resulting in the occurrence of strong artifacts and the destruction of image fidelity. Based on the theoretical findings of preserving image fidelity via invertible transformation, we aim to tackle the issue of high-fidelity fine variable-rate image compression and thus propose the Invertible Continuous Codec (I2C). We implement the I2C in a mathematical invertible manner with the core Invertible Activation Transformation (IAT) module. I2C is constructed upon a single-rate Invertible Neural Network (INN) based model and the quality level (QLevel) would be fed into the IAT to generate scaling and bias tensors. Extensive experiments demonstrate that the proposed I2C method outperforms state-of-the-art variable-rate image compression methods by a large margin, especially after multiple continuous re-encodings with different rates, while having the ability to obtain a very fine variable-rate control without any performance compromise. The project is publicly available at https://github.com/CaiShilv/HiFi-VRIC.
</p>


**Shilv Cai, Liqun Chen, Sheng Zhong, Luxin Yan, Jiahuan Zhou, and Xu Zou. Make Lossy Compression Meaningful for Low-Light Images. In Proceedings of the 38th AAAI Conference on Artificial Intelligence (AAAI), 2024 (Accepted).**


<p style="text-align: justify;">
Abstract: Low-light images frequently occur due to unavoidable environmental influences or technical limitations, such as insufficient lighting or limited exposure time. To achieve better visibility for visual perception, low-light image enhancement is usually adopted. Besides, lossy image compression is vital for meeting the requirements of storage and transmission in computer vision applications. To touch the above two practical demands, current solutions can be categorized into two sequential manners: ``Compress before Enhance~(CbE)'' or ``Enhance before Compress~(EbC)''. However, both of them are not suitable since: (1) Error accumulation in the individual models plagues sequential solutions. Especially, once low-light images are compressed by existing general lossy image compression approaches, useful information~(\textit{e.g.}, texture details) would be lost resulting in a dramatic performance decrease in low-light image enhancement. (2) Due to the intermediate process, the sequential solution introduces an additional burden resulting in low efficiency. We propose a novel joint solution to simultaneously achieve a high compression rate and good enhancement performance for low-light images with much lower computational cost and fewer model parameters. We design an end-to-end trainable architecture, which includes the main enhancement branch and the signal-to-noise ratio~(SNR) aware branch. Experimental results show that our proposed joint solution achieves a significant improvement over different combinations of existing state-of-the-art sequential ``Compress before Enhance'' or ``Enhance before Compress'' solutions for low-light images, which would make lossy low-light image compression more meaningful. The project is publicly available at: https://github.com/CaiShilv/Joint-IC-LL.
</p>


**[Shilv Cai, Zhijun Zhang, Liqun Chen, Luxin Yan, Sheng Zhong, and Xu Zou. High-Fidelity Variable-Rate Image Compression via Invertible Activation Transformation. In Proceedings of the 30th ACM International Conference on Multimedia (ACM MM), 2022 (Published)](https://arxiv.org/abs/2209.05054)**


<p style="text-align: justify;">
Abstract: Learning-based methods have effectively promoted the community of image compression. Meanwhile, variational autoencoder~(VAE) based variable-rate approaches have recently gained much attention to avoid the usage of a set of different networks for various compression rates. Despite the remarkable performance that has been achieved, these approaches would be readily corrupted once multiple compression/decompression operations are executed, resulting in the fact that image quality would be tremendously dropped and strong artifacts would appear. Thus, we try to tackle the issue of high-fidelity fine variable-rate image compression and propose the Invertible Activation Transformation~(IAT) module. We implement the IAT in a mathematical invertible manner on a single rate Invertible Neural Network~(INN) based model and the quality level~(QLevel) would be fed into the IAT to generate scaling and bias tensors. IAT and QLevel together give the image compression model the ability of fine variable-rate control while better maintaining the image fidelity. Extensive experiments demonstrate that the single rate image compression model equipped with our IAT module has the ability to achieve variable-rate control without any compromise. And our IAT-embedded model obtains comparable rate-distortion performance with recent learning-based image compression methods. Furthermore, our method outperforms the state-of-the-art variable-rate image compression method by a large margin, especially after multiple re-encodings.
</p>


## Work in Progress

**Shilv Cai, Xiaoguo Liang, Shuning Cao, Luxin Yan, Sheng Zhong, Liqun Chen, and Xu Zou. Powerful Lossy Compression for Noisy Images. (Under review)**

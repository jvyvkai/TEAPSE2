# TEA-PSE 2.0


Demo clips for "TEA-PSE 2.0: SUB-BAND NETWORK FOR REAL-TIME PERSONALIZED SPEECH ENHANCEMENT".

Authors:
[Yukai Ju](https://github.com/jvyvkai), [Shimin Zhang](https://github.com/echocatzh), Wei Rao, Yannan Wang, Tao Yu, Lei Xie, Shidong Shang.

Abstract:
Personalized speech enhancement (PSE) utilizes additional cues like speaker embeddings to remove background noise and interfering speech and extract the speech from target speaker. Previous work, the Tencent-Ethereal-Audio-Lab personalized speech enhancement (TEA-PSE) system, ranked 1st in the ICASSP 2022 deep noise suppression (DNS2022) challenge. In this paper, we expand TEA-PSE to its sub-band version – TEA-PSE 2.0, to reduce computational complexity as well as further improve performance. Specifically, we adopt finite impulse response filter banks and spectrum splitting to reduce computational complexity. We introduce a time frequency convolution module (TFCM) to the system for increasing the receptive field with small convolution kernels. Besides, we explore several training strategies to optimize the two-stage network and investigate various loss functions in the PSE task. TEA-PSE 2.0 significantly outperforms TEA-PSE in both speech enhancement performance and computation complexity. Experimental results on the DNS2022 blind test set show that TEA-PSE 2.0 brings 0.102 OVRL personalized DNSMOS improvement with only 21.9% multiply-accumulate operations compared with the previous TEA-PSE.


Accepted by [SLT 2022](https://slt2022.org/)

The demo page: [TEA-PSE 2.0](https://jvyvkai.github.io/TEAPSE2/)

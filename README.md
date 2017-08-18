# NU-InNet
This implements training of NU-InNet (Naresuan University Inception Network) from NU-InNet: Thai Food Image Recognition Using Convolutional Neural Networks on Smartphone by Chakkrit Termritthikun, et. al.

This implements training of residual networks from [NU-InNet: Thai Food Image Recognition Using Convolutional Neural Networks](http://journal.utem.edu.my/index.php/jtec/article/view/2436/1521) by [Chakkrit Termritthikun](https://chakkritte.github.io/cv/), et. al.

# TH-FOOD50
Coming soon

# Result NU-InNet with TH-FOOD50

#### Single-crop (224x224) average of 10-fold-cross-validation

| Network       | Top-1 Accuracy | Top-5 Accuracy | Average Forward-Backward (ms/images) | Parameters (x10^6) |
| --------      | --------       | --------       | --------                 | --------   |
| AlexNet       | 58.1           | 86.4           | 13.90                     | 58.48       |
| SqueezeNet    | 58.2           | 87.4           | 24.53                     | 0.75       |
| GoogLeNet     | 68.4           | 91.7           | 40.13                     | 10.45       |
| **NU-InNet 1.0**  | 69.8           | 92.3           | 18.16                     | 0.88       |
| **NU-InNet 1.1**  | 68.7           | 92.3           | 36.52                     | 0.89       |


## License and Citation

NU-InNet and TH-FOOD50 for **non-commercial research/educational** use.

Please cite NU-InNet and TH-FOOD50 in your publications if it helps your research:

( Thai ) NU-InNet และ TH-FOOD50 อนุญาตให้ใช้เฉพาะเพื่อการ**ศึกษาและวิจัยเท่านั้น ห้ามนำไปใช้เชิงการค้าทุกรูปแบบ**

หากคุณนำ NU-InNet หรือ TH-FOOD50 ไปใช้ในงานวิจัย กรุณาอ้างอิง 

    @article{termritthikun2017nu,
      title={NU-InNet: Thai Food Image Recognition Using Convolutional Neural Networks on Smartphone},
      author={Termritthikun, Chakkrit and Muneesawang, Paisarn and Kanprachar, Surachet},
      journal={Journal of Telecommunication, Electronic and Computer Engineering (JTEC)},
      volume={9},
      number={2-6},
      pages={63--67},
      year={2017}
    }

## Donate

![Build Status](https://raw.githubusercontent.com/chakkritte/NU-InNet/master/images/pic.png)

 (Bitcoin Address) : 3DermWyouJQ5MwoNvEtv2SgnvFRMTDBudv

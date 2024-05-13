# Comparative Analysis of Adversarial Attacks and Defense Methods
 In this project, we explore and contrast the impacts of multiple adversarial
 attacks, including Projected Gradient Descent (PGD), noise-based attacks, Fast
 Gradient Sign Method (FGSM), Carlini & Wagner (C&W), DeepFool, Feature
 importance-aware Attack(FIA), and Jacobian-based Saliency Maps(JSM) on three
 distinct neural network architectures, using the CIFAR-10 dataset. The models
 evaluated include a custom-trained simple Convolutional Neural Network (CNN),
 a pre-trained ResNet-18, and a Tiny Vision Transformer (Tiny-VIT) which has
 been specifically trained on the CIFAR-10 dataset. We employ a range of de
fense strategies, such as adversarial training, denoising through trained DnCNN,
 and regularization techniques, to mitigate the effects of these attacks. The perfor
mance of each model is meticulously assessed by comparing their accuracy under
 various adversarial conditions. This comparative analysis aims to elucidate the rel
ative effectiveness and shortcomings of each attack and defense method, providing
 insight into their practical implications in securing neural networks against adver
sarial threats.

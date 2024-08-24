# Cross-modal information retrieval using generative models

Implements a novel VAE with siamese loss on the latent space to correctly classify visually-invoked brain wave signals to the image shown.

The model achieves 25.30% Accuracy and 96% AUROC on 50-class classification, compared to a similarly deep standard VAE which achieves 2% and 50% respectively (random guessing, cannot pick apart signal at all). A neural net classifier achieves the same.

The model is also one of the first to perform reasonably on 100-class classification: 19.57% accuracy and 97% AUROC. Similarly deep standard VAEs and neural nets perform only as well as random guessing.

The model, unfortunately, is not able to reproduce the visually-invoked image from the brain wave signals.

![posterpng](https://github.com/user-attachments/assets/736c418f-5313-4db0-8598-e7cadb2076ae)

[CS237_Final_Project (17).pdf](https://github.com/user-attachments/files/16735774/CS237_Final_Project.17.pdf)

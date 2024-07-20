# MaskViT

Developed a system that processes video files to extract frames, train a Vision Transformer (ViT) model for masked autoencoding, and reconstruct frames. The system evaluates the accuracy of the reconstructed frames compared to the original frames.

The program extracts frames from the video and uses a pre-trained Vision Transformer (ViT) model to perform masked autoencoding. This involves training the model to reconstruct masked parts of the images (frames) and then evaluating the reconstruction accuracy.

The pre trained model used in this project is VIT-MAE model from Hugging Face transformers library . Specifically  facebook/vit-mae-base is utilized.
![image](https://github.com/user-attachments/assets/7e67331c-b900-465f-ac66-0fe70c96a4ca)


Three deep learning architectures were implemented and compared:

- **MobileNet + BiLSTM:** A lightweight, efficient combination of a pre-trained CNN and a bidirectional LSTM for temporal pattern learning.
- **VGG16 + LSTM:** A classical CNN architecture for spatial feature extraction followed by LSTM for sequence modeling.
- **Vision Transformer (ViT):** A transformer-based model capturing both spatial and temporal relationships using attention mechanisms.


### Dataset

- **Total Videos:** 2,000  
- **Violence Class:** 1,000 videos with violent activities  
- **NonViolence Class:** 1,000 videos with peaceful activities  
- **Format:** AVI  
- **Frame Extraction:** 16 equally spaced frames per video

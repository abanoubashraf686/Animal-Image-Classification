# Animal Image Classification Using Neural Networks 🐾

This project focuses on classifying images of 18 different animals using deep learning architectures. It is a hands-on project where we learned, experimented, and fine-tuned models to achieve high accuracies. Our efforts won **1st place** in the Kaggle course competition at our university.

---

## Dataset 📦

Since the original dataset was small, we collected additional images from multiple sources to cover the same 18 animals.  

**Sources:**
- [Animal Image Dataset (90 Different Animals)](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals)  
- [Sea Animals Image Dataset 🌊](https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste)  
- [Different types of Animals Labeled Image Datasets | images.cv](https://images.cv/dataset-categories/animals)  

**Dataset Stats:**  
- Total images after removing duplicates: **30,657**  
- Training: 21,459  
- Validation: 6,438  
- Test: 2,760  

**Classes:**  
- Total Number of Classes: **18**  
- Class Names:  
  `beaver, butterfly, cougar, crab, crayfish, crocodile, dolphin, dragonfly, elephant, flamingo, kangaroo, leopard, llama, lobster, octopus, pigeon, rhino, scorpion`

---

## Architectures Used 🏗️

We experimented with the following deep learning models:  

1. **Inception V3**  
<img width="1069" height="416" alt="Inception V3" src="https://github.com/user-attachments/assets/1073a296-3652-448a-a80e-61425112c33d" />

2. **ResNet**  
<img width="611" height="603" alt="ResNet 50" src="https://github.com/user-attachments/assets/0f3dfd9f-f49f-47c7-8336-a3156fa0e9c9" />
<img width="1124" height="444" alt="ResNet 152" src="https://github.com/user-attachments/assets/5349d864-3909-4184-bc8f-41dec7345c51" />

3. **MobileViT**  
<img width="1069" height="411" alt="MobileViT" src="https://github.com/user-attachments/assets/820a35ff-ebd6-48a4-bb38-568401d1b838" />

---

## Accuracies 📊

| Model          | Inception V3 | ResNet 50 | ResNet 152 | MobileViT |
|----------------|--------------|-----------|------------|-----------|
| Training Acc   | 98.18%       | 93.4%     | 93.8%      | 72.6%     |
| Validation Acc | 98.76%       | 94.25%    | 94.5%      | 72.7%     |
| Test Acc       | 98.66%       | 93.26%    | 94.6%      | 72.4%     |
| Pretrained     | Yes          | Yes       | Yes        | No        |

> ⚠️ For MobileViT, we stopped training despite it learning well without overfitting due to time constraints.

---

## Key Learnings ✨

- Hands-on experience with deep learning architectures: Inception V3, ResNet, and MobileViT.  
- Data collection, preprocessing, and augmentation for better model performance.  
- Model fine-tuning, experimentation with hyperparameters, and evaluation.  
- Practical understanding of training, validation, and testing pipelines in PyTorch/TensorFlow.  

We gained a lot of experience through this project, and it helped us achieve **1st place** in our university Kaggle course competition! 🏆  

![Competition Winning](https://www.kaggle.com/t/885dbe904a9941c9b0f8bd6c613360ec)
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d7af87ee-7f82-4ca4-a485-39f8ac0a4daa" />

---

## License

This project is for educational purposes.

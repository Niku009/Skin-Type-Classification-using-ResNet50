# 🧴 Skin Type Classification using ResNet50

A deep learning-based skin analysis tool that classifies facial images into **Dry**, **Normal**, or **Oily** skin types using a fine-tuned **ResNet50** model.

---

## 📸 What It Does

- 🧠 Classifies images into:
  - **Dry**
  - **Normal**
  - **Oily**

- 🔄 Trains a ResNet50 CNN on a labeled dataset
- ⚙️ Uses transfer learning for better performance on fewer images
- 🎯 Evaluates accuracy on validation and test sets
- 📊 Visualizes predictions with a color-coded border on the uploaded image:
  - 🟤 Dry → Brown border  
  - 🟢 Normal → Green border  
  - 🔴 Oily → Red border

---

## 📂 Dataset Used

- **Source**: [Oily-Dry-and-Normal-Skin-Types Dataset](https://www.kaggle.com/datasets/shakyadissanayake/oily-dry-and-normal-skin-types-dataset/data)
- Contains three folders (`dry`, `normal`, `oily`) under:
  - `train/`
  - `valid/`
  - `test/`

```text
Oily-Dry-Skin-Types/
├── train/
│   ├── dry/
│   ├── normal/
│   └── oily/
├── valid/
│   ├── dry/
│   ├── normal/
│   └── oily/
└── test/
    ├── dry/
    ├── normal/
    └── oily/


```
## 🧠 Tech Stack

| Tool           | Purpose                                 |
|----------------|-----------------------------------------|
| **PyTorch**     | Deep learning framework                 |
| **ResNet50**    | Pretrained CNN for image classification |
| **Torchvision** | Transforms & pretrained models          |
| **Matplotlib**  | Image visualization                     |
| **Google Colab**| Training & inference environment        |

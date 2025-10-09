Objective was to identify and benchmark several advanced convolutional neural network (CNN)architectures for distinguishing the full ASL alphabet, and then to embed the mostaccurate model into a live recognition stream driven by a webcam and MediaPipe hand tracking. 
This study trained and fine-tuned a suite of pre-trained models like VGG16, ResNet50, InceptionV3, DenseNet201, and MobileNetV2 alongside a custom CNN on a balanced ASL dataset of 27 handshape classes.

## 🔗 Resources

### 📊 Dataset
The dataset used in this project is publicly available on Kaggle:  
👉 [Kaggle Dataset Link](https://www.kaggle.com/datasets/grassknoted/asl-alphabet/data)

### 🤖 Trained Models
- VGG16
- ResNet50
- DenseNet201
- InceptionV3
- MobileNetV2
- Custom CNN
The pretrained model files (`.h5`, `.pkl`) are hosted on Kaggle:  
👉 [Model Download Link](https://www.kaggle.com/models/siddhantbahadkar/huge_models)

## ⚙️ Configuration
Configuration files are available in the `config/` folder.

## 📈 Results
- Validation Accuracy: 93.18%
- Test Accuracy: 98.77%  
Visual results and confusion matrix are included in the notebook.

## 🧩 Tools Used
- Python, TensorFlow, Keras, OpenCV
- Matplotlib, Seaborn
- Jupyter Notebook

## 🗂️ Repository Structure

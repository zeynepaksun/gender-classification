# Gender Classification with Deep Learning

## This is a small project to perform gender classification using deep learning techniques. The custom CNN Architecture is added on top of the Inception-v3 architecture for feature extraction and classification. It is developed using Google Colab for using GPU resources to perform efficient training.

## The dataset can be found here: https://www.kaggle.com/datasets/abhikjha/utk-face-cropped/data

## Requirements
- Basic Python understanding and deep learning concepts
- UTK Face Cropped Dataset (provided above)
- Colab Account (recommended)
  
## Setup
1. **Clone Repository**: Directly open it on Colab or use it on your local machine.
  ```bash
git clone https://github.com/zeynepaksun/gender-classification.git
```
2. **Open "classification.ipynb"**
3. **Connect your Google Drive**: If you are using Colab, download the dataset from the link and put it in your drive folders.
4. **Dependencies**: To make sure it goes smoothly, install the dependencies listed in the notebook (if necessary) by using ```!pip install```
5. **Load Dataset and Preprocessing**: After putting the dataset into the directory, make sure you run the first cells to perform label splitting. Make sure you replace the file paths according to your folders. This is a one time operation, after using the "savez" to convert the arrays into npz format you can directly take them from the npz file that will be created in your directory.
6. **Explore**: You can try different approaches, architectures and even visualization techniques.

## Acknowledgement
- Multiple resources, such as online resources and research papers, are inspired from.

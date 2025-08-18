
## <div align="justify"> Title - Intelligent Image Classification System with Deep Learning </div>

##  Introduction

<div align="justify">
Image classification is a core task in computer vision that enables systems to automatically identify and categorize objects in images. Traditional approaches often struggle with scalability, feature generalization, and performance on diverse datasets. To address these challenges, this project introduces an intelligent image classification system powered by deep learning. Leveraging Convolutional Neural Networks (CNNs) and transfer learning (MobileNetV2), the system efficiently extracts hierarchical visual features, enabling robust classification of large and complex image datasets. The framework is equipped with a Gradio-powered user interface, allowing users to upload images, interactively classify them, and visualize predictions with confidence scores. This project demonstrates the potential of modern deep learning pipelines in building accurate, scalable, and user-friendly image classification applications.
</div>

##  Structure 

├── dataset/  # Training & testing image dataset (organized by class folders)   

├── image_classification_code.ipynb  # Main Jupyter notebook with code & UI

├── requirement.txt # Required Python libraries for the project

## Setup Instructions

1. Clone the Repository

    Terminal - Command - Git Clone 

    https://github.com/Praisingh-Codes/Image-Classification.git

    cd Image-Classification


2. Create Virtual Environment

   Terminal - Command
   
   python -m venv venv

   (On Linux/Mac: source venv/bin/activate)
   
   (On Windows: venv\Scripts\activate)


3. Install Dependencies
   
   Terminal - Command
    
   pip install -r requirements.txt


4. Prepare Dataset

   Organize your dataset into subfolders, one per class:

   dataset/

      ├── class_1/
            ├── img1.jpg
            ├── img2.jpg
            ...

      ├── class_2/
            ├── img3.jpg
            ├── img4.jpg
            ...


5. Run the Jupyter Notebook
   
   Launch the notebook environment:
   
   jupyter notebook

   Run the cells in image_classification_code.ipynb to train and evaluate the model.


6. Use the Gradio Interfac
   
   Run the last cell of the notebook to launch the Gradio web app:
   
   - Upload any image for classification.

   - The system will return the predicted class and confidence score.

   - Supports multiple image uploads for batch testing.


## Conclusion

<div align="justify">
This project delivers a professional and scalable deep learning solution for image classification. By combining CNN architectures, transfer learning via MobileNetV2, and performance metrics such as accuracy, precision, recall, and confusion matrix visualization, the system ensures reliable and interpretable results. The inclusion of a Gradio-based web interface further enhances accessibility, enabling both researchers and end-users to classify images interactively with minimal effort. Overall, this system represents a robust and practical framework for deploying intelligent image classification models in real-world scenarios.
</div>

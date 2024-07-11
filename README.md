# Emotion-Detection-Using-CNN-and-FER-2013-Dataset
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral)

**Description:**
* **Addressed class imbalance** in the FER-2013 dataset by employing image augmentation and class weights, improving model robustness.
* Designed and **iterated on custom CNN models**, including advanced architectures such as VGG16 and ResNet50v2, to optimize performance.
* Achieved a **66% overall accuracy** on emotion classification with the final model based on ResNet50v2, detailed through precision, recall, and F1 scores across 7 emotion labels.
* **Deployed the model** for real-time emotion detection in live video streams using Gradio and OpenCv, showcasing emotion label dynamically on screen.

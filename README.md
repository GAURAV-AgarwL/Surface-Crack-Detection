# Surface-Crack-Detection

An exploratory project leveraging Convolutional Neural Networks (CNNs) to automatically detect surface cracks in structural elements using deep learning techniques, implemented with Keras and TensorFlow under the guidance of Dr. Basuraj Bhowmik.

## INTRODUCTION

Surface cracks are among the earliest indicators of structural deterioration. Manual inspection methods are time-consuming, labour-intensive, and prone to human error. This project builds an automated approach using a CNN model to detect cracks accurately and efficiently before they escalate into severe damage.
Developed as an exploratory project in Structural Engineering during B.Tech in Civil Engineering at IIT (BHU), Varanasi, under the supervision of Dr. Basuraj Bhowmik, this work demonstrates the integration of machine learning and deep learning on the core applications of civil engineering.

## LITERATURE REVIEW

Several studies on deep learning techniques in recent years have gained significant attention in the field of SHM. Convolutional Neural Networks (CNNs), however, have emerged as a powerful tool for image classification tasks due to their ability to extract spatial features from raw images automatically. Numerous studies have demonstrated the effectiveness of CNNs in crack detection. One has developed a deep learning-based method for crack classification in concrete structures and reported high accuracy under diverse environmental conditions. Researchers have also explored the use of transfer learning and data augmentation techniques to improve generalisation on limited datasets. The use of Keras and TensorFlow has become common in implementing such models due to their flexibility and ease of use.

## METHODOLOGY

The project was conducted in a step-by-step manner, beginning with the collection of a dataset of surface images that included both cracked and non-cracked samples sourced from publicly available platforms like Kaggle. The images were meticulously reviewed and labelled according to their results to ensure the accuracy of the dataset.
Next, the labelled images were randomly divided into training, validation, and test sets. This random sampling was done to enhance the model's performance across the entire dataset.
Using the Keras library, a Convolutional Neural Network (CNN) model was developed, with multiple layers to train the data. The model was trained to automatically extract spatial features relevant to crack detection from the training data. We used several layers in the model.

Throughout the training process, we implemented a strategic approach using multiple epochs and employed an early stopping callback. This allowed us to halt training when the validation accuracy plateaued or the loss ceased to improve, effectively preventing overfitting. Then we made the call for the epochs.
After training, the model's performance was evaluated using the test dataset. Metrics such as accuracy and loss were recorded, and their trends were visualised to assess the learning behaviour and reliability of the model. We plotted graphs depicting accuracy and loss, clearly demonstrating their variations with the number of epochs.

## CONCLUSION AND FUTURE WORK

We can conclude that the model successfully demonstrated the use of a convolutional neural network (CNN) for detecting surface cracks in structural images.  By training the model on a labelled dataset of cracked and non-cracked surfaces, the CNN achieved reliable accuracy and effectively identified patterns indicative of damage. The use of early stopping ensured optimal training without overfitting, and evaluation metrics confirmed the model's robustness. The results highlight the potential of deep learning as a powerful tool for automating structural health monitoring and reducing the reliance on manual inspection.

As for future aspects, we can think of a dataset with more diverse and real-world images captured under varying environmental conditions. Additionally, deploying the trained model in a mobile or embedded system could enable real-time crack detection on-site. Integration with drone or robotic inspection systems can also be explored for large-scale infrastructure monitoring.

## REFERENCES

1. Zhang, L., Yang, F., Zhang, Y. D., & Zhu, Y. J. (2019). Road crack detection using a deep convolutional neural network. Mathematical Problems in Engineering, 2019, Article ID 6520620. 
https://doi.org/10.1155/2019/6520620
2. Qayyum, S., Khan, M. A., Hussain, N., Alhaisoni, M., & Rehman, A. (2021). A robust and efficient approach for pavement crack detection using a deep convolutional neural network. Neural Computing and Applications,33(13),7071–7086. 
https://doi.org/10.1007/s00521-021-05690-8

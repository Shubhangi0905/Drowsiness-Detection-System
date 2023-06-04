# Driver Drowsiness Detection using Deep Learning

Driver drowsiness is a critical issue that poses a significant risk to road safety. The objective of this project is to develop a deep learning model for driver drowsiness detection using the MRL Eye Dataset. The model aims to classify driver eye images and determine whether a driver is alert or drowsy, thereby helping prevent accidents and improve driver safety.

## Dataset

The MRL Eye Dataset was utilized in this project. This dataset comprises eye images of drivers in different states of drowsiness. It serves as the foundation for training and evaluating the deep learning model.

## Model Architecture

Transfer learning was employed to build the deep learning model, leveraging the InceptionV3 architecture. By utilizing pre-trained weights from InceptionV3, the model can extract relevant features from the input images effectively. This approach accelerates the training process and enhances the model's performance.

## Model Training and Evaluation

The model was trained, validated, and tested using various evaluation metrics to measure its performance. During training, the model learned to differentiate between alert and drowsy states based on the input eye images. The evaluation metrics were employed to assess the model's accuracy, precision, recall, and F1 score.

## Results

The evaluation of the model using the selected metrics demonstrated promising results. The model achieved high accuracy, precision, recall, and F1 score, indicating its effectiveness in detecting driver drowsiness accurately.

## Conclusion

In conclusion, this project proposed a deep learning model for driver drowsiness detection using transfer learning based on the InceptionV3 architecture. The model was trained on the MRL Eye Dataset, which contains eye images of drivers in various states of drowsiness. Through comprehensive evaluation, the model exhibited reliable performance in distinguishing between alert and drowsy drivers. By alerting drivers when drowsiness is detected, this project can contribute to accident prevention and overall improvement in driver safety.

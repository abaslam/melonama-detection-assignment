# Multiclass Classification Model using a custom Convolutional Neural Network in TensorFlow. 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
  
## Technologies Used
- Augumentor
- numpy
- pandas
- matplotlib
- sklearn
- tensorflow
- glob

## Conclusion
- Training and Validation Accuracy Graph:

    - Training Accuracy (Blue Line): This line is steadily increasing, which suggests the model is learning and improving its ability to correctly classify the training data over time.
    - Validation Accuracy (Orange Line): This line is more volatile and generally lower than the training accuracy. It shows improvements but with significant fluctuations, which may suggest the model isn't generalizing as well to new data as it is to the training data.

- Training and Validation Loss Graph:

    - Training Loss (Blue Line): The loss decreases sharply at first and continues to decrease over time, which is expected as the model is optimizing its parameters to minimize the loss on the training data.
    - Validation Loss (Orange Line): It decreases initially but then has an overall increasing trend with fluctuations, indicating the model is not performing as well on the validation set as on the training set, and could be overfitting.

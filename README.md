  This project consists of a model that can accurately recognize food items from images and estimate their calorie content, enabling users to track their dietary intake and make informed food choices.
# 1. Food Recognition Model

1. **Data Preparation**:
 Dataset:-Food-101, which contains over 100,000 food images across 101 categories.
The images are organized into a folder structure, with each category having its own subfolder.
2. **Loading Images and Labels**: 
given a function to load images from the dataset directory.
The function reads images, resizes them to a specified size (e.g., 64x64 pixels), and collects them into an array.
And also extracted the corresponding labels (food categories) for each image.
3. **Label Encoding**:
To train a machine learning model, I have encoded the food category labels into integer values using LabelEncoder.
This step ensures that the model can work with categorical labels.
4. **Train-Test Split**:
Split the data into training and testing sets using train_test_split.
The training set will be used to train the model, while the testing set will evaluate its performance.
5. **Training the Model**:
Trained the model for 100 epochs, monitoring its loss and accuracy during training.
6. **Saving the model**:

# 2. Calorie Estimation Model

1. **Regression Model for Calorie Estimation**:
   - Build a regression model that predicts calorie values based on the recognized food categories.
   - The architecture includes convolutional layers, max-pooling layers, and fully connected layers.
   - The output layer consists of a single neuron (for regression) without activation.
   - Train this model using the calorie labels you've prepared.

2. **Training and Evaluation**: 
   - Split the data into training and testing sets for calorie prediction.
   - The model will learn to estimate calorie values from food images.
   - After training,evaluate its performance using the Mean Absolute Error (MAE).

3. **Saving the Model**:
   - Once trained, we'll save the model as "calorie_model.task5" for future use.
# Contact
For any inquiries, please reach out to me at:
- Email: [akhilaraveendranpm@gmail.com](akhilaraveendranpm@gmail.com)
- LinkedIn: [akhilaraveendranpm](https://www.linkedin.com/in/akhila-raveendran-pm)


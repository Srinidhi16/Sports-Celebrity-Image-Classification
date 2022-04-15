# Sports-Celebrity-Image-Classification

This project is to classify the images of sports celebrities with the use of Machine learning models.
The images of Sports Celebrities used are Roger Federer, Virat Kohli, Serena Williams, Maria Sharapova, Lionel Messi.

# Approach
Using Haar Cascade, which is an object detection machine learning algorithm for face recognition. Used face and eye cascades to get cropped images of the celebrities.

Using Fourier Transform  which is a processing tool used to decompose an image into its sine and cosine components. The output of the transformation represents the image in the Fourier or frequency domain, while the input image is the spatial domain equivalent.

![image](https://user-images.githubusercontent.com/60066112/163627571-caf15f70-91e1-447e-a329-cbc2c7cc2ee9.png)

# Training Models
Trained the image data with Random Forest, SVM and Logistic Reression with Hyperparameter tuning using GridSearchCV

# Accuracy
- SVM : 0.84
- Random Forest : 68
- Logistic Regression : 0.84

# CONCLUSION

![image](https://user-images.githubusercontent.com/60066112/163627603-0474ef00-9ea1-4f66-a3c6-3aaa21ef2647.png)

From the confusion matrix diagram, the diagonal represents on how many samples our model predicted correctly.

- The model has correctly predicted all samples of maria_sharapova and virat_kohli.
- For the image of lionel_messi, one instance incorrectly predicted as maria_sharapova and other as serena_williams
- For the image of roger_federer, 2 instances incorrectly predicted as maria_sharapova and other 2 as serena_williams
- For the image of serena_williams, one instance incorrectly predicted as roger_federer

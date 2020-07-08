# Image-Classification-Python-Project
Would like to start with giving due credit to codebasics YouTube channel for the project; to be able to follow it to complete it. Credit to StackOverflow as well for enhancing my learning. The project classifies the image of the sports star: Lionel Messi, Maria Sharapova, Roger Federer, Serena Williams and Virat Kohli. Applied Haar-cascade feature extraction and then Wavelet transformation. Drew Confusion Matrix to visualize the accuracy of the prediction (compared 'Predicted' vs 'Truth'). Finally, did manual clean-up of the faulty images. Applied GridSearchCV to evaluate best fit method among Support Vector, Random Forest and Logistic Regression. In the end, applied SVM with 'rbf' kernel via Pipeline method.

# Folder/Files information:
- Inside Model folder: 
   -- Dataset folder contains all the sample images of the sports celebrities(lionel_messi, maria_sharapova, roger_federer, serena_williams, virat_kohli)
   -- Cropped Folder that gets created automatically recognizing the facial features of the celebrity. No need to create it manually. Can be deleted initially and will get
      created automatically when you run the code in the jupyter notebook.
      
      
- OpenCV folder:
  -- contains haar cascades xml files (pre-trained feature extraction)

- Test images folder:
  -- contains images used for testing the prediction of the trained SVM model

- requirements.txt file contains the necessary library and version required for the project

- Script_For_Scrapping_Images.ipynb will help you scrap images from google automatically. Saving your manual efforts

- Sports_Person_Classification_Model.ipynb file is the main jupyter notebook for the model creation and saving it later as pickle file

# Results info:
  -- After the model being trained, SVM method generates prediction accuracy of 85%
  -- Saved model into pickle file using joblib
  -- save_model.pkl is the saved model pickle file.

# Ongoing task
  -- Learning Flask framework to be able to deploy end to end.....

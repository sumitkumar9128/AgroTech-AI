<a id="top"></a>
<div style="display:none;" align="center">
<h1><font size="10"> AgroTech AI </font></h1>

![image](https://github.com/user-attachments/assets/4c4855a7-3256-4878-8cbf-7ef4ecefa058)

![image](https://github.com/user-attachments/assets/bb2da5d2-fe19-4cfd-a410-0efa8c02366e)

![image](https://github.com/user-attachments/assets/5b57a69a-d450-4530-bd76-88b02a85a4de)
    
<!-- repo intro -->

</div>
<div align="center">

<h3><font size="4">AgroTech AI platform is a comprehensive web-based tool where users can access various machine learning models for making accurate predictions related to agriculture. It offers solutions for crop management, soil health assessment, pest control, and more.</h3>
<br>
Make sure you star the repository and show your love to us💗
</font>
<br>
<br>
<p>

## Why to Open Source

Contributing in open source increases your opportunities to work with different projects and mentors, getting to know various insights and ideas. It is a platform where contributors grow together with a construvtive and a positive attitude.
This repository also provides one such platforms where contributers come over and put their ideas  and make our website as interactive as much they can!

<table>
    <tr>
      <th>Event Logo</th>
      <th>Event Name</th>
      <th>Event Description</th>
    </tr>
    <tr>
        <td><img src="https://user-images.githubusercontent.com/63473496/213306279-338f7ce9-9a9f-4427-8c2a-3e344874498f.png#gh-dark-mode-only" width="200" height="auto" loading="lazy" alt="GSSoC 24"/></td>
        <td>GirlScript Summer of Code 2024</td>
        <td>GirlScript Summer of Code is a three-month-long Open Source Program conducted every summer by GirlScript Foundation. It is an initiative to bring more beginners to Open-Source Software Development. 
    </tr>
</table>

![GitHub issues](https://img.shields.io/github/issues/manikumarreddyu/AgroTech-AI)
![GitHub forks](https://img.shields.io/github/forks/manikumarreddyu/AgroTech-AI)
![GitHub pull requests](https://img.shields.io/github/issues-pr/manikumarreddyu/AgroTech-AI)
![GitHub Repo stars](https://img.shields.io/github/stars/manikumarreddyu/AgroTech-AI)
![GitHub contributors](https://img.shields.io/github/contributors/manikumarreddyu/AgroTech-AI)


</p>

</div>

<details>
    <summary><h2>:pushpin:Table of Contents: </h2></summary>


1. [Project Description](#project-description)
2. [TechStack](#techstack)
3. [Screenshots](#screenshots)
4. [Video](#video)
5. [Code of Conduct](#code-of-conduct)
6. [Setting Up on your machine](#setting-up-on-your-machine)
7. [How to Contribute](#how-to-contribute)
8. [Our Contributors](#our-contributors)
9. [License](#license)

</details>
<hr>

## Project Description

AgroTech AI platform is a comprehensive web-based tool where users can access various machine learning models for making accurate predictions related to agriculture. It offers solutions for crop management, soil health assessment, pest control, and more.

It implements machine learning algorithms to implement 3 basic functionalities:
# 1. Fertilizer Prediction
Aims to predict the appropriate fertilizer based on environmental and soil conditions. The dataset contains various features like temperature, humidity, moisture, soil type, crop type, and the levels of nitrogen, potassium, and phosphorus in the soil. The model aims to recommend the correct fertilizer to use, improving crop yield and soil health.
 
# Dataset: 
Fertilizer Prediction.csv (Uploaded under notebooks)
 
# Model Development :
A Random Forest Classifier was chosen as the primary model due to its robustness and high accuracy in classification tasks. The dataset was split into training and testing sets in an 80:20 ratio.
Key steps:

# Label Encoding: 
Categorical variables (Soil Type, Crop Type, and Fertilizer Name) were encoded using LabelEncoder.
# Model Training: 
A Random Forest model was trained using the training data.
# Hyperparameter Tuning: 
A grid search with cross-validation was applied to find the optimal parameters for the Random Forest model.

# 2. Crop Prediction
Implements a machine learning-based crop recommendation system using various classification algorithms to predict the best crop for farming based on the soil and environmental conditions. The model takes features such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall as inputs and predicts the most suitable crop for a particular set of conditions.

# Dataset:
Crop_recommendation.csv(Uploaded under notebooks)

# Model Training and Results
Four different models were trained on the dataset to predict the crop:
The results of each model are as follows:

1. Logistic Regression: 96.18%
2. Decision Tree Classifier: 97.82%
3. Gaussian Naive Bayes: 99.45%
4. Random Forest Classifier: 99.45%
The final model selected for deployment is the Random Forest Classifier.

# 3. Soil Quality Prediction 
Implements machine learning models to classify soil quality based on various features like nitrogen content, pH levels, organic carbon, and other nutrients. The goal of the model is to predict the quality of soil using logistic regression and a Support Vector Machine (SVM) model.

# Dataset:
Soil_Quality.csv (Uploaded under notebooks)

# Model Traning and Results
1. Logistic Regression
Logistic Regression is used to model the soil quality based on the provided features. The dataset is split into training and testing sets, and the logistic regression model is trained on the training data.

2. Support Vector Machine (SVM)
A Support Vector Machine with an RBF (Radial Basis Function) kernel is trained as an alternative model. The SVM model aims to find the decision boundary that best separates different soil quality classes.

3. Performance Evaluation
The performance of both models is evaluated using accuracy. The accuracy of each model is calculated by comparing the predicted soil quality labels with the actual labels in the test dataset.

# 4. Yield Prediction
Aims to develop a machine learning-based model for predicting crop yields based on various environmental and agricultural factors. The primary objective of this project is to create a model that predicts the total crop yield for a given region using data such as Area and type of crop, Year of cultivation, Average rainfall (in mm per year), Pesticide usage (in tonnes), Average temperature (in °C)

# Dataset:
yield_df.csv (Uploaded under notebooks)

# Model Training and Results
Various machine learning regression algorithms are applied, and the performance is evaluated based on metrics like Mean Squared Error (MSE).
The results of the models used are as follows:
1. Linear Regression
Mean Squared Error : 80852.08620158922
Score 0.09879301553673503

2. K Neighbors Regressor
Mean Squared Error : 55183.1146293406
Score 0.5801883304861266

3. Decision Tree Regressor
Mean Squared Error : 13211.190235825037
Score 0.9759383181169221

4. Random Forest Regressor
Mean Squared Error : 10135.46523142438
Score 0.9858378410451943

5. Gradient Boosting Regressor
Mean Squared Error : 34773.822585474634
Score 0.833295640875001

6. XGB Regressor
Mean Squared Error : 13451.947664464684
Score 0.975053338957936Linear Regression
Mean Squared Error : 80852.08620158922
Score 0.09879301553673503

The Random Forest Regressor was found to have the lowest MSE, making it the most suitable model for crop yield prediction. This model was selected for deployment and future predictions.

## TechStack

- React
- Tailwind
- python - Flask
- Node
- MongoDB
- Express
- Machine Learning
- Deep Learning

<hr>

## ⚙️ Getting Started / 📥 Installation

Ready to contribute to this fun project? Here's how to set up your development environment:
<br>
Make sure you follow our contributing guidlines:-  [here](https://github.com/RamakrushnaBiswal/PlayCafe/blob/main/CONTRIBUTING.md) 

1. **Fork this repository** 🍴 and clone it to your local machine:
   ```bash
   git clone https://github.com/manikumarreddyu/AgroTech-AI.git
2. **Install the required Python packages for Flask backend 🐍:**
   ```bash
   pip install -r requirements.txt
3. **Start the Flask server ⚡:**
   ```bash
   python app.py
4. **Install the dependencies for React frontend 🧩:**
   ```bash
   npm install
5. **Run the development server ⚡:**
   ```bash
   npm run dev
6. Open your browser at `http://localhost:3000` to see the project running! 🌟

<!-- Code of conduct -->
<div>
<h2><img src = "https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png" width="35" height="35"> Code of Conduct</h2>
</div>

Please note that this project is released with a [Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.



<div>
  <h2><img src="https://github.com/Meetjain1/wanderlust/assets/133582566/90f3930e-5a12-4a4e-8ac9-0dc7d5396adb" width="35" height="35">Are Ready to Contribute?</h2>
</div>

If you would like to contribute to the project then kindly go through [Contributing Guidelines](CONTRIBUTING.md) to understand everything from setup to necessary instructions.

<hr>
<h2 align = "center">Our Contributors ❤️</h2>
<div align = "center">
 <h3>Thank you for contributing to our repository</h3>

<p><a href="https://github.com/manikumarreddyu/AgroTech-AI/contributors">
  <img src="https://contributors-img.web.app/image?repo=manikumarreddyu/AgroTech-AI" />
  
</a></p>

</div>
<!-- License -->
<div>
<h2><img src = "https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Page%20with%20Curl.png" width="35" height="35"> License:</h2>
</div>

This project is licensed under the MIT License. See the [LICENSE](https://github.com/manikumarreddyu/AgroTech-AI/blob/main/LICENSE) file for more details.

<hr>
<div>
  Don't forget to leave a star<img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" width="35" height="30"> for this project!
</div> <br>

<a href="#top" style="position: fixed; bottom: 20px; right: 20px; background-color: black ; color: white; padding: 10px 20px; text-align: center; text-decoration: none; display: inline-block; border-radius: 5px; font-family: Arial; font-size: 16px;">Go to Top</a>

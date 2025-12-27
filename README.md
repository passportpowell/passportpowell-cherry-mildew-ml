# 🍒 Powdery Mildew Detection System for Cherry Leaves

[![Heroku Deployment](https://img.shields.io/badge/Deployment-Heroku-purple)](https://otis-project-5.herokuapp.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Languages](https://img.shields.io/github/languages/top/passportpowell/passportpowell-cherry-mildew-ml)](https://github.com/passportpowell/passportpowell-cherry-mildew-ml)

> A machine learning powered Streamlit dashboard that detects powdery mildew on cherry leaves from images in real time.

---

## 🚀 Live Demo

Try the live app here:  
**https://otis-project-5.herokuapp.com/**  
*(If you see a “set_page_config() can only be called once per app” error, refresh the page.)*

![Home page](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685702149/Project%205/page_0_xs57da.png)

---

## 📌 Project Description

The Powdery Mildew Detection System for Cherry Leaves automates visual detection of powdery mildew, a common fungal disease that harms cherry plantations and reduces yields. Using machine learning and image analysis, the system classifies leaf images as **healthy** or **infected**, saving manual inspection time and improving reliability.

---

## 🧠 Business Requirements

1. Visually distinguish between healthy and powdery mildew-infected leaves.  
2. Predict mildew presence in uploaded leaf images.

---

## 📈 Business Case

We trained a binary supervised classification model with the goal of achieving high accuracy (95%+). The model outputs a prediction flag and probability indicating whether a leaf has powdery mildew. Plantation staff can capture and upload leaf images and receive real-time predictions through the app.

---

## 📊 Dataset

Images were sourced from a cherry leaf dataset on **Kaggle** that contains 4,208 images of both healthy leaves and those with powdery mildew. Users can visit the dataset here:

https://www.kaggle.com/codeinstitute/cherry-leaves

---

## 🧪 Methodology & Model Development

1. **Data Preprocessing:** Resize, normalize, and split leaf images into train and test sets.  
2. **Model Selection:** Explore CNN architectures (e.g., VGG, ResNet, MobileNet).  
3. **Model Training:** Train the selected model and optimize performance.  
4. **Model Evaluation:** Validate using accuracy, confusion matrices, and other metrics.  
5. **Deployment:** Integrate the trained model into a Streamlit dashboard for real-time use.

---

## 🖼️ Dashboard Pages

### 📌 Page 1: Project Overview  
Overview of goals and dataset summary.  
![Home page](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685702149/Project%205/page_0_xs57da.png)

### 📌 Page 2: Leaves Visualizer  
Visualizes differences and galleries of leaf images.  
![Page 2](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685699850/Project%205/page_2_czp5oa.png)

### 📌 Page 3: Powdery Mildew Detector  
Upload images to see predicted results and probabilities.  
![Page 3](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685699850/Project%205/page_3_ljexqt.png)

### 📌 Page 4: Project Hypothesis & Validation  
Explains how predictions compare to expert visual labels.  
![Page 4](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685699850/Project%205/page_4_akaosh.png)

### 📌 Page 5: ML Performance Metrics  
Displays confusion matrix, accuracy history, and set distributions.  
![Page 5](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685699850/Project%205/page_5_1_zrkiom.png)  
![Page 5](https://res.cloudinary.com/dbqkng7cd/image/upload/v1685699850/Project%205/page_5_2_i1or1e.png)

---

## 🐛 Bugs

Bugs and issues are tracked in the [Project Dashboard](https://github.com/users/passportpowell/projects/6/views/1?layout=table).

---

## 🚢 Deployment

This app is deployed on **Heroku**. Deployment instructions included:

1. Create a Heroku app.  
2. Connect the GitHub repository to Heroku.  
3. Deploy the selected branch.  
4. If slug size is large, add unneeded files to `.slugignore`.

---

## 🧰 Libraries Used

- **NumPy** – numerical operations  
- **Matplotlib** – visualizations  
- **Seaborn** – statistical plots  
- **Plotly** – interactive charts  
- **Streamlit** – web UI  
- **scikit-learn** – ML utilities  
- **TensorFlow & Keras** – deep learning  
- **Pandas** – data manipulation  
- **pandas-profiling** – EDA reports  
- **protobuf** – data serialization

---

## 📚 Acknowledgements

- Base code and dashboard design adapted from the “Mildew Detection in Cherry Leaves” template from Code Institute.  
- Supported by Code Institute resources and Slack community.  
- Mentored by Rohit Sharma.

---

## 📄 License

This project is released under the **MIT License**. Feel free to use, modify, or share it.

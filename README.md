# ♻️ AI-Based Recycling Management System (YOLOv8 + Streamlit)

##  Project Overview

This project is an AI-powered recycling management system that automatically detects and classifies waste into categories such as **plastic, paper, and metal** using computer vision. The system helps improve recycling efficiency by reducing manual effort and increasing accuracy.


##  Features

* Real-time waste detection using camera input
* Classifies waste into **Plastic, Paper, Metal**
* Built using **YOLOv8 object detection model**
* Simple and interactive **Streamlit web interface**
* Fast and accurate predictions


##  Tech Stack

* **Programming Language:** Python
* **Model:** YOLOv8 (Ultralytics)
* **Libraries:** OpenCV, NumPy, Pandas
* **Frontend/Backend:** Streamlit
* **Tools:** LabelImg (for annotation)


##  How It Works

1. Collect and label dataset images (plastic, paper, metal)
2. Train YOLOv8 model on labeled data
3. Load trained model in Streamlit app
4. Capture image from camera or upload image
5. Model predicts and displays waste category


##  Project Structure

```
├── streamlit_app/
│   └── app.py
├── waste_YOLOv8.ipynb
├── .gitignore
└── README.md
```


##  How to Run the Project

### Step 1: Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### Step 2: Install dependencies

```
pip install -r requirements.txt
```

### Step 3: Run Streamlit app

```
streamlit run streamlit_app/app.py
```


## Results

* Achieved good accuracy in detecting waste categories
* Real-time detection works efficiently with webcam input

# Final Project - Emotion Detection Application

## 📌 Repository Name Requirement

This repository is part of the **oaqjp-final-project-emb-ai** assignment.

---

## 📖 Project Description

This project is a web-based **Emotion Detection Application** that analyzes user input text and detects emotions such as:

* Anger
* Disgust
* Fear
* Joy
* Sadness

It also identifies the **dominant emotion** using the IBM Watson NLP API.

---

## ⚙️ Technologies Used

* Python
* Flask
* IBM Watson NLP API
* HTML, CSS, JavaScript

---

## 📁 Project Structure

```
final_project/
│
├── emotion_detection.py
├── server.py
├── test_emotion_detection.py
│
├── templates/
│   └── index.html
│
├── static/
│   └── mywebscript.js
```

---

## 🚀 How to Run the Application

### 1. Install dependencies

```
pip install flask requests
```

### 2. Run the server

```
python server.py
```

### 3. Open in browser

```
http://localhost:5000
```

---

## 🧪 Running Unit Tests

```
python test_emotion_detection.py
```

---

## ⚠️ Error Handling

* If user input is empty → displays:

```
Invalid text! Please try again!
```

---

## 📊 Example Output

Input:

```
I love my life
```

Output:

```
For the given statement, the system response is 'anger': 0.006..., 'disgust': 0.002..., 'fear': 0.009..., 'joy': 0.968... and 'sadness': 0.049.... The dominant emotion is joy.
```

---

## 🎯 Conclusion

This project demonstrates:

* API integration
* Emotion analysis
* Web deployment using Flask
* Unit testing and error handling

---



# 🌟 Medical Chatbot Project 🌟

## 🚀 Project Overview

Welcome to the **Medical Chatbot**, your interactive health assistant! This Python-based chatbot provides information about **diseases**, including **causes** and **precautions**. Simply enter the name of a disease, and get instant health advice in a user-friendly manner.

Implemented in a **Jupyter Notebook** and powered by a **JSON dataset**, this chatbot currently supports **15 common diseases** and can be easily extended with more.

## ✨ Features

* ✅ Interactive chatbot in Jupyter Notebook.
* ✅ Provides causes and precautions for 15 diseases.
* ✅ Automatically creates and loads the dataset.
* ✅ Easy to extend with more diseases.
* ✅ Lightweight and user-friendly interface.

## 🛠️ Technologies Used

* **Python 3**
* **JSON** for disease data
* **Jupyter Notebook** for interactive execution
* **OS module** for file path management

## 📋 Dataset

The **diseases.json** file includes 15 diseases:

1. Diabetes
2. Malaria
3. Hypertension
4. Asthma
5. COVID-19
6. Flu
7. Arthritis
8. Tuberculosis
9. Hepatitis
10. Dengue
11. Chickenpox
12. Eczema
13. Pneumonia
14. Migraine
15. Obesity

Each disease contains:

* **Causes**: Brief description of what causes the disease.
* **Precautions**: List of steps to prevent or manage the disease.

## 💡 How to Use

1. Open `medical_chatbot_notebook.ipynb` in Jupyter Notebook.
2. Run the cells sequentially:

   * Import libraries
   * Detect folder path
   * Define dataset
   * Save dataset to `diseases.json`
   * Load dataset
   * Define chatbot function
   * Run the chatbot
3. Enter the **disease name** when prompted.
4. Receive **causes** and **precautions** instantly!

## 🌟 Extending the Project

* Add more diseases by updating the `diseases_data` dictionary.
* Integrate with **real medical APIs** for dynamic data and advanced recommendations.
* Customize the chatbot interface to make it more interactive.

## 🖥️ Example Usage

```
Welcome to the Medical Chatbot!
Enter a disease name to get causes and precautions:
diabetes

Disease: Diabetes
Causes: Genetic factors, obesity, lack of exercise, unhealthy diet.
Precautions:
1. Maintain a healthy weight
2. Exercise regularly
3. Monitor blood sugar levels
4. Take medications as prescribed
```
Made with ❤️ for learners and developers interested in healthcare technology.

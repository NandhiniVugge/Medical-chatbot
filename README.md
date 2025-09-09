# Medical Chatbot using AIML, JSON, and Pandas

## 📌 Project Overview

This project is a **Medical Chatbot** that allows users to input their symptoms and receive possible diseases and precautions. The chatbot uses **AIML** for conversation handling, a **JSON dataset** for disease information, and **Pandas** to display and query the dataset dynamically.

---

## 💡 Features

* **Interactive Chatbot:** Responds to greetings and unknown queries using AIML.
* **Symptom-based Diagnosis:** Users can enter symptoms to receive possible diseases and suggested precautions.
* **Dynamic Dataset:** A JSON file stores **10 common diseases** with symptoms and precautions.
* **Pandas Integration:** Visualizes and queries the dataset in a tabular format.
* **Extensible:** New diseases or symptoms can easily be added to the JSON file.

---

## 🛠 Technologies Used

* **Python**: Programming language for chatbot logic.
* **AIML (`python-aiml`)**: Handles conversational patterns and fallback responses.
* **JSON**: Stores symptom-disease mapping and precautions.
* **Pandas**: Displays and queries the dataset in a readable table.
* **Requests** *(optional)*: Can be used for integrating external medical APIs in the future.

---

## ⚙️ How It Works

1. **Setup:** Install necessary libraries (`python-aiml`, `pandas`, `requests`).
2. **AIML File:** The `medical.aiml` file contains greeting and fallback patterns.
3. **JSON Dataset:** `diseases.json` contains 10 diseases with their symptoms and precautions.
4. **Pandas DataFrame:** Loads JSON data to display in a tabular format and query dynamically.
5. **Chat Interaction:**

   * User inputs a symptom.
   * AIML handles greetings or unknown responses.
   * Pandas searches the dataset and prints possible diseases and precautions.
6. **Exit:** Type `quit` to close the chatbot.

---

## 📝 Sample Interaction

```
Welcome to the Medical Chatbot (AIML + Dynamic Dataset)!
Type 'quit' to exit.

You: I have fever
Chatbot (AIML): 
Symptom: Fever
Possible Diseases: Flu, COVID-19
Precautions: Rest, Drink water, Monitor temperature, Consult doctor

You: headache
Symptom: Headache
Possible Diseases: Migraine, Stress
Precautions: Rest, Hydrate, Avoid screen strain

You: quit
Chatbot: Goodbye! Stay healthy.
```

---

## 📂 Project Structure

```
medical_chatbot_notebook.ipynb  # Main Jupyter Notebook
medical.aiml                     # AIML conversation file
diseases.json                    # JSON dataset of symptoms and diseases
```

---

## 🔧 How to Run

1. Open the Jupyter Notebook.
2. Run all cells sequentially.
3. Enter symptoms when prompted.
4. Type `quit` to exit.

---

## 🚀 Future Improvements

* Integrate **external medical APIs** for real-time disease information.
* Expand the dataset beyond 10 diseases.
* Add **machine learning** to predict diseases from multiple symptoms.
* Develop a **web or mobile interface** for easier access.

---

## ✅ Conclusion

This project provides a **simple yet effective** medical chatbot that can help users quickly identify possible diseases and precautions based on symptoms. It also demonstrates integration of **AIML for chatbot logic**, **JSON for dynamic data**, and **Pandas for interactive data querying**.


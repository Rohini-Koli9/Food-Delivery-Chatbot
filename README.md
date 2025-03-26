# 🍔 Food Delivery Chatbot

An AI-powered chatbot for a food delivery system, designed using **Dialogflow, FastAPI, and MySQL** to handle customer queries, process orders, and provide a seamless food ordering experience.

---

## 🚀 Features

- **Intelligent Query Handling**: Utilizes **Dialogflow** to process user queries with intents, entities, and contexts.
- **Order Fulfillment**: Fetches real-time order details and availability from a **MySQL database**.
- **FastAPI Backend**: Manages chatbot responses and interacts with the database efficiently.
- **Web Integration**: Easily deployable with a web interface for a smooth user experience.

---

## 🛠️ Tech Stack

- **Backend**: FastAPI, Python
- **NLP Engine**: Dialogflow
- **Database**: MySQL
- **Frontend**: (Optional) React.js/HTML + JavaScript
- **APIs**: Google Dialogflow API

---

## 📌 Installation & Setup

### 1️⃣ Clone the Repository
```bash
 git clone https://github.com/yourusername/food-delivery-chatbot.git
 cd food-delivery-chatbot
```

### 2️⃣ Install Dependencies
```bash
pip install fastapi uvicorn mysql-connector-python google-cloud-dialogflow
```

### 3️⃣ Set Up Dialogflow
- Create a Dialogflow agent and configure **intents, entities, and fulfillment**.
- Download your **Google Cloud service account JSON key** and set it as an environment variable:
  ```bash
  export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/json-key.json"
  ```

### 4️⃣ Configure Database
- Create a MySQL database and update **config.py** with your credentials.
- Run the SQL script to initialize tables.

### 5️⃣ Run the Server
```bash
uvicorn main:app --reload
```

---

## 📝 Usage
- The chatbot can process food orders, check availability, and handle customer inquiries.
- Users interact via the **web interface** or **API requests**.

---

## 🤖 Future Enhancements
- Payment gateway integration
- Personalized food recommendations
- Multi-language support

---

## 🤝 Contributing
Feel free to submit issues and pull requests to improve the chatbot!

---

## 📜 License
This project is licensed under the MIT License.

---

### 📧 Contact
For any queries, reach out to: [rohiniKoli076@gmail.com](mailto:rohiniKoli076@gmail.com)

---

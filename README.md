# 🤖 AI Chatbot Mini Project (.NET)

## 📌 Project Overview

This project is an **AI-based Chatbot Desktop Application** developed using **.NET Windows Forms**.
The chatbot interacts with users in real-time by integrating with the **Groq AI API**, providing intelligent responses based on user input.

---

## 🎯 Objectives

* To build a smart chatbot using AI API integration
* To understand real-time API communication
* To implement user-friendly desktop UI
* To containerize the application using Docker

---

## 🚀 Features

* 🧠 AI-powered chatbot responses
* 💬 Real-time conversation interface
* 🖥️ Windows Forms user interface
* 🔌 API integration (Groq AI)
* ⚠️ Error handling & validation
* 📦 Docker support

---

## 🛠️ Technologies Used

* .NET (Windows Forms)
* C#
* Groq API (AI Integration)
* Newtonsoft.Json
* HttpClient
* Docker

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/your-repo-name.git
```

### 2️⃣ Open in Visual Studio

* Open the solution file (`.sln`)
* Restore NuGet packages

### 3️⃣ Install Required Package

```
Newtonsoft.Json
```

### 4️⃣ Add Your API Key

Open `Form1.cs` and replace:

```
private readonly string apiKey = "YOUR_API_KEY";
```

---

## ▶️ Run the Application

* Press **F5** in Visual Studio
* Enter a message
* Click **Send**
* View AI response

---

## 🐳 Docker Setup

### Build Docker Image

```
docker build -t ai-chatbot .
```

### Run Container

```
docker run -it --rm ai-chatbot
```

---

## 🧩 System Workflow

1. User enters input
2. Application sends request to Groq API
3. AI processes the request
4. Response is returned
5. Output displayed in chat interface

---

## 🖼️ Screenshots

* UI Interface
* Chat Interaction
* API Response

(Add your screenshots here)

---

## 🧪 Testing

| Input        | Output      |
| ------------ | ----------- |
| Hello        | AI greeting |
| How are you? | AI response |

---

## 📊 Results & Discussion

* Successfully implemented AI chatbot
* Real-time API communication works efficiently
* Minor dependency on internet connectivity

---

## ⚠️ Limitations

* Requires active internet connection
* API rate limits may apply
* Basic UI design

---

## 🔮 Future Improvements

* Voice-based chatbot
* Enhanced UI/UX design
* Chat history storage
* Multi-language support

---

## 🔐 Security Note

⚠️ Do not expose your API key publicly. Always regenerate your key before deployment.

---

## 👨‍💻 Author

Muhammad Usama Bilal

---

## ⭐ Contribution

Feel free to fork and improve this project!

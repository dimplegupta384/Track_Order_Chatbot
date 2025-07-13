 Track Order Chatbot

A smart, conversational chatbot built to help users easily track their product orders in real-time using basic NLP techniques. Ideal for customer support simulations or integration with e-commerce systems.

---

 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Folder Structure](#folder-structure)
- [How It Works](#how-it-works)
- [Sample Interaction](#sample-interaction)
- [Getting Started](#getting-started)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

---

 Features

- Track order status by order ID  
- Friendly chatbot interface  
- Predefined intents and fallback handling  
- NLP-based input recognition  
- Easily extendable for real-world use cases  

---

 Tech Stack

- **Language**: Python  
- **NLP**: Custom rule-based or Dialogflow  
- **Backend (Optional)**: Flask  
- **Data Format**: JSON for intents and responses  

---

 Folder Structure

Track_Order_Chatbot/
├── chatbot.py # Main chatbot logic
├── intents/ # Folder containing predefined user intents
├── utils.py # Optional helper functions
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

 How It Works

1. User sends a query (e.g., "Track order #1234")  
2. Chatbot extracts the order ID using basic NLP or rules  
3. Responds with a simulated status (e.g., "Out for delivery")  
4. Fallback response for unknown or unsupported queries  

---

 Sample Interaction

User: Where is my order #5678?
Bot: Your order #5678 is currently out for delivery.


---

 Getting Started

 1. Clone the repository
```bash
git clone https://github.com/dimplegupta384/Track_Order_Chatbot.git
cd Track_Order_Chatbot


2. Install dependencies
pip install -r requirements.txt

3. Run the chatbot
python chatbot.py

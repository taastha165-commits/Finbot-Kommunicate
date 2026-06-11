# 💰 FinBot – AI-Powered Finance Chatbot

## 📖 Overview

FinBot is an intelligent finance chatbot built using **Google Dialogflow Essentials** and integrated with **Kommunicate**. The chatbot provides instant responses to finance-related queries and helps users understand financial concepts such as investments, loans, insurance, budgeting, credit scores, NPV, IRR, and financial ratios.

The project demonstrates the application of **Conversational AI** and **Natural Language Processing (NLP)** in the finance domain to deliver quick, interactive, and user-friendly financial assistance.

---

## 🚀 Features

✅ Investment Guidance

✅ Loan & EMI Assistance

✅ Insurance Advisory

✅ Credit Score Information

✅ Budget Planning Support

✅ Financial Ratio Explanations

✅ NPV & IRR Information

✅ Real-Time Conversational Interface

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| Dialogflow Essentials | Intent Recognition & NLP |
| Kommunicate | Chatbot Deployment |
| NLP | Query Processing |
| Conversational AI | User Interaction |

---

## 📂 Project Architecture

```text
User
  ↓
Kommunicate Chat Widget
  ↓
Dialogflow Agent
  ↓
Intent Detection
  ↓
Response Generation
  ↓
User Receives Financial Guidance
```

---

## 💬 Supported Queries

```text
What is NPV?
Explain IRR
What is EMI?
Suggest investment options
Insurance advice
What is a credit score?
How do I create a budget?
Explain current ratio
What is financial leverage?
```

---

## 🔗 Kommunicate Integration Code

Add the following code to your website to integrate the chatbot:

```html
<script type="text/javascript">
(function(d, m){
    var kommunicateSettings =
    {
        "appId":"YOUR_APP_ID",
        "popupWidget":true,
        "automaticChatOpenOnNavigation":true
    };

    var s = document.createElement("script");
    s.type = "text/javascript";
    s.async = true;
    s.src = "https://widget.kommunicate.io/v2/kommunicate.app";

    var h = document.getElementsByTagName("head")[0];
    h.appendChild(s);

    window.kommunicate = m;
    m._globals = kommunicateSettings;

})(document, window.kommunicate || {});
</script>
```

---

## 🤖 Example Dialogflow Intent

### Intent Name: NPV

**Training Phrases**

```text
What is NPV?
Explain NPV
Define Net Present Value
Tell me about NPV
```

**Response**

```text
Net Present Value (NPV) is a capital budgeting technique used to determine the profitability of an investment by calculating the difference between the present value of cash inflows and cash outflows.
```

---

## 🎯 Objectives

- Automate responses to common financial queries.
- Improve financial literacy and awareness.
- Demonstrate the use of Conversational AI in Finance.
- Provide an interactive user experience.
- Enable quick access to financial knowledge.

---

## 📸 Screenshots

### Welcome Screen
![Welcome Screen](screenshots/welcome.png)

### NPV Intent
![NPV Intent](screenshots/npv.png)

### Insurance Advisor
![Insurance Advisor](screenshots/insurance.png)

### Kommunicate Integration
![Kommunicate Integration](screenshots/integration.png)

---

## 📚 Learning Outcomes

- Dialogflow Agent Creation
- Intent Training & Management
- NLP-Based Chatbot Development
- Kommunicate Integration
- Finance Domain Knowledge Implementation
- Conversational AI Deployment

---

## 🔮 Future Enhancements

- Real-Time EMI Calculator
- Mutual Fund Recommendation System
- Stock Market Integration
- Voice-Based Chatbot
- Multi-Language Support
- Personalized Financial Planning

---

## 👩‍💻 Author

**Aastha Thakur**  
MBA (Applied Finance)

---

## ⭐ Project Summary

FinBot is an AI-powered finance chatbot that helps users understand financial concepts and make informed decisions through natural conversations using Dialogflow and Kommunicate.

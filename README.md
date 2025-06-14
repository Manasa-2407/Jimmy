# 🤖 JIMMY A CHATBOT – CURRENCY CONVERTER

Jimmy is a smart AI-powered chatbot that helps users **convert currencies** instantly through a conversational interface. Built to simulate a natural and user-friendly experience, Jimmy acts like your personal assistant for real-time currency conversion.


## 💡 Project Overview

Jimmy is designed using **Dialogflow** to understand natural language queries and respond with accurate currency conversions. The bot takes user inputs like:

- 💬 “Convert 100 dollars to rupees”
- 💬 “How much is 50 euros in yen?”

...and returns the corresponding amount based on live exchange rates.


## 🔧 Features

- 💱 Converts from one currency to another
- 🧠 Understands natural language inputs
- 🗣️ Interactive and real-time response
- 🌍 Supports multiple currencies (USD, INR, EUR, JPY, etc.)
- 🔌 Built using Dialogflow

## 🧪 How It Works

1. **User** types: “Convert 50 dollars to rupees”
2. **Dialogflow** matches the intent `currency.convert`
3. **Parameters extracted**: amount = 50, from = USD, to = INR
4. **Response**:
   - If API connected: Real-time converted value
   - Else: Pre-defined or mock value


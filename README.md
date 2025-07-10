# RoastBot GPT – The Hindi-English Chat Roaster Bot 

This bot automates the art of witty roasting in group chats. Built using `pyautogui`, `pyperclip`, and `OpenAI`, it reads the last message from a user , uses GPT to generate a humorous roast response, and pastes it back into the chat — fully automated.

---

## Features

- Reads selected chat content automatically  
- Uses OpenAI’s GPT model to generate funny, bilingual roast replies  
- Automates mouse/keyboard actions to interact with the chat app  
- Copies and pastes text using system clipboard  
- Character: An Indian coder named *Naruto* with a funny, sarcastic tone  

---

## Files

| File                | Description                                |
|---------------------|--------------------------------------------|
| `chat_bot.py`       | Main automation + GPT logic                |
| `pointer_location.py` | Utility to get real-time mouse coordinates |
| `Requirements.txt`  | Required Python libraries                  |

---

## Setup & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/roast-bot-gpt.git
cd roast-bot-gpt
```
### 2. Install Dependencies

```bash
pip install -r Requirements.txt
```


### 3. Add Your OpenAI API Key

Edit chat_bot.py and replace:

api_key = "<api_key>"

with your actual OpenAI API key.

### 4. Get Mouse Coordinates

Use pointer_location.py to locate:

    Where to click to activate chat

    Where to drag-select chat text

    Where to paste and send the roast

Run:
```bash
python pointer_location.py
```
Then hover the mouse over target areas and copy coordinates into chat_bot.py.

### 5. Run the Bot

Once everything is configured:
```bash
python chat_bot.py
```
Make sure your chat app (e.g., WhatsApp Web) is visible and focused.

### Requirements

    Python 3.8+

    Desktop environment (Windows/Linux/macOS with GUI)

    Chat app with accessible UI (WhatsApp Web, Messenger, etc.)

### Tech Stack

    pyautogui – For simulating user interactions

    pyperclip – For clipboard operations

    openai – To generate AI-powered roast replies

### Author

    Made by Shreya Kumari
    Enjoy!


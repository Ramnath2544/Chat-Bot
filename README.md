# Chat Bot

---

**<h2>Overview</h2>**

**<h3>Chatbot UI with React</h3>**
A sleek and interactive chatbot interface built with React, featuring an auto-scrolling chat window, dynamic interactivity, and polished styling with custom CSS.

---

## 🚀 Features  

- 🎨 **Custom UI** – Clean and modern chatbot interface  
- ⚡ **Interactive Elements** – Engages users with smooth interactions  
- 🖌️ **Stylish Design** – Fully styled using CSS for a professional appearance  
- 🔄 **Auto-Scrolling Chat** – Automatically scrolls to the latest response using `useEffect` and `useRef`

### ⌨️ Enter Key Features

### Smart Enter Handling
- Enter Key: Sends the message (same as clicking Send button)
- Shift + Enter: Allows new lines in the input (for multi-line messages)
- Prevents Default: Stops the default form submission behavior

### Enhanced User Experience
- Faster Typing: Users can now press Enter to send messages quickly
- Natural Feel: Mimics popular chat applications like WhatsApp, Discord, etc.
- Multi-line Support: Hold Shift + Enter to create line breaks if needed

### How it Works
- `handleKeyPress` function: Listens for key press events
- Enter detection: Checks if Enter key is pressed (without Shift)
- Prevents default: Stops the browser's default Enter behavior
- Triggers send: Calls the same `sendMessage()` function as the Send button

### User Benefits
- ✅ Faster messaging: No need to reach for the mouse
- ✅ Keyboard-friendly: Great for power users
- ✅ Intuitive: Standard chat app behavior
- ✅ Accessible: Better for users with mobility issues

Now users can simply type their message and press `Enter` to send it instantly, making the chat experience much more fluid and natural! 🚀

---

## 📖 Project Journey  
This project evolved step by step through the following commits:  

1. **Chatbot UI Creation**  
   - Initial chatbot interface design was implemented.  

2. **Interactivity Added**  
   - Made the chatbot interactive to enhance user experience.  

3. **Polished with CSS**  
   - Styled the chatbot with CSS for a professional appearance.  

4. **Auto-Scrolling Feature**  
   - Used React hooks (`useEffect`, `useRef`) to make the chat window scroll automatically.  

---

## 🛠️ Tech Stack  

- **Frontend:** React  
- **Styling:** CSS  
- **State & Hooks:** useState, useEffect, useRef

--- 

## 🎯 Future Improvements  

- Integrate with an AI backend (e.g., GPT API)  
- Add support for multiple conversation threads  
- Include emoji and multimedia support  

---

## 👤 Author  

**Ramnath**  
📧 [ramnath2544@gmail.com](mailto:ramnath2544@gmail.com)  










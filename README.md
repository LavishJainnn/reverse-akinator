# Reverse Akinator 🤖🎭

An AI-powered terminal-based reverse guessing game inspired by Akinator.

In this version, the AI already knows the character, and **you** must figure it out by asking smart questions. The system responds using dataset-based reasoning with the help of AI agents built using [CrewAI](https://www.crewai.com/?utm_source=chatgpt.com).

The project demonstrates:

* Multi-agent AI workflows
* Tool usage in CrewAI
* Dataset-based reasoning
* Interactive terminal gameplay
* Simple AI game logic using LLMs

Based on the uploaded source code and execution logs. 

---

# 🚀 Features

* 🎮 Interactive command-line gameplay
* 🤖 Multi-agent architecture using CrewAI
* 🧠 AI-powered question answering
* 🔍 Dataset-driven reasoning
* 💡 Dynamic hints system
* ✅ True / False / BINGO responses
* 🎭 Reverse Akinator concept

---

# 🧠 How It Works

The game contains:

* A hidden character dataset
* An AI agent that answers questions
* A hint-generation AI agent
* A custom CrewAI tool for dataset checking

The user asks questions like:

```text
Is he fictional?
Is he a human?
Is he from a movie?
```

The AI responds with:

* `True`
* `False`
* `BINGO!`
* `False. Inappropriate question`

When the character is guessed correctly, the game ends.

---

# 🛠️ Tech Stack

* Python
* CrewAI
* Gemini 2.0 Flash
* LLM Agents
* Custom Tools

---

# 📂 Project Structure

```bash
reverse-akinator/
│
├── main.py          # Main game logic
├── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/LavishJainnn/reverse-akinator.git
cd reverse-akinator
```

---

## 2️⃣ Create Virtual Environment (Optional but Recommended)

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install crewai
```

You may also need:

```bash
pip install google-generativeai
```

---

# ▶️ Run the Project

```bash
python main.py
```

---

# 🎮 Example Gameplay

```text
Ask a question (or guess the character): Is he fictional?
Answer: True
Hint: You are going in the right direction!

Ask a question (or guess the character): Is he a human?
Answer: True

Ask a question (or guess the character): Pushpa Raj
Answer: BINGO!

🎉 You guessed it right! Game Over.
```

Example interaction taken from the uploaded execution logs. 

---

# 🧩 AI Agents Used

## 1️⃣ Question Answering Agent

Responsible for:

* Understanding the question
* Calling the dataset checking tool
* Returning accurate answers

Defined in the source code here: 

---

## 2️⃣ Hint Agent

Responsible for:

* Giving subtle hints
* Encouraging the player
* Responding based on previous answers

Defined here: 

---

# 🔧 Custom Tool

The project includes a custom CrewAI tool called:

```python
CheckTool(BaseTool)
```

It checks user questions against the dataset and returns:

* True
* False
* BINGO
* Inappropriate question

Implementation available here: 

---

# 📊 Dataset Example

The current hidden character dataset contains:

* Character Name
* Source
* Gender
* Profession
* Fictional Status
* Hero/Villain info
* Language
* Personality traits
* Movie details

Dataset defined in the source code. 

---

# ✨ Future Improvements

* Multiple characters support
* Random character selection
* Web-based UI using Streamlit
* Better NLP understanding
* Scoring system
* Difficulty levels
* Voice interaction
* Larger datasets
* Database integration

---

# 🤝 Contributing

Contributions are welcome.

## Steps

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is open-source and available under the MIT License.

---

# 👨‍💻 Author

Built by **Lavish Jain**

GitHub: [LavishJainnn GitHub](https://github.com/LavishJainnn)

Repository: [Reverse Akinator Repository](https://github.com/LavishJainnn/reverse-akinator)

---

⭐ If you like this project, give it a star on GitHub!

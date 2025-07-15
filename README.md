## Project1

# 📝 Word Counter GUI Application

A simple and user-friendly Python application that counts the number of words in a given input using a Tkinter-based GUI.

---

## 📌 Features

- ✅ Word counting from user input
- ✅ Clean, interactive Tkinter GUI
- ✅ Error handling for empty inputs
- ✅ Organized, modular code with reusable functions

---

## 🎨 GUI Design Choices

| Component       | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| 🎯 Framework    | Built using Python’s built-in Tkinter library for easy deployment           |
| 🧠 Structure     | Uses separate functions (`count_words`, `on_submit`) for modular design     |
| 🚫 Error Handling | Gracefully handles empty input by returning 0                              |
| 👁️ UX Design    | Includes a label, entry field, submit button, and result output label       |

---

## 🔍 How It Works

1. The user enters text into the entry field.
2. On clicking "Submit", the app counts words using regex.
3. The total word count is displayed below the button.

---

## 📦 Installation & Usage

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/word-counter-gui.git
cd word-counter-gui
```

### 2. Run the Application

```bash
python word_counter_gui.py
```

✅ Make sure you have Python 3.x installed.

---

## ⚙️ Technologies Used

- Python 3.x
- Tkinter (built-in GUI framework)
- re (regular expressions for word detection)

---

## ⚠️ Known Challenges

- 🧩 Regex may be complex for beginners, but offers efficient word extraction
- 🎨 Tkinter has limited styling capabilities (for advanced UI, explore PyQt or customTkinter)

---

## 🚀 Future Enhancements

- Add character count or sentence analysis
- Implement real-time text monitoring
- Improve styling with themes or alternative GUI frameworks
- Add support for file input and saving results

---

## 📄 Code Organization

| Function        | Role                                               |
|----------------|----------------------------------------------------|
| count_words()   | Uses regex to calculate number of words            |
| on_submit()     | Callback function triggered by button click        |

---

## 🧠 Example Output

> Input: "This is a simple test."  
> Output: Word Count: 5

---



## Project2

📝 Word Counter – Tkinter GUI Application

A simple desktop application built using Python and Tkinter that allows users to input text and view the word count with a click.

---

## 📐 Design Choices

### 🧱 Tkinter GUI Framework
Used Tkinter, a built-in Python GUI library, for simplicity and ease of deployment. It offers a straightforward and lightweight interface ideal for small applications.

### 📚 Separation of Concerns
The code is modular, with functions like:
- `count_words()`: Logic to count words using regex.
- `on_submit()`: Handles user input submission and updates UI.

This structure improves maintainability and makes future updates easier.

### 🚫 Error Handling
Handled empty input gracefully. The application returns a word count of 0 if no text is provided.

### 🎯 User-Friendly Interface
Designed a clean and intuitive interface with:
- A text entry field
- A submit button
- A result label displaying word count

---

## 🧩 Challenges

- 🔠 Regular Expressions: Regex was used for efficient word matching. While powerful, it may be tricky for beginners to understand and maintain.
- 🎨 Styling Limitations: Tkinter supports only basic styling. Advanced UI features may require customTkinter, PyQt, or Kivy.

---

## 🚀 Features

- ✅ Real-time word counting
- 🖱️ Interactive GUI with input and result display
- 🔄 Robust error handling for empty input

---

## ✨ Possible Enhancements

- 📏 Character and sentence counters
- 🌍 Support for text from external files or URLs
- 🧪 Real-time analysis as the user types
- 🎨 Improved styling with themed widgets or alternative frameworks
- 📘 Code documentation with inline comments and dev instructions

---

## 🛠️ Technologies Used

- Python 3.x
- Tkinter
- Regular Expressions (`re` module)

---

## ▶️ Usage

1. Clone or download the repository.
2. Run the script using:

```bash
python word_counter_gui.py
```

3. Enter text in the GUI window and click "Submit" to view the word count.

---

## 🧠 Example

> Input: “Hello world! This is a test.”  
> Output: Word Count: 6

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

Made with ❤️ by Kirti Vardhan Singh  
📧 Email: kirtivardhan7549@gmail.com



# ✨ Calculator Web Application

## 💡 Project Overview
This is a simple yet fully functional **Calculator Web Application** built using HTML, CSS, and JavaScript. The calculator allows users to perform basic arithmetic operations including addition, subtraction, multiplication, and division.

---

## 🔧 Features
- **Arithmetic Operations:** Addition (+), Subtraction (-), Multiplication (*), Division (/)
- **Clear Display:** Reset the entire display using the **AC** button
- **Delete Function:** Remove the last digit entered using the **DE** button
- **Decimal Support:** Perform calculations with floating-point numbers
- **Responsive Design:** Works seamlessly across different devices

---

## 📝 How to Use
1. Open the calculator in your web browser.
2. Enter numbers and operators by clicking the buttons.
3. Use the **AC** button to clear the entire display.
4. Use the **DE** button to delete the last digit.
5. Press the **=** button to display the result.

---

## ⚙️ Code Explanation

### HTML Structure
- **Container Div:** Holds the main calculator layout.
- **Input Display:** Shows the user input and results.
- **Buttons:** Each button triggers operations or inputs through `onclick` events.

### CSS Styling
- Centered layout with a visually appealing structure.
- Styled buttons with hover effects and distinct operator colors.
- Minimalistic and clean design.

### JavaScript Logic
- **Event Handling:** Button clicks dynamically update the calculator display.
- **Operator Functions:** The `eval()` method evaluates user-entered mathematical expressions.
- **Error Handling:** Clear (`AC`) and delete (`DE`) features for better user control.

Example Code Snippet for Button Operations:
```javascript
<input type="button" value="=" class="equal operator" onclick="display.value = eval(display.value)">
```

---

## 🛠️ Installation & Usage
1. Clone or download the project.
2. Open the `index.html` file in your preferred web browser.

---

## 🛡️ Safety Note
Using `eval()` in JavaScript can be risky if the input isn't controlled or sanitized. This project is for educational purposes and assumes safe usage.

---

## 🌟 Future Enhancements
- Keyboard support for input.
- Advanced mathematical operations (e.g., square root, percentage).
- Enhanced error handling.
- More responsive design improvements.

---

## 👨‍💻 Author
**Harjot Singh**

Enjoy calculating! 💬


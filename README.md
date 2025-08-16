# Quiz-app

An interactive **Quiz Application** built using **HTML, CSS, and JavaScript**.  
This project demonstrates DOM manipulation, event handling, and basic JavaScript logic to create a dynamic quiz experience.

---

---

##  Features
- Displays one question at a time with multiple-choice options.
- User can select an answer, and immediate feedback is shown .
- Score tracking throughout the quiz.
- Restart option at the end of the quiz.
- **Timer** of 30 seconds per question ⏱️.
- Responsive and styled UI.

---

##  Approach
1. **HTML**: Created the quiz layout including question box, options, feedback section, score display, and restart button.  
2. **CSS**: Styled the quiz app for a clean and responsive design, added hover effects and color indicators for correct/incorrect answers.  
3. **JavaScript**:
   - Stored quiz questions in an array of objects.
   - Dynamically loaded questions and options using DOM manipulation.
   - Implemented a **scoring system** to keep track of correct answers.
   - Added a **30-second timer** per question using `setInterval()`.
   - Provided **restart functionality** to replay the quiz.

---

##  Challenges Faced
- Handling the **timer reset** for each new question.
- Ensuring that once an option is clicked, others are disabled to prevent multiple selections.
- Making the quiz UI responsive and user-friendly.
- Debugging path issues for CSS/JS files during hosting on Netlify/Vercel.

---

##  How to Run the Project Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/nupurchoksi/quiz-app.git

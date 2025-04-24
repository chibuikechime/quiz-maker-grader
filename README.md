# 🧠 Python Quiz Maker

This project is a simple quiz maker that helps users create and take multiple-choice quizzes. It is designed for learners who want to test their Python knowledge and for teachers who want to build their own question sets. The tool is interactive, beginner-friendly, and runs directly in a Jupyter Notebook.

## 🎯 Purpose

The main goal of this project is to make learning Python fun and hands-on. It allows users to take quizzes and also create new questions. This is helpful for practice, self-study, and teaching.

## 📦 What’s Inside

The notebook includes:
- A set of predefined Python quiz questions
- A function to add your own questions and answer options
- A function to take the quiz
- A scoring system that shows how many answers were correct
- A function to save results to a file

Each part of the code is explained with comments to help you understand what it does.

## ▶️ How to Use

1. Open the notebook in Jupyter or any compatible Python environment.
2. Run the cells in order.
3. Choose your role:
   - As an **admin**, you can add custom questions.
   - As a **student**, you can take the quiz.
4. After the quiz, your score will be shown and saved.

## 💡 Example Usage

```python
# Add questions (admin only)
add_custom_questions()

# Start the quiz
run_quiz()
```

## 🗂️ File Structure

- `quiz_questions`: Dictionary of questions, options, and answers.
- `add_custom_questions()`: Lets the admin add questions to the quiz.
- `run_quiz()`: Starts the quiz and shows score at the end.
- `save_score(name, score, total)`: Saves results to `quiz_scores.txt`.
- `main()`: Handles the program flow based on user role.

## ✅ Benefits

- Easy to understand
- No technical setup needed
- Useful for learning and teaching
- Extendable with more questions and features

## 👤 Author
This project was developed by Chibuike Chime.
If you have any feedback, ideas, or questions, feel free to reach out or contribute!
#RITAAfricaBootcamp #Python

Enjoy learning Python through quizzes!

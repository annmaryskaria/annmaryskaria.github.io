# adc-mcq-practice

Weekly MCQ practice app for the ADC written exam. Hosted on GitHub Pages — no installation, no server, just open and go.

---

## Live App

👉 [Open the Exam App](https://annmaryskaria.github.io/adc-mcq-practice/ADCMockApp.html)

---

## How to use

1. Open the live link above.
2. Click **Choose File** and upload your JSON question file from your computer.
3. Answer all questions and navigate freely using Next, Previous, or Jump to Question.
4. Click **Finish Exam** to see your results, correct answers, and explanations.

---

## Generating questions each week

1. Open `MockQuestionGeneratorPrompt.txt`.
2. Fill in the topic, difficulty, and question count at the bottom.
3. Paste into any AI and save the output as a `.json` file on your computer.
4. Upload it to the app when you're ready to practise.

---

## Repo structure

```
adc-mcq-practice/
├── ADCMockApp.html                  # The exam app
├── MockQuestionGeneratorPrompt.txt  # Prompt template for generating new questions
└── README.md
```

---

## Requirements

None. Pure HTML, CSS, and JavaScript. Works in any modern browser.

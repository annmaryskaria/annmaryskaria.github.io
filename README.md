# adc-mcq-practice

Weekly MCQ practice app for the ADC written exam. Hosted on GitHub Pages — no installation, no server, just open and go.

---

## Live App

👉 [Open the Exam App](https://YOUR-USERNAME.github.io/adc-mcq-practice/adc_exam_app.html)

> Replace `YOUR-USERNAME` with your GitHub username after enabling GitHub Pages.

---

## How to use

1. Open the live link above.
2. Upload a JSON question file from the `questions/` folder.
3. Answer all questions and navigate freely using Next, Previous, or Jump to Question.
4. Click **Finish Exam** to see your results, correct answers, and explanations.

---

## How to enable GitHub Pages

1. Go to your repo on GitHub.
2. Click **Settings → Pages**.
3. Under **Source**, select `main` branch and `/ (root)`.
4. Click **Save**. Your app will be live at `https://YOUR-USERNAME.github.io/adc-mcq-practice/`.

---

## Adding questions each week

1. Open `adc_mcq_prompt_template.txt`.
2. Fill in the topic, difficulty, and question count at the bottom.
3. Paste into any AI and save the output as a `.json` file.
4. Add the file to the `questions/` folder using the naming convention `week##_specialty.json`.
5. Commit and push — the new file is immediately available via the live app.

---

## Repo structure

```
adc-mcq-practice/
├── adc_exam_app.html              # The exam app
├── adc_mcq_prompt_template.txt   # Prompt template for generating new questions
├── questions/
│   ├── week01_general_medicine.json
│   └── ...
└── README.md
```

---

## Requirements

None. Pure HTML, CSS, and JavaScript. Works in any modern browser.

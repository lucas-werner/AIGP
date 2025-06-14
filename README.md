# AIGP Practice Quiz

This repository contains a single-page web application that provides an interactive practice quiz for the IAPP AI Governance Professional (AIGP) certification exam. The quiz includes 100 multiple-choice questions with rationale and scoring similar to the official test.

## Opening the Quiz

1. Clone or download this repository.
2. Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Edge, etc.). No additional server setup is required.

The page will load the quiz automatically and start a three‑hour timer when you press **Start**. You can restart the quiz at any time using the **Restart Quiz** button that appears once results are shown.

At the halfway point, the quiz pauses and shows a review screen. Use the flag icon on any question to mark it for review. Flagged questions from the first half appear on this mid-quiz review page so you can revisit them before continuing.

## Prerequisites

The HTML file references Tailwind CSS and Google Fonts via public CDNs and fetches `questions.json` for quiz data. Make sure your computer has internet access when you open `index.html` so these resources can be loaded.


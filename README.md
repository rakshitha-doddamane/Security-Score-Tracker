# Security+ Score Tracker

A small, fast web app for tracking how many practice questions you get **right** and **wrong** while studying for the CompTIA Security+ exam. Save each paper's score with a date and time, then see which papers you're weakest on.

**[Open the live app](https://rakshitha-doddamane.github.io/Security-Score-Tracker/)**


## Why I built it

When I practice for Security+, I take several papers and mock exams. Scrolling back through answer sheets to work out my accuracy was slow, and I couldn't see whether I was improving on a particular paper. I wanted one tap per question, a saved record, and a clear view of progress. This is that tool.

## Features

- **One-tap counting.** Big Right and Wrong buttons, plus a −1 button for mistakes.
- **Live accuracy.** Shows questions answered, percentage correct, and a progress bar.
- **Save with a stamp.** Saving records the paper name, right and wrong counts, percentage, and the date and time. A "SAVED" stamp confirms it.
- **Reset when you're ready.** Clear the counters for the next paper. Saved scores stay.
- **Progress by paper.** A table shows attempts, latest score, best score and average for each paper.
- **Full history.** Every saved score is listed, newest first, and can be deleted.
- **Keyboard shortcuts.** Press `R` for right and `W` for wrong.
- **Works on phone and desktop.** Responsive layout, with automatic light and dark mode.

![Saved scores and progress by paper](screenshots/progress.png)

## How to use it

1. Type the paper name, for example `Practice Test 1`. Use the same name each time you retake it.
2. Tap **Right** or **Wrong** after each question.
3. Press **Save score** when you finish the paper.
4. Press **Reset counters** and start the next paper.

## Privacy

There is no account, no server and no tracking. Your scores are stored in your browser's `localStorage` and never leave your device. The trade-off is that each browser keeps its own list, and clearing your browser data erases your scores.

## Built with

- HTML, CSS and vanilla JavaScript in a single file, with no frameworks or dependencies
- Browser `localStorage` for saving scores
- Google Fonts (Archivo and Source Sans 3)
- GitHub Pages for hosting

## Run it locally

```bash
git clone https://github.com/rakshitha-doddamane/Security-Score-Tracker.git
cd Security-Score-Tracker
```

Then open `index.html` in your browser. There is nothing to install or build.

## Ideas for later

- Tag each question by Security+ domain to see weak areas by topic
- Export scores to CSV
- Sync scores across devices

## License

Released under the [MIT License](LICENSE).

## Author

Built by **Rakshitha D H**, a computer science graduate focused on cybersecurity and GRC.
Find my writing on Medium and my other projects on [GitHub](https://github.com/rakshitha-doddamane).

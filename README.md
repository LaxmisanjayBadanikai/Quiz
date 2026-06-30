# Quiz App

A simple, interactive quiz application built with vanilla HTML, CSS, and JavaScript.

## Features

- **Interactive Quiz**: Answer multiple-choice questions with instant feedback
- **Score Tracking**: Automatically calculates your score as you progress
- **Restart Functionality**: Reset the quiz and try again at any time
- **Responsive Design**: Clean, dark-themed interface that works on all devices
- **Zero Dependencies**: Pure vanilla JavaScript - no frameworks or libraries needed

## How It Works

1. Click the **Start Quiz** button to begin
2. Read each question and click on your chosen answer
3. Click **Next Question** to proceed to the next question
4. After answering all questions, view your final score
5. Click **Restart Quiz** to play again

## Project Structure

```

quiz-app/
├── index.html          # Main HTML structure
├── style.css           # Styling and dark theme
├── script.js           # Quiz logic and interactivity
└── README.md           # Project documentation

```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with dark theme
- **JavaScript (ES6)** - Dynamic DOM manipulation and event handling

## Customization

### Adding New Questions

To add or modify questions, edit the `questions` array in `script.js`:

```javascript
const questions = [
  {
    question: "Your question here?",
    choices: ["Option A", "Option B", "Option C", "Option D"],
    answer: "Correct answer",
  },
  // Add more questions...
];
```

### Styling

- The dark theme can be customized by modifying the CSS variables in `style.css`
- Primary accent color is `#6200ea` (purple) - change to match your brand

## Getting Started

1. Clone or download this repository
1. Open `index.html` in your web browser
1. No build process, server, or installation required - it runs directly in the browser

## Browser Support

Works on all modern browsers:

- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## Future Improvements

- Add question categories
- Timer for each question
- Progress bar
- High score tracking with localStorage
- Animated transitions between questions
- Support for image-based questions
- Export results to CSV

Made with ❤️ using vanilla JavaScript


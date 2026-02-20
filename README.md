# Marks to Percentage Converter

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A web-based calculator that converts exam paper marks and MCQ scores into an overall module percentage. Built for the OOC1 (Object-Oriented Computing 1) module.

## Overview

This tool helps students quickly calculate their final module percentage by combining their written exam marks (out of 75, worth 70%) with their MCQ assessment scores (worth 30%). It provides real-time calculation as values are entered, with input validation and instant feedback. Hosted on GitHub Pages for easy access.

## Features

- Real-time percentage calculation as you type
- Combines exam marks (70% weighting) and MCQ scores (30% weighting)
- Input validation with clear error messaging
- Responsive layout using Bootstrap
- Hosted on GitHub Pages for instant access

## Prerequisites

- A **modern web browser** (Chrome, Firefox, Safari, or Edge)

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/marks-to-percentage-converter.git
   cd marks-to-percentage-converter
   ```

2. Open `index.html` in your browser.

### Usage

1. Visit [danielcregg.github.io/marks-to-percentage-converter](https://danielcregg.github.io/marks-to-percentage-converter/) or open `index.html` locally.
2. Enter your exam paper marks (0--75).
3. Enter your MCQ1 percentage (0--100).
4. Enter your MCQ2 percentage (0--100).
5. Your overall module percentage is displayed automatically.

**Calculation formula:**
- Exam component: `(marks / 75) * 70`
- MCQ component: `((MCQ1 + MCQ2) / 2) * 0.3`
- Total: Exam component + MCQ component

## Tech Stack

- **HTML5** - Page structure and form elements
- **JavaScript** - Real-time calculation logic
- **Bootstrap 4** - Responsive UI styling
- **GitHub Pages** - Static site hosting

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

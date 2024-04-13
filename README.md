# Basic HTML/CSS Quiz

This project is a simple quiz application built with HTML and CSS. It's designed to test basic knowledge of HTML and CSS. The quiz consists of multiple-choice questions and a text area for comments.

## Structure

The HTML structure of the quiz is defined in `BasicQuiz.html`. The main sections of the quiz are:

- **Student Info:** This section collects basic information about the student, including their name, email, and date of birth.

- **HTML Questions:** This section contains multiple-choice questions about HTML.

- **CSS Questions:** This section contains multiple-choice questions about CSS.

Each section is marked with `role="region"` for accessibility, and each question is contained within a `fieldset` element.

## Styling

The styling of the quiz is defined in `styles.css`. The CSS file includes styles for the body, header, navigation, main content, and footer. It also includes styles for form elements like labels, inputs, and textareas.

The color scheme of the quiz is a combination of `#f5f6f7` (light gray) for the background, `#1b1b32` (dark blue) for the text, and `#f1be32` (yellow) for headings.

The logo in the header is styled to maintain its aspect ratio and to scale its size based on the viewport width.

## Usage

To take the quiz, fill out your information in the "Student Info" section, answer the questions in the "HTML" and "CSS" sections, and then click the "Submit Quiz" button.

## Accessibility

The quiz is designed with accessibility in mind. Each section of the quiz is marked with `role="region"` and `aria-labelledby` to provide a descriptive name for the section. The contrast ratio between the text and background colors is high for readability.

## Future Improvements

Future improvements to the quiz could include adding JavaScript to validate the form inputs and to calculate the quiz score.
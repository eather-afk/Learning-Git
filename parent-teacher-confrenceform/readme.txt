# Parent Teacher Conference Form

A simple and clean parent-teacher conference form built using HTML and CSS. This project collects student information, parent/guardian details, preferred contact method, and additional notes for scheduling a parent-teacher meeting.

## Features

* Clean and structured HTML form
* Dark-themed design
* Centered form container
* Student information section
* Parent/guardian information section
* Preferred contact method using custom radio buttons
* Additional notes textarea
* Required input fields
* Placeholder text for guidance
* Submit button with hover effect
* Responsive layout with `width` and `max-width`

## Technologies Used

* HTML5
* CSS3

## Concepts Practiced

### HTML Concepts

* `form`
* `fieldset`
* `legend`
* `label`
* `input`
* `textarea`
* `button`
* `required` attribute
* `placeholder` attribute
* Radio buttons
* External CSS linking

### CSS Concepts

* Background color
* Text color
* Width and max-width
* Margin and padding
* Border and border-radius
* Box-shadow
* Text alignment
* Pseudo-classes like `:hover`, `:checked`, and `:not()`
* Pseudo-elements like `::before` and `::placeholder`
* Custom radio button styling
* CSS transitions
* CSS transforms

## Project Structure

```md
project-folder/
│
├── index.html
└── styles.css
```

## How It Works

The form is divided into different sections using `fieldset` and `legend`.

* **Student Information** collects the student’s name and grade.
* **Parent/Guardian Information** collects the parent or guardian name.
* **Preferred Contact Method** lets the user choose between email and phone.
* **Additional Notes** allows the user to write any concerns or discussion topics.

The radio buttons are customized using CSS. The default browser radio button style is removed using `appearance: none`, and a custom circle is created with `::before`. When the radio button is selected, the `:checked` pseudo-class makes the inner circle visible.

## Styling Overview

The page uses a dark midnight blue background with a semi-transparent form container. The form is centered using `margin: auto`, and the container has rounded corners and a shadow effect to make it look like a card.

The submit button changes color when hovered over, giving the form a more interactive feel.

## Learning Outcome

Through this project, I practiced creating a structured HTML form and styling it using CSS. I also learned how to customize form elements, use pseudo-classes and pseudo-elements, and create a clean user interface.

## Future Improvements

* Add email and phone input fields
* Add better form validation
* Make the design more responsive for small screens
* Add JavaScript functionality
* Connect the form to a backend or database

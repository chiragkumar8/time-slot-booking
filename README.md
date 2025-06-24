# Time Slot Booking
This is a simple web application that allows users to book a time slot by selecting a date and a specific time from a list of available slots. The application includes a form for user input, dynamic date restrictions, and interactive time slot selection with visual feedback.

![Product Name Screen Shot][product-screenshot]

<!-- MARKDOWN LINKS & IMAGES -->
[product-screenshot]: book-time-slot.png

## Project Overview

The Time Slot Booking application is a single-page web app that enables users to:

- Enter their name and mobile number.
- Select a date within a 7-day range from the current date.
- Choose a time slot from a predefined list.
- Submit the form to receive a confirmation message with the selected date and time.

The application uses HTML for structure, CSS for styling, and JavaScript for interactivity, including form validation and dynamic slot selection.
## Features

- **Responsive Form:** Input fields for name, mobile, date, and time slot selection.
- **Date Restrictions:** Users can only select dates from today up to 7 days in the future.
- **Interactive Time Slots:** Users can click time slots to select them, with visual feedback (highlighting the selected slot).
- **Form Submission:** Displays a confirmation message with the selected date and time slot.
- **Mobile-Friendly:** Responsive design with a clean and modern UI.

## How It Works

- The user loads the page and sees a form with fields for name, mobile number, date, and time slots.
- The date input is restricted to the current date and up to 7 days in the future.
- The user selects a time slot by clicking one of the available time slot buttons, which highlights the selected slot.
- Upon submitting the form, a confirmation message displays the selected date and time slot.

## Usage

- Open index.html in a web browser.
- Enter your name and mobile number.
- Select a date from the date picker (restricted to today + 7 days).
- Click a time slot to select it (the slot highlights with a blue background).
- Click "Book Now" to submit the form.
- View the confirmation message below the form.

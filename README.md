# Contact Form Project

This project includes a simple contact form that collects user information and feedback. Upon submission, the data is sent to an email address and the user is redirected to a feedback page confirming their submission.

## Features

- Collects user's name, email, phone number, gender, hobbies, a rating of their experience, and optional comments.
- Data is submitted to a specified email using FormSubmit.
- User receives a confirmation message after submission.

## Files

- `index.html`: The main HTML file containing the contact form.
- `feedback.html`: The HTML file displayed after successful submission.

## Usage

1. **Clone the repository** or download the files to your local machine.

   ```bash
   git clone <repository-url>
2. **Open** index.html in a web browser to view the form.

3. **Fill out the form** with the required information:

    - Name
    - Email
    - Phone Number
    - Gender
    - Hobbies (optional)
    - Rate your experience
    - Comments (optional)

4. **Submit the form.** You will be redirected to feedback.html, indicating that your information has been received.

## Configuration

- Update the action URL in the form to your email address for data submission:

```bash
action="https://formsubmit.co/your-email@example.com"
```

## Requirements
- A modern web browser to view and test the form.
- Internet access for form submission.

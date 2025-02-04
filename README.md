# Online Resume/CV Builder

This project is an online resume/CV builder that allows users to create professional resumes with ease. The application provides a user-friendly interface to input personal details, achievements, experiences, education, projects, and skills, and generates a formatted resume that can be printed or saved.

## Project Structure
         /project-root
      │── /assets            # Contains all static files (CSS, images, JavaScript)
      │   ├── /css           # Stores all stylesheet files
      │   │   ├── main.css   # Main stylesheet for the project
      │   │
      │   ├── /images        # Contains all images and icons used in the project
      │   │   ├── dublin-resume-templates.avif
      │   │   ├── curriculum-vitae.png
      │   │   ├── feature-1.svg
      │   │   ├── feature-2.svg
      │   │   ├── feature-3.svg
      │   │   ├── visual.svg
      │   │
      │   ├── /js            # Contains JavaScript files
      │   │   ├── app.js     # Main JavaScript file
      │   │   ├── script.js  # Additional script file for interactivity
      │
      │── index.html         # Homepage of the project
      │── resume.html        # Resume page for displaying resume templates
      
      


- **assets/css/main.css**: Contains the styles for the application.
- **assets/images/**: Contains images used in the application.
- **assets/js/app.js**: Contains the main JavaScript logic for form handling and resume generation.
- **assets/js/script.js**: Contains additional JavaScript for form repeater functionality.
- **index.html**: The home page of the application.
- **resume.html**: The resume builder page.

## Features

- **User-Friendly Interface**: Easy-to-use form to input personal details, achievements, experiences, education, projects, and skills.
- **Live Preview**: Real-time preview of the resume as the user inputs data.
- **Form Validation**: Validation for text, email, phone number, and other input fields.
- **Image Upload**: Option to upload a profile picture.
- **Print Resume**: Option to print the generated resume.

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.)
- Internet connection to load external libraries (jQuery, jQuery Repeater)

### Running the Application

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/online-resume-builder.git
    ```
2. Navigate to the project directory:
    ```sh
    cd online-resume-builder
    ```
3. Open `index.html` in your web browser to view the home page.
4. Click on "Create My Resume" to navigate to the resume builder page (`resume.html`).

## Usage

1. Fill in the form fields with your personal details, achievements, experiences, education, projects, and skills.
2. The resume preview will update in real-time as you input data.
3. Click on the "Print CV" button to print your resume.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- jQuery Repeater

## Acknowledgements

- Icons and images used in the project are sourced from various free resources.
- Special thanks to the contributors of jQuery and jQuery Repeater libraries.

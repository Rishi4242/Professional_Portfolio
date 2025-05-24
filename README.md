🎨 Rishi Teja Palugula – Developer Portfolio
Welcome to my personal portfolio website! This platform showcases my skills, projects, and provides an interactive way for visitors to get in touch with me directly through a contact form powered by EmailJS.

🚀 Features
Responsive Design: Optimized for desktops, tablets, and mobile devices.

Dynamic Contact Form: Send messages directly to my inbox without any backend setup.

Project Showcase: Explore my latest projects with detailed descriptions and live links.

Clean UI/UX: User-friendly interface with intuitive navigation.
GitHub
+2
EmailJS
+2
Medium
+2

🛠️ Built With
HTML5 & CSS3

JavaScript (ES6+)

EmailJS – For handling contact form submissions without a backend.

Figma – For designing the UI/UX components.
Medium
+9
GitHub
+9
YouTube
+9
EmailJS
+13
Dev Genius
+13
React.js Examples
+13

📬 Contact Form Integration with EmailJS
The contact form is seamlessly integrated using EmailJS, allowing visitors to send messages directly from the website.

📌 Setup Instructions
Sign Up on EmailJS: Create a free account at EmailJS.

Create Email Service:

Navigate to the Email Services section.

Click on Add New Service and connect your preferred email service (e.g., Gmail).

Create Email Template:

Go to the Email Templates section.

Click on Create New Template and design your email layout.

Use placeholders like {{from_name}}, {{from_email}}, and {{message}} to capture form data.

Obtain Credentials:

Service ID: Found in the Email Services section.

Template ID: Found in the Email Templates section.

Public Key: Available in your Account settings under API Keys.

Integrate into Your Code:

Initialize EmailJS with your Public Key:
GitHub
+2
Medium
+2
Dev Genius
+2

javascript
Copy
Edit
emailjs.init('YOUR_PUBLIC_KEY');
Handle form submission:
DEV Community
+1
EmailJS
+1

javascript
Copy
Edit
document.getElementById('contact-form').addEventListener('submit', function(event) {
  event.preventDefault();
  emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this)
    .then(function() {
      alert('Thank you! Your message has been sent successfully.');
      document.getElementById('contact-form').reset();
    }, function(error) {
      console.error('EmailJS Error:', error);
      alert('Oops! Something went wrong. Please try again later.');
    });
});
Ensure that the name attributes in your form fields match the placeholders in your EmailJS template.

📁 Project Structure
bash
Copy
Edit
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── script.js
├── images/
│   └── [profile and project images]
├── assets/
│   └── RISHI_TEJA-RESUME.pdf
└── README.md
📸 Live Demo
Experience the live version of my portfolio here.

🤝 Connect with Me
GitHub: Rishi4242

LinkedIn: Rishi Teja Palugula

Email: rishipatelpalugula@gmail.com

📄 License
This project is open-source and available under the MIT License.

Feel free to customize this README.md to better fit your personal style and the specifics of your project. If you need further assistance or have any questions, don't hesitate to ask!

# Aurora-Scholarship-repo
🌟 Aurora Scholarship Portal
Aurora Scholarship Portal is a web application designed to streamline the process of applying for, managing, and reviewing scholarship applications. Built with a sleek, responsive frontend using Tailwind CSS and custom components, the portal ensures a premium user experience for applicants, reviewers, and administrators.
🚀 Features

🎓 Scholarship application submission
📄 Auto-generated PDF from application data
📁 Document upload support (including Aadhar, photo, certificates)
🗂 Admin view of submitted applications
🔐 Secure data handling and validation
🧾 Aesthetic and clean UI built with Tailwind CSS

📁 Project Structure
Aurora-Scholarship-Portal/
├── index.html              # Landing page
├── appli.html              # Application form (PDF generation)
├── rregistration.html      # Registration form with document upload
├── aadm.html               # Admin view of application data
├── assets/
│   ├── css/                # Custom styles and Tailwind
│   └── js/                 # JavaScript files for form logic
├── images/                 # Logo and UI images
├── scripts/                # PDF and data handling scripts
└── README.md               # Project documentation

    
🛠 Tech Stack

Frontend: HTML5, Tailwind CSS, Custom CSS
Scripting: JavaScript
PDF Generation: jsPDF, html2canvas
Data Handling: LocalStorage / Form-based redirection

📝 How It Works

User fills out the application on appli.html.
PDF is generated automatically using jsPDF with embedded details and uploaded images.
Data is redirected to the admin page (aadm.html) for storage or review.
Admin can view submitted records and verify attached documents.

📦 Installation & Setup

Clone the repo:

git clone https://github.com/yourusername/Aurora-Scholarship-Portal.git
cd Aurora-Scholarship-Portal
    
Open index.html in your browser.

Note: This is a static web project. No backend integration yet. To enable full features like database storage, server-side validation, and email alerts, backend implementation is recommended.

🧩 To-Do

 Add backend support (Node.js / PHP / Firebase / etc.)
 Integrate database for storing applicant data
 Add email notifications
 Implement login system for applicants and admins
 Improve accessibility and cross-browser testing

🤝 Contributing
Contributions are welcome! Feel free to submit issues or pull requests.

Fork the project
Create your feature branch (git checkout -b feature/new-feature)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/new-feature)
Open a Pull Request

📄 License
This project is licensed under the [MIT License](LICENSE).
✨ Acknowledgements

Tailwind CSS — for utility-first styling
jsPDF & html2canvas — for smooth PDF creation
Inspiration from various open scholarship platforms

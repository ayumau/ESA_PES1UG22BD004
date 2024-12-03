# Aayush Maurya - Personal Portfolio

This is a responsive personal portfolio website to showcase skills, experiences, and projects. It includes sections for About, Resume, Portfolio, Blog, and Contact.

## Features

- **Responsive Design**: Works seamlessly across devices.
- **Customizable Layout**: Easily modify content and styles.
- **Sections**:
  - About: Personal introduction and skills.
  - Resume: Education and professional experience.
  - Portfolio: Showcase of projects.
  - Blog: Space for articles and updates.
  - Contact: Form and location.

## File Structure

```plaintext
.
├── index.html       # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css   # Custom styles
│   ├── images/         # Images and icons
│   └── js/             # Custom scripts
└── README.md        # Project documentation
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/portfolio.git
Navigate to the project folder:
bash
Copy code
cd portfolio
Open index.html in a web browser to view the portfolio.
Customization
HTML Content
Modify text and links in index.html to update the content.
Replace placeholder images in the assets/images folder.
CSS Styles
Update the color scheme, fonts, or layout in assets/css/style.css.
Key variables for customization are defined in the :root section.
Adding New Projects
Add a new item to the project-list in the Portfolio section of index.html:
html
Copy code
<li class="project-item active" data-filter-item data-category="web design">
    <a href="#">
        <figure class="project-img">
            <img src="./assets/images/new-project.png" alt="New Project" loading="lazy">
        </figure>
        <h3 class="project-title">New Project</h3>
        <p class="project-category">Web Design</p>
    </a>
</li>
Add the relevant image in the assets/images directory.
Development
To make further modifications:

Use a code editor (e.g., VS Code).
Install the Live Server extension for live preview.
Deployment
Deploy the website on a hosting platform like GitHub Pages, Netlify, or Vercel.
Upload all files, ensuring correct folder structure.
Contributing
Feel free to contribute by submitting issues or pull requests. Suggestions for improving the design and functionality are welcome.

Contact
Portfolio: Aayush Maurya
Email: mauryaaayush789@gmail.com
Phone: +91 8368244952
sql
Copy code

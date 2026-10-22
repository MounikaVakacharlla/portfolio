Mounika Vakacharlla --- DevOps Engineer Portfolio
A responsive personal portfolio website showcasing DevOps and cloud
engineering skills, workflow, experience, education, projects, training,
and contact information.
Overview
This portfolio is built with HTML, CSS, and vanilla JavaScript. It
uses a dark theme with teal accents and includes sections for:
- Home / introduction
- About
- Skills and technologies
- DevOps workflow
- Experience and training
- Education
- Featured projects
- Certifications and training
- Contact information
The portfolio highlights technologies such as AWS, Git, Jenkins, GitHub
Actions, Docker, Kubernetes, Terraform, Helm, Prometheus, Grafana, Loki,
and Argo CD.
Features
- Responsive layout for desktop and mobile screens
- Navigation links to the portfolio sections
- Mobile navigation toggle with accessible aria-expanded and
  aria-label attributes
- Navigation menu closes after a section link is selected
- Smooth scrolling
- Back-to-top button that appears after scrolling more than 500 pixels
- Project cards linking to GitHub repositories
- Technology icons provided by Devicon's stylesheet
- Basic page metadata for search engines and social sharing
Built With
- HTML5 --- page structure and content
- CSS3 --- layout, styling, responsive design, hover effects, and
  smooth scrolling
- JavaScript --- mobile menu interactions and back-to-top behavior
- Devicon --- technology icons loaded from a CDN
Project Structure
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── favicon.svg
Adjust the folder paths in this tree if your actual project uses a
different structure. The provided HTML references css/style.css and
favicon.svg; place the JavaScript file where the <script> element
in your HTML expects it.

Run Locally
No build tools or package installation are required for this static
website.
1. Download or clone the repository.
2. Check that index.html, the stylesheet, JavaScript file, and
   favicon are in the expected locations.
3. Open index.html in a web browser.
For a more reliable local preview, use a local development server such
as the Live Server extension in Visual Studio Code.
JavaScript Behavior
Mobile navigation
The script selects the menu button (#menu-toggle) and navigation list
(#nav-links). When the button is clicked, it toggles the active
class, updates the button's accessible label and expanded state, and
switches the button symbol between ☰ and ✕.

When a navigation link is selected, the menu closes and the button's
accessible attributes and symbol are reset.
Back-to-top button
The script selects the element with the ID back-to-top. It displays
the button when the page has been scrolled more than 500 pixels and
hides it otherwise. Clicking it scrolls the page to the top smoothly.

HTML/CSS requirement: Make sure the page contains an element with
id="back-to-top" and that your CSS positions and styles it
appropriately. Also ensure the script loads after these elements exist
(for example, place the script before </body> or use defer).
Featured Projects
The portfolio currently presents projects such as:
- HRMS DevOps Project --- CI/CD automation for an HRMS application
  using Jenkins and Docker
- HRMS Production Deployment --- Kubernetes-based application
  deployment with database, caching, storage, scaling, monitoring,
  backups, and recovery concepts
- HRMS Helm Deployment --- reusable Helm chart and
  environment-specific Kubernetes configuration
- Enterprise Kubernetes Security Project --- Kubernetes security
  practices including RBAC, network policies, secrets, security
  contexts, resource limits, and health probes
- GitOps with Argo CD --- GitOps-oriented deployment of a
  multi-component HRMS application
See the project cards in the website for links to the corresponding
repositories.
Customization
- Update the text in index.html to change profile information,
  skills, experience, projects, and contact links.
- Update css/style.css to change colors, spacing, typography,
  layout, and responsive behavior.
- Update js/script.js to change navigation and back-to-top
  interactions.
- Replace the favicon by updating favicon.svg and its reference in
  the HTML.
- Verify all external links and project repositories before
  publishing.
Before Publishing
- [ ] Test navigation links on desktop and mobile.
- [ ] Confirm that the mobile menu opens and closes correctly.
- [ ] Confirm that the back-to-top button exists and works.
- [ ] Verify every GitHub, contact, and social link.
- [ ] Check that the page looks correct on different screen sizes.
- [ ] Ensure the experience, training, certifications, and project
  descriptions accurately reflect your background and work.
- [ ] Do not publish passwords, cloud credentials, access keys, or
  other secrets.
Author
Mounika Vakacharlla
- GitHub: MounikaVakacharlla
# Portfolio Homepage

Welcome to the **Portfolio Homepage**, a personal portfolio website showcasing the work and skills of Moath Mouadi, a Frontend Developer. This project is built with HTML, SCSS, and modern web technologies to create a responsive, visually appealing interface that highlights projects, skills, and contact information.

## Overview
The Portfolio Homepage is a single-page web application designed to present Moath Mouadi's professional profile as a Frontend Developer. It includes sections for an introduction, a showcase of recent projects, a skills overview, and a contact form. The site is styled using SCSS with a modular approach, compiled to CSS for production, and is fully responsive for various devices.

## Features
- **Introduction Section**:
  - Displays a brief bio and social media links (e.g., GitHub).
  - Includes a professional headshot for personal branding.
- **Projects Section**:
  - Showcases key projects with images, descriptions, and links to GitHub repositories or live demos.
  - Projects include Dijkstra's Algorithm, Nearby Places, and FitLife Gym.
- **Skills Section**:
  - Highlights technical skills in a grid layout, including React, Next.js, JavaScript, HTML/CSS, Tailwind CSS, Java, Node.js, and SpringBoot.
- **Contact Section**:
  - Provides a direct email link for easy communication.
- **Responsive Design**:
  - Uses CSS Grid and Flexbox for a modern, adaptive layout.
  - Optimized for desktop, tablet, and mobile devices.
- **Modular SCSS**:
  - Organized SCSS files with resets, variables, mixins, and block-specific styles for maintainability.

## Technologies Used
- **Frontend**: HTML, SCSS, CSS
- **Tools**:
  - **Sass**: For modular and maintainable CSS preprocessing (`sass ^1.87.0`).
  - **Node.js**: For managing dependencies and running the Sass compiler.
- **Dependencies**:
  - `sass`: Used to compile SCSS to CSS with features like variables, mixins, and nesting.
  - Optional dependencies for Sass (e.g., `@parcel/watcher`, `chokidar`) for file watching during development.
- **Assets**: Icons from [Icons8](https://icons8.com/) and custom images for projects and profile.

## Installation
To set up the Portfolio Homepage on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MoathMalki/portfolio-homepage.git
   cd portfolio-homepage
   ```

2. **Install Dependencies**:
   - Ensure [Node.js](https://nodejs.org/) (version >= 14.0.0) is installed.
   - Install the required dependencies:
     ```bash
     npm install
     ```

3. **Set Up the Project**:
   - Ensure the `img/` directory contains the necessary images (`imagemoath.jpeg`, `djkstra.png`, `nerbay.png`, `project3.png`).
   - Verify that the Icons8 icons are accessible or replace the URLs with local copies if needed.

4. **Compile SCSS to CSS**:
   - Run the Sass compiler to generate the CSS file:
     ```bash
     npm run sass
     ```
   - This command watches for changes in `src/scss/main.scss` and compiles them to `dist/main.css`.

5. **Host the Application**:
   - Use a local web server to view the site. For example, with Python:
     ```bash
     python -m http.server 8000
     ```
   - Alternatively, use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

6. **Access the Application**:
   - Open your browser and navigate to `http://localhost:8000`.

## Usage
- **View the Portfolio**: Open `index.html` in a browser to explore the portfolio.
- **Navigate Sections**:
  - Use the header navigation to jump to "Projects," "Skills," or "Contact" sections.
  - Click project buttons to visit GitHub repositories or live project links.
- **Update Content**:
  - Modify `index.html` to update project details, bio, or skills.
  - Edit SCSS files in `src/scss/` to customize styles, then recompile with `npm run sass`.
- **Add New Projects**:
  - Update the `projects__grid` section in `index.html` with new project cards.
  - Ensure corresponding images are added to the `img/` directory.


## Contact Information
For questions or collaboration, reach out to:
- **Email**: [moathmouadi4@gmail.com](mailto:moathmouadi4@gmail.com)
- **GitHub**: [MoathMalki](https://github.com/MoathMalki)


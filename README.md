# Neeraj Gaur --- AI/ML Portfolio

A responsive, recruiter-facing portfolio website built with React and
Vite. It presents AI/ML projects through searchable project cards and
individual case-study pages, with navigation for Home, Projects, About,
Contact, and Resume.

## Features

-   Responsive layout for desktop, tablet, and mobile
-   Home page with professional introduction and featured projects
-   Projects gallery with search and category filters
-   Individual project case-study pages
-   About page for professional background and technical skills
-   Contact page with professional links
-   Resume navigation
-   Dark, modern AI/technology-inspired visual theme
-   Vercel deployment configuration

## Pages

  Route               Purpose
  ------------------- -------------------------------------------
  `/`                 Home page and featured projects
  `/projects`         Searchable and filterable project gallery
  `/projects/:slug`   Individual project case studies
  `/about`            Background, experience, and skills
  `/contact`          Contact and professional links

## Technology Stack

-   **React** --- UI components and page rendering
-   **Vite** --- development server and production build
-   **CSS** --- responsive styling and visual design
-   **React Router** --- page navigation
-   **Vercel** --- suggested hosting platform
-   **GitHub** --- source control and repository hosting

## Requirements

-   Node.js 18 or newer (a current LTS release is recommended)
-   npm, included with Node.js
-   Git and a GitHub account for publishing (optional for local
    development)

Check your installed versions:

``` bash
node -v
npm -v
```

## Run the Website Locally

1.  Download and extract the portfolio ZIP.

2.  Open a terminal in the extracted `neeraj-ai-portfolio` folder.

3.  Install dependencies:

    ``` bash
    npm install
    ```

    If PowerShell reports that `npm.ps1` cannot be loaded because script
    execution is disabled, use:

    ``` powershell
    npm.cmd install
    ```

4.  Start the development server:

    ``` bash
    npm run dev
    ```

    In PowerShell, if needed:

    ``` powershell
    npm.cmd run dev
    ```

5.  Open the local URL printed in the terminal, usually
    `http://localhost:5173/`.

Keep the terminal open while using the local development server. Press
`Ctrl+C` to stop it.

## Build and Preview for Production

Build the website:

``` bash
npm run build
```

Preview the production build locally:

``` bash
npm run preview
```

The production files are generated in the `dist/` directory.

## Customise Before Publishing

Open `src/main.jsx` and update the portfolio content and links. Search
for the existing constants and project data rather than creating
duplicate entries.

1.  **LinkedIn:** replace the placeholder with your actual LinkedIn
    profile URL.
2.  **Email:** add the professional email address you want recruiters to
    use.
3.  **GitHub links:** ensure each project links to its correct public
    repository or source file.
4.  **Live demos:** add the permanent URL for each deployed application.
    If a demo is not available, label it clearly rather than leaving a
    misleading link.
5.  **Resume:** put your final PDF at `public/resume.pdf` (create the
    `public` folder if necessary) and confirm that the Resume link
    points to it.
6.  **Project details:** verify each overview, problem statement,
    implementation description, architecture, results, and limitation
    against the actual project.
7.  **Images and screenshots:** use screenshots from your own projects
    where possible, and ensure you have permission to publish them.
8.  **Contact links:** test every external link and make sure it opens
    the intended destination.

### Suggested Project Portfolio

Prioritise a small number of strong, well-documented projects, such as:

-   Multi-Document PDF RAG Chatbot
-   MNIST Digit Recognition Web App
-   Customer Churn Prediction
-   Credit Card Fraud Detection
-   Sentiment Analysis

Only describe capabilities that are implemented. Do not invent
performance metrics, business impact, or evaluation results.

## Deploy to Vercel

1.  Create a new GitHub repository.
2.  Upload or push the **contents** of the portfolio folder to the
    repository.
3.  Sign in to Vercel using GitHub.
4.  Import the repository into Vercel.
5.  For a Vite project, confirm these build settings:
    -   **Build command:** `npm run build`
    -   **Output directory:** `dist`
    -   **Install command:** `npm install` (usually detected
        automatically)
6.  Deploy the project.
7.  Open the deployed URL and test the Home, Projects, case-study,
    About, Contact, Resume, and external project links.

The included `vercel.json` should provide a rewrite for client-side
routes. If you change routing or deployment settings, test direct
navigation to a case-study URL as well as navigation from the home page.

## Updating the Live Website

When the GitHub repository is connected to Vercel:

1.  Edit the relevant files locally.
2.  Test the changes using `npm run dev`.
3.  Commit and push the changes to the connected GitHub branch.
4.  Vercel will normally build and deploy the new version automatically.
5.  Check the deployed site after the build completes.

## Suggested Repository Structure

``` text
neeraj-ai-portfolio/
├── index.html
├── package.json
├── vercel.json
├── README.md
├── public/
│   └── resume.pdf
└── src/
    ├── main.jsx
    └── styles.css
```

The exact files may differ if the project is expanded with more
components, assets, or tests.

## Quality Checklist

-   [ ] Personal introduction and professional links are correct.
-   [ ] Resume PDF opens successfully.
-   [ ] Every project has accurate descriptions.
-   [ ] GitHub repository links work.
-   [ ] Live demo links open the correct applications.
-   [ ] Search and category filters work.
-   [ ] All navigation links work.
-   [ ] Direct URLs to project pages load after deployment.
-   [ ] Website is usable on mobile and desktop.
-   [ ] No secrets, API keys, confidential customer details, or
    employer-restricted information are published.
-   [ ] Claims and metrics can be substantiated.

## Privacy and Accuracy

This portfolio is intended for public viewing by recruiters. Do not
publish confidential employer or customer information, private datasets,
access tokens, API keys, or code you are not authorised to share.
Include only verifiable outcomes and project capabilities.

## Author

**Neeraj Gaur**\
AI/ML, Generative AI, and software quality engineering

Update the professional contact and social links in the source code
before sharing the live website.

```markdown
# Recruitment Management System (RMS) - Frontend

A responsive, high-fidelity frontend prototype for a Recruitment Management System. This project provides a comprehensive dashboard interface for HR administrators to manage job postings, track candidates, and handle recruitment analytics.

Originally designed for a Django backend, this version has been converted to standalone **Static HTML/CSS/JS** for independent frontend deployment (e.g., Netlify, Vercel, or GitHub Pages).

## 🚀 Key Features

* **Authentication UI:** Clean Login, Registration, and Password Recovery pages with validation feedback.
* **Interactive Dashboard:** Overview of hiring stats, recent applications, and system notices.
* **Candidate Management:**
    * View active candidate lists.
    * Add new candidate profiles.
    * Edit existing candidate details.
    * Simulated deletion workflow.
* **Job Directory:**
    * View open job positions.
    * Post new job roles with industry categorization.
    * Edit and remove job listings.
* **User Profile:** Account settings and profile management pages.
* **Responsive Design:** Built with Bootstrap 5, fully optimized for desktop and mobile viewports.

## 🛠️ Tech Stack

* **HTML5:** Semantic markup.
* **CSS3:** Custom styling with a modern "Glassmorphism" aesthetic.
* **Bootstrap 5.3:** For responsive grid layout and components (via CDN).
* **Bootstrap Icons:** For iconography (via CDN).
* **JavaScript (Vanilla):** Used to simulate form submissions and page redirection.

## 📂 Project Structure

Ensure your file structure looks like this for the links to work correctly:

/rms-frontend
│
├── css/
│   └── style.css            # Main stylesheet
│
├── index.html               # Login Page (Entry Point)
├── register.html            # Sign Up Page
├── forgot-password.html     # Password Recovery
│
├── dashboard.html           # Main Admin Dashboard
│
├── candidates.html          # List of all candidates
├── add-candidate.html       # Form to add a candidate
├── update-candidate.html    # Form to edit a candidate
├── delete-candidate.html    # Confirmation page for deletion
│
├── positions.html           # List of open job roles
├── add-position.html        # Form to post a new job
├── update-position.html     # Form to edit a job
├── delete-position.html     # Confirmation page for deletion
│
├── profile.html             # User Profile View
└── settings.html            # Account Settings/Edit Profile


## ⚡ How to Run

Since this is a static project, you do not need a server environment (like Python or Node.js) to view it.

1.  **Download** or Clone the repository.
2.  Ensure you have an active **Internet Connection** (required to load Bootstrap CSS and Icons from CDN).
3.  Open the **`index.html`** file in any modern web browser (Chrome, Firefox, Edge).
4.  **Login Simulation:**
    * Click "Login" to enter the dashboard (No specific credentials required for this prototype).

## 🧩 Mock Logic (JavaScript)

Please note that this is a **Frontend-Only** build. There is no database connected.

* **Forms:** When you click "Save," "Update," or "Confirm," the data is **not saved** to a server.
* **Redirects:** Small JavaScript snippets are included at the bottom of the HTML files to intercept form submissions and redirect you to the relevant list pages (e.g., saving a candidate redirects you back to the Candidate List) to simulate a real application flow.

## 🎨 Customization

To modify the visual style, edit the `css/style.css` file.
* **Colors:** The primary theme uses Bootstrap defaults mixed with custom transparency effects.
* **Glass Effect:** Check the `.card-glass` class in the CSS to adjust the background blur and opacity.


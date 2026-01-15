```markdown
# Recruitment Management System (RMS) — Frontend

A responsive, high-fidelity frontend prototype for a Recruitment Management System. This project provides a comprehensive dashboard interface for HR administrators to manage job postings, track candidates, and handle recruitment analytics.

Originally designed for a Django backend, this version has been converted to a standalone **Static HTML/CSS/JS** architecture for independent frontend deployment on platforms like Vercel or GitHub Pages.

## 🚀 Key Features

* **Authentication UI:** Clean Login, Registration, and Password Recovery pages with real-time validation feedback.
* **Interactive Dashboard:** A centralized overview of hiring statistics, recent applications, and system notifications.
* **Candidate Management:**
    * View and filter active candidate lists.
    * Interface for adding and editing candidate profiles.
    * Simulated deletion and archival workflows.
* **Job Directory:**
    * Management of open job positions.
    * Industry-categorized job posting forms.
    * Full CRUD (Create, Read, Update, Delete) UI simulation.
* **User Profile & Settings:** Dedicated account management and profile customization pages.
* **Responsive Design:** Fully optimized for desktop, tablet, and mobile viewports using **Bootstrap 5**.

## 🛠️ Tech Stack

* **HTML5:** Semantic markup for improved accessibility and SEO.
* **CSS3:** Custom styling featuring a modern **"Glassmorphism"** aesthetic.
* **Bootstrap 5.3:** Responsive grid system and UI components (loaded via CDN).
* **Bootstrap Icons:** Scalable vector iconography.
* **JavaScript (Vanilla):** Client-side logic to simulate form submissions, state changes, and routing.

## 📂 Project Structure

Ensure your local file structure matches the following to maintain correct pathing:

```text
/rms-frontend
│
├── css/
│   └── style.css            # Custom glassmorphism and theme styles
│
├── index.html               # Login Page (Application Entry Point)
├── register.html            # User Registration
├── forgot-password.html     # Password Recovery Workflow
│
├── dashboard.html           # Main Administrative Overview
│
├── candidates.html          # Candidate Directory
├── add-candidate.html       # Create Candidate Interface
├── update-candidate.html    # Edit Candidate Interface
├── delete-candidate.html    # Deletion Confirmation Modal/Page
│
├── positions.html           # Job Openings Directory
├── add-position.html        # Job Creation Interface
├── update-position.html     # Job Modification Interface
├── delete-position.html     # Deletion Confirmation Modal/Page
│
├── profile.html             # User Profile View
└── settings.html            # Account & Security Settings

```

## ⚡ How to Run

This is a static frontend project; no server-side environment (Python, Node.js, etc.) is required.

1. **Clone/Download** the repository to your local machine.
2. Ensure you have an active **Internet Connection** to fetch Bootstrap dependencies from the CDN.
3. Launch **`index.html`** in any modern web browser.
4. **Simulation Note:** Click "Login" to access the dashboard. No specific credentials are required for this prototype.

## 🧩 Mock Logic (JavaScript)

This build is **Frontend-Only**. There is no persistent database connection.

* **Form Handling:** Clicking "Save," "Update," or "Confirm" triggers a success simulation but does not persist data to a server.
* **Client-Side Redirects:** JavaScript snippets handle form interception to redirect users back to list views (e.g., redirecting to the Candidate List after "saving"), mimicking a full-stack application flow.

## 🎨 Customization

To adjust the visual theme:

* **Styles:** Modify `css/style.css` to change the primary color palette.
* **Glassmorphism:** Locate the `.card-glass` class in the CSS to tweak background blur, transparency, and border-radius.

```

---
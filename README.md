# Github-Manager

# GitSite Manager & IDE 

GitSite Manager is a powerful, browser-based integrated development environment (IDE) that connects directly to your GitHub account. It is designed to act as a centralized dashboard for managing your web properties, allowing you to browse repositories, explore files, and edit code directly in your browser without needing local setup or complex IDEs. high-performance code editor engine for real-time syntax highlighting and intelligent editing.Vanilla JavaScript: To handle all logic and state management, ensuring a fast, lightweight experience.Security NoticeThis application stores your Personal Access Token in your browser's sessionStorage. This ensures that your credentials are not persistent across browser restarts and are never sent to a third-party server. Always ensure you are using this on a secure, private device.

# Features

GitHub Integration: Connect securely using your GitHub Personal Access Token (PAT).
Centralized Dashboard: View all your repositories at a glance with search and filter capabilities.
Integrated Code Editor: Built with Monaco Editor (the technology powering VS Code) for a premium, syntax-highlighted coding experience.
Direct File Management: Explore your repository file structure directly within the platform.
In-Browser Saving: Commit code changes back to GitHub instantly with custom commit messages.
Client-Side Security: Your GitHub token is stored only in your browser's session storage and is cleared automatically upon closing the session.

# Getting Started

Generate a Token:
Go to your GitHub Settings > Developer Settings > Personal Access Tokens.
Create a new token with repo scope permissions.

Connect:
Open index.html in your browser.
Paste your token into the "PAT Token" field at the top and click "Connect".

Manage:
Click "Edit Code" on any repository to open the file explorer and begin editing.
Make your changes in the editor, enter a commit message, and click "Save Changes".

# Technology Stack

HTML5 & Tailwind CSS: For a modern, responsive user interface.
GitHub REST API: For seamless communication with your remote repositories.
Monaco Editor: A high-performance code editor engine for real-time syntax highlighting and intelligent editing.
Vanilla JavaScript: To handle all logic and state management, ensuring a fast, lightweight experience.

# Security Notice

This application stores your Personal Access Token in your browser's sessionStorage. This ensures that your credentials are not persistent across browser restarts and are never sent to a third-party server. Always ensure you are using this on a secure, private device.

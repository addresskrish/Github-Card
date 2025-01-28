# Github-Card GitHub Profile Card Generator

This project is a simple web application that allows users to search for GitHub profiles and display details such as the user's name, avatar, bio, followers, following, and public repositories in an elegant card design.

## Features

- Fetches GitHub user data using the GitHub API.
- Displays user information including:
  - Avatar
  - Name
  - Username
  - Bio
  - Followers, Following, and Public Repositories count
- Responsive design.
- Button to view the user's GitHub profile.

---

## Demo

![Demo Screenshot](https://github.com/addresskrish/Github-Card/blob/main/Github-Card.png)

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling and layout.
- **JavaScript**: For API calls and interactivity.
- **GitHub API**: To fetch user profile data.

---

## Setup and Installation

### Prerequisites

- A text editor (e.g., VS Code, Sublime Text).
- A browser to run the application.
- Node.js installed for local development (optional).

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Github-Card.git
   cd Github-Card
## Setup API Token

### Steps to Generate a GitHub API Token:

1. Go to your GitHub account.
2. Navigate to **Settings** > **Developer Settings** > **Personal Access Tokens** > **Tokens (Classic)**.
3. Click on **Generate new token**.
4. Add the required scopes (e.g., `read:user`).
5. Copy the generated token and replace the `token` variable in the `assets/app.js` file:
   ```javascript
   const token = "your-github-token-here";

# John Krebian On ORBITER

[![Stars](https://img.shields.io/github/stars/jkrebian/jkrebian.orbiter.website)](https://github.com/jkrebian/jkrebian.orbiter.website/stargazers)
[![Forks](https://img.shields.io/github/forks/jkrebian/jkrebian.orbiter.website)](https://github.com/jkrebian/jkrebian.orbiter.website/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This is the personal website of John Krebian, hosted on ORBITER.

## Key Features & Benefits

*   **Personal Website:** A platform to showcase John Krebian's projects and information.
*   **ORBITER Hosting:** Leverages the ORBITER platform for easy and reliable deployment.
*   **Hugo Integration:** Built using Hugo, a fast and flexible static site generator.
*   **Automated Deployment:** Utilizes GitHub Actions for continuous integration and deployment.

## Prerequisites & Dependencies

Before setting up the project, ensure you have the following installed:

*   **Node.js:** (Version 16 or higher is recommended) - [https://nodejs.org/](https://nodejs.org/)
*   **npm:** (Usually installed with Node.js)
*   **Hugo:** Static Site Generator - [https://gohugo.io/](https://gohugo.io/getting-started/installing/)
*   **Git:** Version control system - [https://git-scm.com/](https://git-scm.com/)

## Installation & Setup Instructions

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/jkrebian/jkrebian.orbiter.website.git
    cd jkrebian.orbiter.website
    ```

2.  **Initialize Submodules:**

    ```bash
    git submodule init
    git submodule update
    ```

3.  **Install Dependencies:**

    ```bash
    npm install
    ```

4.  **Configure Environment Variables:**

    *   Create a `.env` file (if necessary) and configure any required environment variables.  Refer to `.github/workflows/deploy.yaml` for used environment variables.

5.  **Run Hugo Server (for local development):**

    ```bash
    hugo server
    ```

    This will start a local development server, usually at `http://localhost:1313/`.

## Usage Examples & API Documentation

*   **Content Creation:** Create new posts in the `content/posts/` directory using Markdown. Refer to the `content/posts/readme.md` file for a basic template.
*   **Customization:** Modify the website's appearance by editing the Hugo templates in the `themes/` directory (if custom themes are used).  Consult the Hugo documentation for detailed instructions ([https://gohugo.io/](https://gohugo.io/)).
*   **GitHub Actions:**  The `.github/workflows/deploy.yaml` file defines the deployment workflow. This workflow is automatically triggered on pushes to the main branch.  It handles building the Hugo site and deploying it.

## Configuration Options

*   **Hugo Configuration:** The `hugo.toml` file contains various Hugo configuration options, such as the website's title, theme, and other settings.
*   **Environment Variables:** Environment variables used in GitHub Actions can be configured in the repository's settings.

## Contributing Guidelines

We welcome contributions! Please follow these steps:

1.  **Fork the Repository:** Create your own fork of the repository on GitHub.
2.  **Create a Branch:** Create a new branch for your feature or bug fix.

    ```bash
    git checkout -b feature/your-feature-name
    ```

3.  **Make Changes:** Implement your changes and ensure they are well-tested.
4.  **Commit Changes:** Commit your changes with a clear and concise message.

    ```bash
    git commit -m "Add your commit message here"
    ```

5.  **Push to Your Fork:** Push your branch to your forked repository.

    ```bash
    git push origin feature/your-feature-name
    ```

6.  **Create a Pull Request:** Submit a pull request from your branch to the main branch of the original repository.

## License Information

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

*   **Hugo:** The static site generator used to build this website.
*   **ORBITER:** The hosting platform used for deployment.
*   **GitHub Actions:**  For providing CI/CD pipelines.

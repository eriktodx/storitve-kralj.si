# Storitve Kralj d.o.o. Website

Welcome to the official repository for the **Storitve Kralj d.o.o.** website, a family-owned business based in Kranj, Slovenia, specializing in professional painting services and finishing construction work. This simple static website showcases the company's services, contact information, and portfolio.

You can view the live website at [storitve-kralj.si](https://storitve-kralj.si/).

## Overview

This project is a lightweight, static HTML/CSS website hosted on Firebase Hosting. It provides information about the services offered by Storitve Kralj d.o.o., including painting, plastering, decorative finishes, and more. The site is designed to be responsive and user-friendly, with integrated analytics for tracking page views.

## Features

- **Responsive Design**: Built with Tailwind CSS and custom styles for optimal viewing on all devices.
- **Service Showcase**: Detailed descriptions and images of services like painting, plastering, and decorative finishes.
- **Contact Information**: Direct links for phone calls and emails, along with business details.
- **Firebase Hosting**: Automated deployment using GitHub Actions for both production and preview environments.
- **Analytics**: Integrated Firebase Analytics to track user interactions.

## Project Structure

```
storitve-kralj.si/
├── .firebaserc                # Firebase project configuration
├── .github/                   # GitHub Actions workflows for deployment
│   └── workflows/
│       ├── firebase-hosting-merge.yml       # Deployment on merge to main
│       └── firebase-hosting-pull-request.yml # Deployment on pull requests
├── .gitignore                 # Git ignore file
├── firebase.json              # Firebase Hosting configuration
├── public/                    # Public directory for hosting
│   ├── index.html             # Main homepage
│   ├── 404.html               # Custom 404 error page
│   ├── assets/                # Static assets (CSS, images)
│   │   ├── css/
│   │   │   ├── main.css       # Custom styles
│   │   │   ├── normalize.css  # CSS normalization
│   │   │   └── print.css      # Print-specific styles
│   │   └── img/               # Images for the website
│   └── sitemap.xml            # Sitemap for SEO
├── LICENSE                    # MIT License file
└── README.md                  # Project documentation
```

## Getting Started

### Prerequisites

- **Node.js** (optional, for local development with Firebase CLI)
- **Firebase CLI** (optional, for manual deployment or local testing)
- A GitHub account for contributing or deploying via GitHub Actions

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/eriktodx/storitve-kralj.si.git
   cd storitve-kralj.si
   ```

2. **Serve Locally (Optional)**:
   If you have Firebase CLI installed, you can serve the site locally:
   ```bash
   npm install -g firebase-tools
   firebase serve
   ```
   The site will be available at `http://localhost:5000`.

### Deployment

The project is set up for automatic deployment to Firebase Hosting using GitHub Actions:
- **On Merge to `main`**: Deploys to the live channel.
- **On Pull Request**: Deploys a preview version for review.

To deploy manually (if needed):
1. Ensure Firebase CLI is installed and logged in:
   ```bash
   firebase login
   ```
2. Deploy to Firebase Hosting:
   ```bash
   firebase deploy
   ```

## Contributing

We welcome contributions to improve the website! Whether it's a bug fix, feature addition, or content update, feel free to get involved.

### How to Contribute

1. **Fork the Repository** or clone it if you have access.
2. **Create a Branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes** and commit them with a descriptive message:
   ```bash
   git commit -m "Add feature: description of changes"
   ```
4. **Push Your Changes**:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** on GitHub with a clear description of your changes.

### Code of Conduct

This project adheres to the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/) Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

### Issues

If you encounter any issues or have suggestions, please [open an issue](https://github.com/eriktodx/storitve-kralj.si/issues/new) on GitHub.

## Maintainers

- **Erik Kralj** ([@eriktodx](https://github.com/eriktodx))

## License

This project is licensed under the [MIT License](LICENSE) © Erik Kralj.

## Acknowledgments

- Thanks to all contributors who help maintain and improve this project.
- Built with [Firebase Hosting](https://firebase.google.com/products/hosting) for reliable deployment.
- Styled using [Tailwind CSS](https://tailwindcss.com/) and custom CSS for a modern look.
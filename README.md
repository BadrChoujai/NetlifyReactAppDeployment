# React App Deployment with Netlify And Github Actions

This repository showcases the seamless deployment of a React app using Netlify and GitHub Actions. The combination of Netlify for hosting and GitHub Actions for continuous integration provides an automated workflow for building, testing, and deploying your React applications.

## Features

- **Continuous Deployment:** GitHub Actions is configured to automatically build and deploy your React app to Netlify whenever changes are pushed to the `main` branch.
- **Environment Variables:** Leverages GitHub Actions secrets and Netlify environment variables for secure storage of sensitive information.
- **Custom Domain:** Easily configure a custom domain for your Netlify site.

## Getting Started

1. **Clone the Repository:**
```bash
git clone https://github.com/BadrChoujai/NetlifyReactAppDeployment.git
cd your-react-app
```
   
2. **Install Dependencies:**
```bash
npm install
```

3. **Configuration:**
    - Update the REACT_APP_API_URL variable in your .env file with your API endpoint if needed.
    - Customize the netlify.toml file for additional configuration options.
    - Customize the .github/workflows/main.yml file for additional GitHub Actions configuration.

2. **Deployment:**
    - Push your changes to the main branch to trigger an automatic deployment on Netlify.
    - Visit your Netlify dashboard for deployment logs, site settings, and more.
    
    2.1 GitHub Actions Workflow:
      - The GitHub Actions workflow is triggered automatically on each push to the main branch.
      - View workflow status, logs, and details in the "Actions" tab of your GitHub repository.

    2.2 Netlify Deployment:
      - Visit your Netlify dashboard for deployment logs, site settings, and more.

### Netlify Status Badge
- https://app.netlify.com/sites/YOUR_NETLIFY_SITE_ID

<img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/YOUR_USERNAME/your-react-app/CI">

## Learn More

For more information on Netlify, GitHub Actions, and how to customize your deployment workflow, refer to the [Netlify Documentation](https://docs.netlify.com/) and [GitHub Actions](https://docs.github.com/en/actions) Documentation.

Feel free to fork this repository and adapt it for your own React projects. Happy coding!

PS: Make sure to replace placeholders like `YOUR_NETLIFY_SITE_ID` and customize any other information according to your project.



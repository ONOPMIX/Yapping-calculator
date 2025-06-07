# Yapping Calculator

A simple point-based wage calculator written in HTML and JavaScript. Enter your daily earned points, the dollar value per point and your working hours to see your hourly, daily and projected earnings.

## Running locally

Simply open `index.html` in a modern browser. No build step is required.

You can also serve the file with a local web server:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.

## GitHub Pages

To host this calculator online, enable GitHub Pages in your repository settings. Select the `main` branch and the `/` (root) folder. Once enabled, GitHub will provide a link similar to:

```
https://<your-username>.github.io/Yapping-calculator/
```

Replace `<your-username>` with your GitHub account name and visit the link to use the calculator.

Every push to the `main` branch will automatically update the page. Share the URL so anyone can access the calculator.

## Security recommendations

The calculator is a static web page, so the only way the files can change is if
someone pushes new commits to this repository. Follow these guidelines to keep
your GitHub Pages site safe:

1. **Restrict write access** to trusted collaborators only.
2. **Enable two-factor authentication** on your GitHub account to prevent
   unauthorized logins.
3. **Review pull requests** and commit history regularly for unexpected changes
   before merging.
4. Consider using **branch protection rules** so modifications require review or
   signed commits.

As long as your repository is secure and only serves the files in this repo,
visitors cannot inject viruses simply by loading the page.

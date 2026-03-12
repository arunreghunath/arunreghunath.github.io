# arunreghunath.github.io

[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=arunreghunath_arunreghunath.github.io&metric=bugs)](https://sonarcloud.io/summary/new_code?id=arunreghunath_arunreghunath.github.io)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=arunreghunath_arunreghunath.github.io&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=arunreghunath_arunreghunath.github.io)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=arunreghunath_arunreghunath.github.io&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=arunreghunath_arunreghunath.github.io)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=arunreghunath_arunreghunath.github.io&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=arunreghunath_arunreghunath.github.io)

<hr>

## About

This repository powers the GitHub Pages site at [arunreghunath.github.io](https://arunreghunath.github.io), which automatically redirects visitors to the personal website hosted at **[www.arunreghunath.com](https://www.arunreghunath.com)**.

## How It Works

The site uses a lightweight `index.html` page that performs an immediate client-side redirect:

- **JavaScript redirect** – `globalThis.location.replace()` redirects the browser as soon as the page loads.
- **Fallback link** – A `<noscript>` block provides a clickable link for browsers with JavaScript disabled, ensuring all visitors can reach the destination.

## Project Structure

```
arunreghunath.github.io/
├── index.html   # Redirect page
└── README.md    # This file
```

## Live Site

👉 [www.arunreghunath.com](https://www.arunreghunath.com)

<hr>

🙂 **Thanks for checking out!**

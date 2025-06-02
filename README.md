# Censys Dorker - Bug Bounty Edition

A simple and powerful web tool to help bug bounty hunters and security researchers generate targeted Censys search queries effortlessly. Use prebuilt dork templates or customize your own queries to discover exposed assets, services, and potential vulnerabilities across domains and subdomains.

---

## Features

- Input target domain or wildcard subdomains.
- Choose from 100+ prebuilt dork queries covering common protocols, services, HTTP headers, certificates, software banners, CDN, and more.
- Enter and test your own custom Censys queries.
- Automatically generates a ready-to-use Censys search URL.
- User-friendly interface built with Tailwind CSS for fast and responsive use.

---

## How to Use

1. Enter a target domain or subdomain (e.g., `example.com` or `*.example.com`).
2. Select a prebuilt dork query from the dropdown or enter your custom query in the textarea.
3. Click **Generate Search URL** to create a direct link to the Censys platform with your query.
4. Click the generated URL to start your reconnaissance on Censys.

---

## Example Queries Included

- Wildcard subdomains: `"*.example.com"`
- HTTP login pages: `"login" AND "*.example.com"`
- SSH services: `"ssh" AND "example.com"`
- TLS certificates with Let's Encrypt: `"Let's Encrypt" AND "*.example.com"`
- Specific software banners like `"Apache"`, `"nginx"`, `"Microsoft-IIS"`
- Common service ports like `port:22` (SSH), `port:80` (HTTP), `port:443` (HTTPS)
- Admin, dashboard, phpMyAdmin pages, and more

---

## Installation

No installation required! Just open the `index.html` file in any modern web browser.

---

## Contributing

Feel free to submit issues or pull requests to add more dorks or improve functionality.

---

## License

MIT License © 2025

---

## Acknowledgments

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Powered by [Censys Search](https://censys.io)

---

Happy hunting! 🔍🕵️‍♂️

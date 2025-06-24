# Elena's Integrative Healing Website

This project contains a simple static website for Elena's shamanic healing practice. The goal is to present her services and philosophy in clear English for a U.S. audience while honoring her depth and lineage.

## Getting Started

The pages live under the `src/` directory. You can view them by opening `src/index.html` in your browser or by running a local web server:

```bash
python3 -m http.server --directory src
```

Then navigate to `http://localhost:8000`.

## Site Map

- **Home** – Hero statement and "Book a Discovery Call" button
- **About Elena** – Credentials, lineage timeline, and personal "why"
- **Services** – Cards outlining each session type
- **What to Expect** – Walk-through of a typical session
- **Client Stories** – Testimonials highlighting transformation
- **Resources & Blog** – Articles and glossary
- **Book Now** – Scheduler widget with consent disclaimer
- **Contact & Location** – In-person or distance sessions

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on style and submitting pull requests.

## Deploying to GitHub Pages

The site files live in the `docs/` directory. Configure GitHub Pages to serve
from the **main branch** and the `/docs` folder so that the content is hosted
correctly.

1. In your repository, go to **Settings**.
2. Select **Pages** from the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch** and set the
   source to `main` and the folder to `/docs`.

## License

This project is licensed under the [MIT License](LICENSE).

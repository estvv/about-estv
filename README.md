# about.estv.fr

Minimalist personal CV website.

## Structure

```
about-estv/
├── config.json    # CV content (edit this file)
├── index.html     # UI/UX implementation
├── nginx.conf     # Web server configuration
└── docker-compose.yml
```

## Usage

Edit `config.json` to update:
- Personal information (name, title, contact)
- About section
- Experience entries
- Skills and categories
- Projects
- Education

## Development

```bash
# Start local server
make up

# Stop
make down

# Update and restart
make update
```

## PDF Download

Click the "Download PDF" button to generate a PDF version of your CV.

## Tech Stack

- Vanilla JavaScript
- Tailwind CSS (CDN)
- Plus Jakarta Sans font
- html2pdf.js for PDF generation

## License

MIT
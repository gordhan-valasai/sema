# Strategic Energy Modelling Associates (SEMA)

A professional consultancy website for energy system optimisation, hydrogen infrastructure, and transport decarbonisation analysis.

## Structure

The website consists of the following pages:

- **index.html** - Home page with tagline, credentials, and quick links
- **services.html** - Five core service categories with detailed descriptions
- **capabilities.html** - Modelling capabilities organised by problem type
- **case-studies.html** - Four detailed case studies with limitations and caveats
- **publications.html** - Publications grouped by theme
- **approach.html** - Six-step working process
- **clients.html** - Who I work with and what I offer/do not offer
- **about.html** - About page (template for personal information)
- **contact.html** - Contact form with filtering questions
- **styles.css** - Main stylesheet with responsive design

## Features

- Clean, professional design with modern CSS
- Responsive layout for mobile and desktop
- Clear navigation structure
- Technical content focused on optimisation-based analysis
- Explicit documentation of limitations and assumptions
- Contact form with project filtering questions

## Customization

### About Page
Edit `about.html` to add:
- Current position and research focus (2-3 sentences)
- Geographic and sectoral experience (1-2 sentences)
- International collaborations and funding (1-2 sentences)

### Publications
Edit `publications.html` to add your actual publications under each theme:
- Hydrogen Systems and Infrastructure
- Transport Sector Decarbonisation
- National Energy Planning and Policy
- Methodological Contributions

Include DOI links and repository links where available.

### Case Studies
The case studies page includes four template case studies. Replace with your actual projects, maintaining the structure:
- Problem
- Approach
- Key Results
- Limitations and Caveats

### Contact Form
The contact form currently uses `action="#"`. To make it functional, you'll need to:
1. Set up a form handler (e.g., Formspree, Netlify Forms, or custom backend)
2. Update the `action` attribute in `contact.html`

## Deployment

### Option 1: Static Hosting
The website is static HTML/CSS and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

### Option 2: Local Development
Simply open `index.html` in a web browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

## Design Notes

- Color scheme: Professional blue tones
- Typography: System fonts for performance
- Layout: Grid-based responsive design
- Navigation: Sticky header for easy access
- Accessibility: Semantic HTML structure

## Content Guidelines

The website follows these principles:
- Technical precision over promotional language
- Explicit documentation of limitations
- Focus on decision support rather than software tools
- Clear communication of what is and is not offered
- Reproducibility and transparency emphasis

## Next Steps

1. Fill in the About page with your information
2. Add your actual publications
3. Replace case study templates with real projects
4. Set up contact form handling
5. Review and customize content as needed
6. Deploy to hosting service

## Maintenance

- Review quarterly to add new case studies
- Remove outdated content
- Update publications as new work is published
- Keep contact information current


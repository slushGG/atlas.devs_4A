# ATLAS-DEVS [ 4A ]

The official portfolio for **ATLAS-DEVS**, a four-member student development team focused on cloud computing, web engineering, UI/UX design, and emerging technologies.

**Live website:** [https://team-ku.tech/](https://team-ku.tech/)

## About the group

ATLAS-DEVS brings together different technical and creative strengths to turn ideas into polished digital products. The team collaborates across planning, design, development, analysis, testing, documentation, and deployment.

- **Course:** Cloud Computing
- **Section:** 4A
- **Founded:** March 2026
- **Team size:** 4 members

### Mission

To design and engineer clean, accessible, and purposeful web experiences while developing our skills through hands-on collaboration.

### Vision

To be recognized for quality execution, bold ideas, and expertise in modern web and blockchain technologies.

### Values

Teamwork, integrity, creativity, and continuous growth.

## Team

| Member | Role | Portfolio |
| --- | --- | --- |
| Tyrone Parreño | Programmer | [View portfolio](https://team-ku.tech/wordpress/index.php/member-1/) |
| Reymund Brondo | Project Manager | [View portfolio](https://team-ku.tech/wordpress/index.php/member-2/) |
| Ivy Velasco | Analyst | [View portfolio](https://team-ku.tech/wordpress/index.php/member-3/) |
| Rhenalyn Oco | Technical Writer | [View portfolio](https://team-ku.tech/wordpress/index.php/member-4/) |

## Portfolio highlights

- Group landing page with links to each member's portfolio.
- Individual member pages for profile, skills, projects, experience, articles, and contact information.
- Group overview with mission, vision, values, roles, team statistics, technology stack, and project timeline.
- Responsive dark-and-orange visual design with animated effects.
- WordPress block editing for page content and image slots.

## Project timeline

| Period | Milestone |
| --- | --- |
| September 2026 | Team formation, role assignments, and project planning |
| October 2026 | UI/UX design, visual identity, and WordPress template planning |
| October to early November 2026 | Theme and portfolio development |
| November 2026 | VPS deployment, cross-device testing, and launch |

## Technology

### Website implementation

- WordPress Full Site Editing and Gutenberg
- PHP and MySQL/MariaDB
- HTML, CSS, and JavaScript
- GSAP, Particles.js, TypeIt, and Font Awesome

### Team toolkit

HTML5, CSS3, JavaScript, Laravel, MySQL, React Native, Expo, and Laragon.

## Repository structure

```text
.
├── database/                         # SQL database snapshots
└── wordpress/
    ├── wp-admin/                     # WordPress administration
    ├── wp-content/
    │   ├── plugins/                  # Installed plugins
    │   └── themes/
    │       └── Devenci WP [V1.0.8]/  # Custom block theme
    │           ├── assets/
    │           │   ├── content/      # Editable homepage block content source
    │           │   ├── css/          # Theme and editor styles
    │           │   ├── js/           # Front-end interactions
    │           │   ├── images/       # Theme artwork
    │           │   ├── audio/
    │           │   └── vendor/       # Bundled front-end libraries
    │           ├── blocks/           # Custom Gutenberg blocks
    │           ├── inc/              # Theme setup, content, and importer
    │           ├── parts/            # Shared headers and footers
    │           ├── patterns/         # Reusable block patterns
    │           ├── templates/        # Full-site editing templates
    │           ├── functions.php
    │           ├── style.css
    │           └── theme.json
    └── wp-includes/                  # WordPress core
```

## WordPress setup

The repository includes the WordPress installation under `wordpress/`. The custom theme is located at:

```text
wordpress/wp-content/themes/Devenci WP [V1.0.8]/
```

For a fresh WordPress installation:

1. Use WordPress 6.6 or newer, PHP 8.0 or newer, and MySQL/MariaDB.
2. Install or copy the custom theme into `wp-content/themes/`.
3. Configure the database connection and site URLs in the private WordPress configuration for your environment.
4. Activate **Dev Venci** from the WordPress Themes screen.
5. Open **Appearance → Dev Venci Setup** if the initial pages and media were not imported automatically.

The theme creates the group homepage and four member pages, sets the homepage as the static front page, and supplies editable Gutenberg blocks and templates.

## Editing content

- Edit the group homepage and its About section from **Pages → TeamKU-4A → Edit**.
- Edit member profiles from their respective pages in the WordPress Page Editor.
- Add or replace portraits using the image blocks or the Member Card block settings.
- Edit shared headers, footers, templates, and reusable patterns in the Site Editor.

The About section source in the theme is used to populate new homepages and to add the section once to an existing homepage if it is missing. Once present, saved edits are stored as page content in the WordPress database.

## Data and deployment notes

- The public portfolio is deployed at [team-ku.tech](https://team-ku.tech/).
- Database snapshots in `database/` are for backup or development use; they are not needed to install the theme. Review and sanitize database exports before sharing them publicly.
- Keep database credentials, WordPress salts, and other environment-specific settings private. Do not copy production credentials into documentation or source control.

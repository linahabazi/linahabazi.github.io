# linahabazi.github.io

## Project Folder Structure
```
linahabazi.github.io/
├── assets/                  # Files that need to be processed by Hugo Pipes (e.g. SCSS to CSS)
│   └── selected-works.yaml  ### Template for dynamic md content built in index.html from dynamodb data
├── content/                 # Static markdown content
├── data/                    # Data files for site generation
├── layouts/                 # Page and section layout html files
├── prebuild/                # Generate dynamic markdown content
├── static/                  # Files served directly to the browser
├── CNAME                    # Custom domain config
├── config.toml              # Hugo configuration file
├── package.json             # Node.js dependencies and scripts
├── README.md                # Project documentation
```
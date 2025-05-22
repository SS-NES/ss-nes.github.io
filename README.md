# ss-nes.github.io

This repository hosts a Jekyll-based website using a custom GitHub-hosted theme. Below is an overview of the structure and guidelines for maintaining and updating the site.

## Features
- **Custom Theme**: The site uses a [custom GitHub-hosted theme](https://github.com/SS-NES/jekyll-theme-ss-nes) for styling and layout.
- **Editable Content**: Website content can be managed through YAML files in the `_data` folder.
- **Image Management**: Images are stored in the `/assets/img/` directory, with slider images placed in `/assets/img/slider/`.
- **Custom HTML**: Additional HTML can be added to the `<head>` section by adding or modifying the `_includes/head-custom.html` file.

## Folder Structure
```
.
├── _data/                 # YAML files for site content
├── _includes/             # Customizable partials (e.g., head-custom.html)
├── assets/
│   ├── img/               # Image files
│   │   ├── slider/        # Slider images
│   │   └── ...            # Other image subfolders (optional)
├── _config.yml            # Jekyll configuration file
├── README.md              # Project documentation
└── ...
```

## How to Update Content
1. **Edit YAML Files**: Update the `_data` folder to modify site content.
2. **Add Images**: Place images in `/assets/img/` or its subfolders. Use `/assets/img/slider/` for slider-specific images.
3. **Customize HTML**: Modify `_includes/head-custom.html` to add custom HTML to the `<head>` section.

## Deployment
This site is hosted on GitHub Pages. Changes pushed to the repository will automatically trigger a rebuild and deploy the updated site.

## Local development
To run the site locally with the custom theme, first clone [jekyll-theme-ss-nes](https://github.com/SS-NES/jekyll-theme-ss-nes) into the parent directory (`../jekyll-theme-ss-nes`). Then, use the following command to start the development server with the appropriate configuration:

```sh
JEKYLL_ENV=development bundle exec jekyll serve --config _config.development.yml
```

This ensures Jekyll loads the local theme and uses development settings for live preview.

## Resources
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

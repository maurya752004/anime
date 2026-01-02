# Anime Website

A complete responsive anime website featuring a modern design with categories for different anime genres including action, family, and children's anime. The website includes a showcase of popular anime series with download functionality and an interactive user interface.

## Project Description

This is a static website project built with HTML, CSS, and JavaScript that provides an anime streaming/download platform interface. The site features a responsive design that works across different screen sizes, with a modern layout showcasing various anime series organized by categories.

## Repository Contents

### File/Folder Tree

```
.
├── .gitignore                     # Git ignore rules for static web projects
├── .vscode/                       # VS Code configuration files
│   ├── c_cpp_properties.json      # C/C++ configuration
│   ├── launch.json                # Debug configuration
│   └── settings.json              # Editor settings
├── LICENSE                        # MIT License
├── README.md                      # This file
├── anime.css                      # Main stylesheet
├── anime.html                     # Anime listing page
├── anime.js                       # JavaScript functionality
├── download.html                  # Main download page
├── download1.html                 # Download page for specific anime #1
├── download2.html                 # Download page for specific anime #2
├── download3.html                 # Download page for specific anime #3
├── download4.html                 # Download page for specific anime #4
├── download5.html                 # Download page for specific anime #5
├── images/                        # Image assets directory (64 files)
│   ├── logo.png                   # Site logo
│   ├── home-img-*.jpeg            # Homepage images
│   ├── anime-img-*.jpg            # Anime preview images
│   ├── action-*.jpg               # Action category images
│   ├── family-*.jpg               # Family category images
│   ├── child-*.jpg                # Children's category images
│   ├── screenshot-img-*.jpeg      # Screenshot images
│   ├── download-img.jpeg          # Download section image
│   ├── death*.jpg, deathnote*.jpg # Death Note anime images
│   ├── kakegurui*.jpg             # Kakegurui anime images
│   ├── ONEPUCH*.jpg, O.jpg        # One Punch Man anime images
│   └── UD6-CSG3.html              # Embedded HTML asset
├── index.html                     # Homepage/main entry point
├── tempCodeRunnerFile             # Binary executable (temp file)
├── tempCodeRunnerFile.cpp         # C++ source file (temp file)
└── video/                         # Video assets directory
    ├── WhatsApp Video 2024-04-23 at 2.59.36 PM.mp4  # Video file (5.3 MB)
    └── WhatsApp Video 2024-04-23 at 3.27.42 PM.mp4  # Video file (16 MB)
```

### Top-Level Files and Directories

- **index.html** - The main entry point of the website. Contains the homepage with featured anime, navigation, and sections for different categories.

- **anime.css** - The primary stylesheet containing all the styling rules for the website, including responsive design breakpoints and animations.

- **anime.js** - JavaScript file handling interactive features like navigation, sliders, and dynamic content.

- **anime.html** - A dedicated page listing all available anime series with filtering and browsing capabilities.

- **download.html, download1-5.html** - Download pages for specific anime series. Each page provides information and download links for individual anime.

- **images/** - Contains all image assets for the website including:
  - Logo and branding images
  - Anime cover images and thumbnails
  - Category-specific images (action, family, children)
  - Screenshot previews
  - Images organized by series (Death Note, Kakegurui, One Punch Man, etc.)

- **video/** - Contains video assets used on the website. **Note:** These video files are moderately large (total ~21 MB). For better Git performance, consider using [Git LFS](https://git-lfs.github.com/) for video files in future updates.

- **.vscode/** - VS Code editor configuration. Contains settings for C/C++ properties, debugging, and editor preferences.

- **tempCodeRunnerFile, tempCodeRunnerFile.cpp** - Temporary files from code editor/runner. These appear to be build artifacts and could be removed or added to .gitignore.

- **LICENSE** - MIT License file for the project.

- **.gitignore** - Git ignore rules configured for static web projects (excludes node_modules, build artifacts, OS files, etc.).

## How to View/Run the Site

### Option 1: Open Directly in Browser
Simply open `index.html` in your web browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

### Option 2: Run a Local HTTP Server
For better compatibility with all features, run a local web server:

**Using Python 3:**
```bash
python3 -m http.server 8000
# Then navigate to http://localhost:8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
# Then navigate to http://localhost:8000
```

**Using Node.js (http-server):**
```bash
npx http-server -p 8000
# Then navigate to http://localhost:8000
```

**Using PHP:**
```bash
php -S localhost:8000
# Then navigate to http://localhost:8000
```

## Features

- 🎨 Modern, responsive design that works on all devices
- 📱 Mobile-friendly navigation and layout
- 🎬 Multiple anime categories (Action, Family, Children)
- 🔍 Browse and search functionality
- 📥 Download pages for individual anime series
- 🎭 Featured anime showcase
- ⚡ Smooth animations and transitions
- 🖼️ Rich media content with images and videos

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons
- Swiper.js (for sliders/carousels)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 maurya752004

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit pull requests.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Notes

- **Large Media Files:** The repository contains video files (~21 MB total). For optimal Git performance, consider migrating large media files to Git LFS or hosting them separately.
- **Temporary Files:** The `tempCodeRunnerFile` and `tempCodeRunnerFile.cpp` files appear to be build artifacts and may be removed if not needed.
- **External Dependencies:** The site uses CDN-hosted libraries (Swiper.js, Font Awesome). An internet connection is required for these features to work properly.

## Contact & Maintainer

**Maintainer:** maurya752004

For questions, suggestions, or support, please open an issue in the repository or contact the maintainer directly.

---

Made with ❤️ for anime fans

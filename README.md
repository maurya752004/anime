# Anime Website

A complete responsive anime website featuring a modern design with anime showcases, categorized content (action, child-friendly, family), and video content.

## 📋 Project Overview

This is a static website built with HTML, CSS, and JavaScript that showcases various anime series and movies. The website features a responsive design with smooth animations, image galleries, and video content. It includes multiple sections for different anime genres including action, child-friendly, and family content.

## 📁 Repository Structure

```
anime/
├── .vscode/                        # VS Code configuration files
│   ├── c_cpp_properties.json      # C/C++ properties (legacy/unused)
│   ├── launch.json                # Debug launch configuration
│   └── settings.json              # Editor settings
├── images/                         # Image assets directory
│   ├── logo.png                   # Website logo
│   ├── home-img-*.jpeg            # Homepage slider images (4 images)
│   ├── anime-img-*.jpg            # General anime images (12 images)
│   ├── action-*.jpg               # Action anime images (8 images)
│   ├── child-*.jpg                # Child-friendly anime images (7 images)
│   ├── family-*.jpg               # Family anime images (8 images)
│   ├── screenshot-img-*.jpeg      # Screenshot images (3 images)
│   ├── download-img.jpeg          # Download section image
│   ├── death*.jpg                 # Death Note series images (3 images)
│   ├── kakegurui*.jpg             # Kakegurui series images (3 images)
│   ├── ONEPUCH*.jpg               # One Punch Man series images (4 images)
│   └── UD6-CSG3.html              # HTML file (likely misplaced)
├── video/                          # Video content directory
│   ├── WhatsApp Video 2024-04-23 at 2.59.36 PM.mp4  # Video file (~5.3 MB)
│   └── WhatsApp Video 2024-04-23 at 3.27.42 PM.mp4  # Video file (~16 MB)
├── index.html                      # Main homepage
├── anime.html                      # Anime showcase page
├── anime.css                       # Main stylesheet
├── anime.js                        # JavaScript functionality
├── download.html                   # Download page
├── download1.html                  # Download page variant 1
├── download2.html                  # Download page variant 2
├── download3.html                  # Download page variant 3
├── download4.html                  # Download page variant 4
├── download5.html                  # Download page variant 5
├── tempCodeRunnerFile              # Temporary executable (should be in .gitignore)
└── tempCodeRunnerFile.cpp          # Temporary C++ source (should be in .gitignore)
```

## 📄 File Descriptions

### Top-Level Files

- **index.html** - The main entry point of the website featuring a home slider, anime categories, and navigation
- **anime.html** - A dedicated page showcasing anime series and related content
- **anime.css** - Contains all the styling for the website including responsive design rules
- **anime.js** - Provides interactivity such as menu toggles, search functionality, and slider controls
- **download.html** through **download5.html** - Various download pages for different anime series

### Directories

- **images/** - Contains all visual assets including logos, anime artwork, screenshots, and promotional images organized by category
- **video/** - Contains video files for the website
  - ⚠️ **Note**: Video files are large (21+ MB total). Consider using Git LFS for better version control of large media files.
- **.vscode/** - VS Code workspace settings (these are typically not committed to repositories)
  - ⚠️ **Note**: The C/C++ configuration files suggest this directory contains legacy/unused configurations.

### Temporary Files

The following files appear to be temporary build artifacts and should not be committed:
- `tempCodeRunnerFile` - Compiled executable
- `tempCodeRunnerFile.cpp` - C++ source file

These have been added to `.gitignore` for future exclusions.

## 🚀 How to View/Run the Site

### Option 1: Direct File Opening
Simply open `anime/index.html` in your web browser:
```bash
# On Linux/Mac
open anime/index.html

# On Windows
start anime/index.html
```

### Option 2: Local HTTP Server (Recommended)

For better compatibility and to avoid CORS issues, use a local HTTP server:

**Using Python:**
```bash
cd anime
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (npx):**
```bash
cd anime
npx http-server -p 8000
```

**Using PHP:**
```bash
cd anime
php -S localhost:8000
```

Then open your browser and navigate to `http://localhost:8000`

## 🎨 Features

- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Smooth Animations** - Uses Swiper.js for slider animations
- **Multiple Categories** - Action, child-friendly, and family anime sections
- **Search Functionality** - Find your favorite anime quickly
- **Video Integration** - Embedded video content
- **Modern UI** - Clean and intuitive interface with Font Awesome icons

## 🔧 Dependencies

The website uses the following external libraries (loaded via CDN):
- **Swiper.js** (v7) - For touch slider functionality
- **Font Awesome** (v6.0.0-beta3) - For icons

## 📦 Large Media Files & Git LFS

This repository contains video files totaling approximately 21 MB. For better performance and version control:

1. **Current State**: Video files are included in the repository
2. **Recommendation**: Consider using Git Large File Storage (Git LFS) for video files
3. **Alternative**: Host large video files on a CDN or video platform (YouTube, Vimeo) and embed them

To use Git LFS in the future:
```bash
git lfs install
git lfs track "*.mp4"
git add .gitattributes
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 maurya752004

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

### How to Contribute:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📧 Contact

**Maintainer:** maurya752004

For questions, suggestions, or issues, please open an issue on GitHub or contact the maintainer directly.

## 🙏 Acknowledgments

- Swiper.js for the slider functionality
- Font Awesome for the icon library
- All anime artists and studios whose work is featured

# Anime Hub

Anime Hub is a college project designed to celebrate the vibrant world of anime. This platform allows users to explore various anime series, character profiles, and genre classifications, fostering a community of anime enthusiasts and showcasing web development skills.

## Features
- Curated lists of anime shows
- Character profiles with detailed information
- Genre classifications for easier discovery (Action, Family, Child-friendly)
- A user-friendly and interactive interface
- Video content for enhanced user experience

## Technologies Used
- **HTML** for structuring the website
- **CSS** for styling and layout
- **JavaScript** for interactive elements and dynamic behavior

## Project Structure

```
anime/
├── .vscode/                    # VS Code configuration
│   ├── c_cpp_properties.json
│   ├── launch.json
│   └── settings.json
├── images/                     # Image assets
│   ├── logo.png
│   ├── home-img-*.jpeg         # Homepage images
│   ├── anime-img-*.jpg         # Anime cover images
│   ├── action-*.jpg            # Action genre images
│   ├── family-*.jpg            # Family genre images
│   ├── child-*.jpg             # Child-friendly content images
│   ├── screenshot-img-*.jpeg   # Screenshot images
│   ├── download-img.jpeg
│   ├── death*.jpg              # Death Note images
│   ├── kakegurui*.jpg          # Kakegurui images
│   ├── ONEPUCH*.jpg            # One Punch Man images
│   └── UD6-CSG3.html           # HTML resource file
├── video/                      # Video assets (21MB total)
│   ├── WhatsApp Video 2024-04-23 at 2.59.36 PM.mp4  (5.3MB)
│   └── WhatsApp Video 2024-04-23 at 3.27.42 PM.mp4  (16MB)
├── index.html                  # Main homepage
├── anime.html                  # Anime listing page
├── anime.css                   # Main stylesheet
├── anime.js                    # JavaScript functionality
├── download.html               # Download page
├── download1.html              # Download page 1
├── download2.html              # Download page 2
├── download3.html              # Download page 3
├── download4.html              # Download page 4
├── download5.html              # Download page 5
├── tempCodeRunnerFile          # Temporary code runner file (binary)
└── tempCodeRunnerFile.cpp      # C++ source file

4 directories, 71 files
```

### Top-Level Files and Folders

- **anime/**: Main project directory containing all source code and assets
  - **index.html**: The main entry point and homepage for the Anime Hub website
  - **anime.html**: Page displaying the anime catalog and listings
  - **anime.css**: Stylesheet containing all visual styling for the website
  - **anime.js**: JavaScript file providing interactivity and dynamic behavior
  - **download*.html**: Multiple download pages for different anime series
  - **images/**: Directory containing all image assets including logos, screenshots, anime covers, and category-specific images (action, family, child-friendly content). Contains 57 image files.
  - **video/**: Directory containing video content. **Note: Contains 2 MP4 files totaling approximately 21MB.**
  - **.vscode/**: VS Code editor configuration files for development environment setup
  - **tempCodeRunnerFile**: Binary executable (temporary development file)
  - **tempCodeRunnerFile.cpp**: C++ source code file (temporary development file)

## How to Run

### Option 1: Open Directly in Browser
1. Clone the repository:
   ```sh
   git clone https://github.com/maurya752004/anime.git
   cd anime
   ```
2. Navigate to the `anime/` directory and open `index.html` in any modern web browser.

### Option 2: Run with a Local HTTP Server (Recommended)
For a better experience, especially if using features that require HTTP protocol:

Using Python:
```sh
cd anime
python -m http.server 8000
# or for Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js (with http-server):
```sh
npm install -g http-server
cd anime
http-server -p 8000
```

Using PHP:
```sh
cd anime
php -S localhost:8000
```

Then open your browser and navigate to `http://localhost:8000`

## Large Media Files Notice

This repository contains video files totaling approximately **21MB** in the `anime/video/` directory:
- `WhatsApp Video 2024-04-23 at 2.59.36 PM.mp4` (5.3MB)
- `WhatsApp Video 2024-04-23 at 3.27.42 PM.mp4` (16MB)

For repositories with larger media files or extensive binary assets, consider:
- **Git LFS (Large File Storage)**: Track large files more efficiently
- **GitHub Releases**: Upload large assets as release attachments
- **External CDN**: Host media files on a content delivery network

## License

This project is open source and available under the [MIT License](LICENSE).

Copyright (c) 2026 maurya752004

## Contribution

Contributions are welcome! Please feel free to:
- Submit a pull request with improvements or new features
- File an issue for bug reports or feature requests
- Suggest new anime to be added to the catalog
- Improve the UI/UX design

### Maintainer

**Author**: [maurya752004](https://github.com/maurya752004)  
**Contact**: GitHub [@maurya752004](https://github.com/maurya752004)  
**Year**: 2026

---

**Enjoy exploring the world of anime with Anime Hub!** 🎌✨

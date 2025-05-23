Smart AdSizer - Lightweight Social Media Image Formatter

Smart AdSizer is an ultra-lightweight, dependency-free tool that automatically crops images to fit various social media platform dimensions. It runs entirely in the browser with no server requirements.
Features

    Zero Dependencies: A single HTML file with vanilla JavaScript - no frameworks, no build tools
    Comprehensive Format Library: Includes over 40 standard sizes for all major social platforms
    Intelligent Cropping: Automatically determines the best way to crop your image while maintaining important visual elements
    Bulk Processing: Crop a single image to multiple formats at once
    Custom Sizes: Add your own custom dimensions for specialized needs
    Downloadable Results: Download individual images or all formats as a ZIP file
    User-Friendly Interface: Organized by platform with collapsible sections
    Offline Capable: Works without an internet connection

Supported Platforms

    📘 Facebook: Profile Pictures, Cover Photos, Feed Posts, Stories, Ads, and more
    📸 Instagram: Profile Pictures, Posts (Square, Portrait, Landscape), Stories, Reels, Ads
    🐦 X / Twitter: Profile Pictures, Headers, Tweet Images, Cards
    📌 Pinterest: Profile Pictures, Pins (Standard, Square, Long), Board Covers
    📺 YouTube: Profile Pictures, Channel Art, Thumbnails
    💼 LinkedIn: Profile Pictures, Banners, Company Images, Posts, Stories
    🎵 TikTok: Profile Pictures, Video Formats, Ad Creatives
    📱 Threads: Profile Pictures, Post Images, Stories
    📣 Snapchat: Stories, Geofilters
    📲 Universal Standards: Cross-platform formats for general use

How to Use

    Download: Save the HTML file to your computer
    Open: Double-click the file to open it in any modern browser
    Upload: Drag and drop an image or click to select one
    Select Formats: Choose which social media formats you need
    Process: Click "Process Image" to crop your image to all selected formats
    Download: Download individual images or get all as a ZIP file

Custom Formats

Create your own custom dimensions:

    Enter the width and height in pixels
    Give your custom format a name (optional)
    Click "Add Custom Format"
    Your custom format will appear in the custom formats section

Technical Details

    File Size: ~40KB uncompressed HTML file
    Browser Compatibility: Works in all modern browsers (Chrome, Firefox, Safari, Edge)
    Image Processing: All image processing happens locally in your browser
    Privacy: Your images never leave your computer
    Limitations: Large images may require more processing time and memory

Installation Options
Local Use

Simply download the HTML file and open it in your browser. No installation required.
Web Server Deployment

Upload the HTML file to any web server or hosting service:

    GitHub Pages
    Netlify
    Vercel
    Any standard web hosting

Integration with Existing Sites

The entire application can be embedded in an iframe or the code can be integrated into an existing page.
Performance Notes

    For very large images (>10MB or >4000px), processing may take longer
    The ZIP download functionality loads the JSZip library only when needed
    All processing happens on the client side, so performance depends on the user's device

Future Development Ideas

    Advanced cropping with manual position adjustment
    Text overlay options for common ad formats
    Batch processing of multiple source images
    Image optimization options (compression level, format conversion)
    Filter and effect presets

License

MIT License - Feel free to use, modify, and distribute as needed.
Author

Created as an ultra-lightweight alternative to complex image editing tools specifically for social media marketers, content creators, and digital agencies.
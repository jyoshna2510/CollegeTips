# CollegeTips Gallery

A modern, responsive photo gallery website showcasing the vibrant culture and activities of CollegeTips. This interactive gallery allows visitors to explore different aspects of our team through categorized photo collections.

## 🌟 Features

- **Responsive Design**: Looks great on all devices - desktop, tablet, and mobile
- **Category Filtering**: Easily navigate through different photo categories:
  - Team Vibes 🤝
  - Creative Campaigns 🎨
  - Work Hard, Play Hard 🥳
  - Behind-The-Scenes 🎥
- **Interactive UI**: Smooth hover effects and transitions
- **Modern Layout**: Clean and professional grid-based design
- **Easy Navigation**: Simple category filters for quick access to specific content

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons

## 📦 Project Structure

```
collegetips/
├── gallery.html      # Main HTML file
├── gallery.css       # Stylesheet
├── img/             # Image assets
└── README.md        # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/collegetips.git
   ```

2. Open `gallery.html` in your web browser to view the gallery locally.

## 🎨 Customization

### Adding New Images
1. Place new images in the `img/` directory
2. Add new gallery items in `gallery.html` following the existing structure:
   ```html
   <div class="gallery-item" data-category="category-name">
       <img src="img/your-image.png" alt="Description">
       <div class="overlay">
           <h3>Title</h3>
           <p>Description</p>
       </div>
   </div>
   ```

### Modifying Categories
To add or modify categories:
1. Add a new filter button in the category-filters div
2. Update the data-category attributes accordingly

## 📱 Responsive Design

The gallery is fully responsive and optimized for:
- Desktop (1200px and above)
- Tablet (768px to 1199px)
- Mobile (up to 767px)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source.

Made with ❤️

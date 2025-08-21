# Shopify Components Repository

A collection of reusable Shopify Liquid components and tools for building modern, interactive e-commerce experiences.

## 🚀 Components

### 1. Rotating Announcement Bar
**Location:** `Rotating Announcement Bar/Rotating-announcement.liquid`

A dynamic, customizable announcement bar that rotates through multiple messages with smooth transitions and typing effects.

#### Features:
- **Customizable Height**: Adjustable bar height (30px - 200px)
- **Color Customization**: Background, text, and cursor colors
- **Typography Control**: Adjustable text size
- **Animation Settings**: Configurable typing speed and rotation period
- **Multiple Announcements**: Support for unlimited announcement blocks
- **Optional Links**: Each announcement can include clickable links
- **Accessibility**: ARIA labels and screen reader support
- **Responsive Design**: Works across all device sizes

#### Usage:
1. Add the section to your Shopify theme
2. Configure colors, dimensions, and timing in the theme customizer
3. Add announcement blocks with your text and optional links
4. The bar will automatically rotate through all announcements

#### Customization Options:
- **Bar Height**: 30px - 200px
- **Background Color**: Any hex color
- **Text Color**: Any hex color
- **Text Size**: Adjustable font size
- **Cursor Color**: Blinking cursor color
- **Typing Speed**: 50ms - 500ms (lower = faster)
- **Rotation Period**: 1s - 9s between transitions

---

### 2. Hero Custom Slider
**Location:** `shopify SLider/V1/`

A customizable hero slider component for showcasing products, promotions, or brand content.

#### Files:
- `hero-custom-slider.liquid` - Main slider component
- `hero-custom-slider.css` - Styling and animations

#### Features:
- **Multiple Slides**: Support for unlimited slide content
- **Customizable Content**: Text, images, and call-to-action buttons
- **Responsive Design**: Optimized for all screen sizes
- **Smooth Transitions**: Professional slide animations
- **Theme Integration**: Seamlessly integrates with existing Shopify themes

---

## 🛠️ Installation

### Prerequisites
- Shopify store with theme editing access
- Basic knowledge of Shopify Liquid templating

### Setup Instructions
1. **Clone or download** this repository
2. **Navigate** to your Shopify theme files
3. **Copy** the desired component files to your theme
4. **Add** the component sections to your theme templates
5. **Customize** the settings through your theme customizer

### File Structure
```
Shopify/
├── Rotating Announcement Bar/
│   └── Rotating-announcement.liquid
├── shopify SLider/
│   └── V1/
│       ├── hero-custom-slider.css
│       └── hero-custom-slider.liquid
├── .gitignore
└── README.md
```

## 🎨 Customization

### Theme Customizer
Both components are designed to work with Shopify's theme customizer, allowing store owners to:
- Change colors and fonts without code editing
- Adjust timing and animation settings
- Add/remove content blocks
- Preview changes in real-time

### Advanced Customization
For developers who want to modify the components:
- Edit the `.liquid` files for structural changes
- Modify the CSS files for styling adjustments
- Update the JavaScript for behavior modifications

## 🔧 Technical Details

### Technologies Used
- **Shopify Liquid**: Template language for dynamic content
- **CSS3**: Modern styling with transitions and animations
- **JavaScript**: Interactive functionality and animations
- **HTML5**: Semantic markup structure

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Design

All components are built with mobile-first responsive design principles:
- Flexible layouts that adapt to screen sizes
- Touch-friendly interactions for mobile devices
- Optimized performance across all devices
- Consistent user experience regardless of screen size

## 🚀 Performance

### Optimization Features
- Minimal JavaScript footprint
- Efficient CSS animations using transform properties
- Optimized image loading and handling
- Reduced DOM manipulation for smooth performance

### Best Practices
- Use appropriate image sizes for your content
- Limit the number of announcement blocks for optimal performance
- Test on various devices and connection speeds

## 🤝 Contributing

### How to Contribute
1. Fork this repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test components across different Shopify themes
- Ensure responsive design works on all devices
- Document any new features or changes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

### Getting Help
- Check the component documentation above
- Review the code comments for implementation details
- Test in a development environment first
- Ensure your Shopify theme supports the required features

### Common Issues
- **Component not appearing**: Check if the section is added to your template
- **Styling issues**: Verify CSS files are properly linked
- **Animation problems**: Check browser compatibility and JavaScript console

## 🔄 Updates

### Version History
- **V1.0.0**: Initial release with Rotating Announcement Bar and Hero Slider
- Future updates will include additional components and improvements

### Stay Updated
- Watch this repository for new releases
- Check the changelog for detailed update information
- Follow best practices for updating components in production

---

## 📞 Contact

For questions, suggestions, or support:
- **Repository**: [GitHub Issues](https://github.com/Abd-Elrhman/Shopify-Components/issues)
- **Contributions**: Pull requests are welcome!

---

*Built with ❤️ for the Shopify community*

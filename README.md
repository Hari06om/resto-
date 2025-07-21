# Savor & Spice Bistro - Restaurant Website

A modern, responsive restaurant website for Savor & Spice Bistro, featuring an elegant design with smooth animations and interactive elements.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations and hover effects
- **Interactive Navigation**: Mobile-friendly hamburger menu with smooth transitions
- **Smooth Scrolling**: Seamless navigation between sections
- **Back to Top Button**: Convenient scroll-to-top functionality
- **Customer Reviews**: Dedicated section showcasing customer testimonials
- **Contact Information**: Easy-to-find contact details and reservation system

## 📁 Project Structure

```
savor-spice-bistro/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── app.js              # JavaScript functionality
└── images/             # Image assets
    ├── plate1.png      # Hero section food image
    ├── tablesetting.jpg # About section image
    ├── quote-img2.png  # Review quote icons
    └── pfp.png         # Customer profile pictures
```



## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6)**: Interactive functionality
- **Font Awesome**: Icons for social media and UI elements
- **Google Fonts**: Poppins font family for typography

## 🎨 Design Features

### Visual Elements
- **Geometric Shapes**: Stylish triangular design element
- **Color Scheme**: Primary color (#222) with elegant neutral tones
- **Typography**: Poppins font for modern, readable text
- **Animations**: Smooth hover effects and transitions

### Layout Sections
1. **Header**: Navigation with brand name and menu links
2. **Hero Section**: Welcome message with call-to-action
3. **About Section**: Restaurant story and philosophy
4. **Reviews Section**: Customer testimonials with star ratings
5. **Contact Section**: Contact information and reservation details

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 550px - 767px
- **Small Mobile**: Below 550px

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)

### Installation
1. Clone or download the project files
2. Ensure all files are in the same directory
3. Create an `images` folder and add the required image files:
   - `plate1.png` (hero section)
   - `tablesetting.jpg` (about section)
   - `quote-img2.png` (review quotes)
   - `pfp.png` (customer profiles)

### Running the Website
1. Open `index.html` in your web browser
2. The website will load with all interactive features

## 🎯 Key JavaScript Features

### Back to Top Button
- Appears when user scrolls down 75px
- Smooth scroll animation back to top
- Hover effect with upward movement

### Mobile Navigation
- Hamburger menu for mobile devices
- Smooth slide-in/slide-out animation
- Auto-close when navigation link is clicked
- Backdrop blur effect for modern look

### Code Structure
```javascript
// Back to top functionality
const toTop = document.querySelector(".back-top")
window.addEventListener("scroll", () => {
    if(pageYOffset > 75){
        toTop.classList.add("active")
    }else{
        toTop.classList.remove("active")
    }
})

// Mobile navigation toggle
const burger = document.querySelector(".burger")
const sidebar = document.querySelector(".links")
const links = document.querySelectorAll(".links li a")

function toggleSidebar(){
    sidebar.classList.toggle("show")
}
```

## 🎨 CSS Highlights

### Custom Properties
```css
:root {
  --primary: #222;
}
```

### Key Animations
- Smooth navigation link underline effects
- Icon hover transformations
- Mobile menu slide transitions
- Back to top button animations

### Responsive Design
- Mobile-first approach
- Flexible grid layouts
- Scalable typography
- Touch-friendly interface

## 🖼️ Required Images

Make sure to include these images in your `images/` folder:
- `plate1.png` - Food plate for hero section
- `tablesetting.jpg` - Table setting for about section
- `quote-img2.png` - Quote icons for reviews
- `pfp.png` - Generic profile picture for customers

## 📧 Contact Information

The website includes contact details for:
- **Email**: info@savorandspicebistro.com
- **Phone**: +1 (123) 456-7890
- **Social Media**: @savorandspice

## 🔧 Customization

### Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
  --primary: #222; /* Change to your brand color */
}
```

### Content
- Update restaurant information in `index.html`
- Replace placeholder images with actual restaurant photos
- Modify contact details and social media links

### Fonts
Current font: Poppins from Google Fonts
To change: Update the Google Fonts import in the CSS file

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements.

---

**Built with ❤️ for Savor & Spice Bistro**

# 🌸 Flowfy - Beautiful Bouquets Website

A modern, responsive website for Flowfy, a premium flower bouquet shop located in Bojongsoang, Bandung. This project features an elegant mobile-first design with smooth animations and integrated WhatsApp ordering system.

## ✨ Features

### 🎨 Modern Design
- **Mobile-first responsive design** optimized for all screen sizes
- **Beautiful gradient backgrounds** with animated floating elements
- **Glassmorphism effects** with backdrop blur for modern aesthetics
- **Smooth animations** and hover effects throughout the interface
- **Contemporary color scheme** with pink and purple gradients

### 📱 User Experience
- **Interactive product cards** with hover animations
- **Modal-based ordering system** with comprehensive form
- **Delivery/Pickup selection** with visual feedback
- **Real-time form validation** and input formatting
- **WhatsApp integration** for seamless order processing

### 🛍️ E-commerce Features
- **Product showcase** with images, pricing, and discount display
- **Custom bouquet option** with special handling
- **Order form** with customer details, delivery preferences, and custom messages
- **Date/time picker** with business hours validation
- **Automatic WhatsApp message generation** with order details

### 🚀 Technical Features
- **Pure HTML, CSS, and JavaScript** - no external dependencies
- **CSS Grid and Flexbox** for responsive layouts
- **CSS animations and transitions** for smooth interactions
- **Form validation** and user input sanitization
- **Local storage** for temporary data handling
- **Cross-browser compatibility**

## 🏗️ Project Structure

```
flowfy-website/
├── index.html              # Main HTML file with embedded CSS and JS
├── images/                 # Product images directory
│   ├── 500131920_17844990513488890_509485197936157356_n.jpg
│   ├── 501159486_17845071756488890_1116318068030086047_n.jpg
│   └── 501679534_17846087607488890_4761912365636862771_n.jpg
└── README.md              # This file
```

## 🎯 Products Featured

1. **Lily Elegance Bouquet** - Premium lily arrangement (Rp 175.000)
2. **Blue Harmony Bouquet** - Beautiful blue-themed bouquet (Rp 165.000)
3. **Gerbera Sunshine Bouquet** - Bright gerbera arrangement (Rp 155.000)
4. **Custom Bouquet** - Personalized arrangements (Price on request)

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/flowfy-website.git
   cd flowfy-website
   ```

2. **Add product images:**
   - Place your product images in the root directory
   - Update image paths in the HTML if necessary

3. **Configure WhatsApp number:**
   - Open `index.html`
   - Find the WhatsApp URL in the JavaScript section
   - Replace `6281247563841` with your WhatsApp business number

4. **Launch the website:**
   - Open `index.html` in your web browser
   - Or serve it using a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     ```

## 📱 Usage

### For Customers:
1. **Browse Products** - View available bouquet options with prices
2. **Select Product** - Click on any product card to open order form
3. **Fill Order Details** - Provide name, phone, delivery preferences
4. **Choose Delivery Method** - Select between delivery or pickup
5. **Set Date & Time** - Pick preferred delivery/pickup schedule
6. **Add Custom Message** - Include greeting card message
7. **Submit Order** - Automatically opens WhatsApp with formatted message

### For Business Owners:
- **Easy Customization** - Update products, prices, and business information
- **WhatsApp Integration** - Receive orders directly via WhatsApp
- **Mobile Optimization** - Perfect for social media sharing
- **No Backend Required** - Simple deployment and maintenance

## 🎨 Customization

### Colors & Branding
```css
/* Main brand colors */
:root {
  --primary-gradient: linear-gradient(135deg, #f8bbd9 0%, #e8a5c8 100%);
  --secondary-gradient: linear-gradient(135deg, #e8a5c8 0%, #d4a5e8 100%);
  --background-gradient: linear-gradient(135deg, #fef7f0 0%, #f8e8f5 100%);
}
```

### Business Information
Update the following in the HTML:
- Business name and tagline in the banner section
- Social media links
- Contact information in About section
- WhatsApp number in JavaScript
- Business hours and location

### Products
Add or modify products by:
1. Adding product images to the directory
2. Creating new product cards in the HTML
3. Updating the `orderProduct` function calls

## 📊 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty)
3. Set publish directory: `/`
4. Deploy automatically on push

### Vercel
1. Import your GitHub repository
2. No build configuration needed
3. Deploy with one click

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support or questions about this project:
- Create an issue on GitHub
- Contact: [yogaradit123@gmail.com]

## 🙏 Acknowledgments

- Design inspiration from modern florist websites
- Icons and emojis for enhanced visual appeal
- CSS techniques from modern web development practices
- WhatsApp Business API for seamless order processing

---

**Made with 💖 for Flowfy - Beautiful Bouquets for Every Moment**
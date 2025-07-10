# 🚀 AICODESHUB - AI Automation Agency  

A modern, responsive website for aicodeshub, a global AI automation agency specializing in custom chatbots and business automation solutions. Built with Vue 3, TypeScript, and Tailwind CSS.  

![Project Logo](https://github.com/samade747/www.AICODESHUB.com/blob/main/AI%20Codes%20Hub%20Logo%20-%20Flat%20Vector%20Style%20(1).png)


## 🌟 Features

### 🎨 **Modern Design & UX**
- **Responsive Design**: Mobile-first approach with seamless desktop experience
- **Dark/Light Theme**: Automatic theme switching with smooth transitions
- **Custom Animations**: PrimeVue AnimateOnScroll with fade-up, slide-in, and zoom effects
- **Interactive Elements**: Hover animations, smooth scrolling, and micro-interactions
- **Professional Branding**: Orange theme with gradient accents and modern typography

### 🤖 **AI-Focused Content**
- **Hero Section**: Video background with AI automation messaging
- **Technology Partners**: Scrolling showcase of AI platforms (OpenAI, Anthropic, AWS, etc.)
- **Benefits Section**: AI-powered automation benefits with contextual icons
- **Features Section**: AI-first architecture, integrations, and security features
- **Services**: AI Agent Automation, Chatbot Development, Web & Mobile Development

### 📧 **Contact & Communication**
- **EmailJS Integration**: Contact form and newsletter subscription
- **Form Validation**: Real-time validation with error handling
- **Auto-hide Messages**: Success/error messages with timeout functionality
- **Professional Email Templates**: Branded email templates for client communication

### 🔧 **Technical Features**
- **TypeScript**: Full type safety and better development experience
- **Component Architecture**: Modular, reusable components with shadcn/ui
- **SEO Optimized**: Meta tags, structured data, and international SEO
- **Performance**: Optimized images, lazy loading, and efficient animations
- **Accessibility**: ARIA labels, keyboard navigation, and semantic HTML

## 🛠️ Tech Stack

### **Frontend Framework**
- **Vue 3** - Progressive JavaScript framework
- **TypeScript** - Type-safe JavaScript
- **Vite** - Fast build tool and dev server

### **Styling & UI**
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - Beautiful, accessible component library
- **Lucide Icons** - Contextually relevant icons
- **PrimeVue** - Animation library for scroll effects

### **External Services**
- **EmailJS** - Email service for contact forms and newsletter
- **VueUse** - Vue composition utilities

### **Development Tools**
- **Vue TSC** - TypeScript compiler for Vue
- **Autoprefixer** - CSS vendor prefixing
- **Tailwind Animate** - Animation utilities

## 📁 Project Structure

```
aicodeshub_website/
├── public/                 # Static assets
│   ├── logo.png           # Company logo
│   ├── hero.mp4           # Hero video background
│   ├── *.png              # Technology partner logos
│   └── *.jpeg             # Social media logos
├── src/
│   ├── components/        # Vue components
│   │   ├── ui/           # shadcn/ui components
│   │   ├── Navbar.vue    # Navigation with popup modals
│   │   ├── Hero.vue      # Hero section with video
│   │   ├── Benefits.vue  # AI benefits with icons
│   │   ├── Features.vue  # AI features showcase
│   │   ├── Services.vue  # Service offerings
│   │   ├── Sponsors.vue  # Technology partners
│   │   ├── Contact.vue   # Contact form with EmailJS
│   │   ├── Footer.vue    # Footer with newsletter
│   │   └── ...           # Other sections
│   ├── assets/
│   │   └── index.css     # Global styles and theme
│   ├── lib/
│   │   └── utils.ts      # Utility functions
│   ├── App.vue           # Main app component
│   └── main.ts           # App entry point
├── index.html            # HTML template with SEO
├── tailwind.config.js    # Tailwind configuration
├── vite.config.ts        # Vite configuration
└── package.json          # Dependencies and scripts
```

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v16 or higher)
- **npm** or **yarn**

### Installation

1. **Clone the repository**
   ```bash
   git clone 
   cd aicodeshub_website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory:
   ```env
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_public_key
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 🎯 Key Components

### **Navbar Component**
- Responsive navigation with mobile menu
- Theme toggle functionality
- "Coming Soon" popup for Portfolio/About links
- Smooth scroll navigation

### **Hero Section**
- Video background with custom controls
- Gradient overlays and animations
- Call-to-action buttons
- YouTube reference link

### **Technology Partners**
- Scrolling animation showcase
- AI platform logos (OpenAI, Anthropic, AWS, etc.)
- Responsive grid layout

### **Contact Form**
- EmailJS integration
- Form validation
- Success/error handling
- Professional email templates

### **Newsletter Subscription**
- EmailJS integration
- Auto-hide success messages
- Form validation
- Responsive design

## 🎨 Design System

### **Color Palette**
- **Primary**: Orange (#f97316) - Brand color
- **Background**: Light/Dark theme support
- **Text**: High contrast for accessibility
- **Accents**: Gradient combinations

### **Typography**
- Modern, clean fonts
- Responsive sizing
- Proper hierarchy

### **Animations**
- PrimeVue AnimateOnScroll
- Custom CSS animations
- Smooth transitions
- Hover effects

## 📧 EmailJS Configuration

The website uses EmailJS for contact forms and newsletter subscriptions. Configure the following environment variables:

```env
VITE_EMAILJS_SERVICE_ID=your_emailjs_service_id
VITE_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
```

### **Email Templates**
- **Contact Form**: Professional inquiry template
- **Newsletter**: Subscription confirmation template
- **Branding**: Orange theme with company logo

## 🌐 SEO & Performance

### **SEO Features**
- Meta tags for social sharing
- Structured data (Schema.org)
- International SEO support
- Optimized images and videos
- Semantic HTML structure

### **Performance Optimizations**
- Lazy loading components
- Optimized images
- Efficient animations
- Minimal bundle size
- Fast loading times

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Customization

### **Theme Colors**
Edit `src/assets/index.css` to modify the color scheme:
```css
:root {
  --primary: 24.6 95% 53.1%; /* Orange */
  --background: 0 0% 100%;   /* White */
  /* ... other colors */
}
```

### **Animations**
Customize animations in `tailwind.config.js`:
```javascript
keyframes: {
  "logo": { /* Custom logo animation */ },
  "logo-hover": { /* Hover effects */ }
}
```

### **Content**
Update component data in respective Vue files:
- `src/components/Benefits.vue` - Benefits list
- `src/components/Features.vue` - Features list
- `src/components/Services.vue` - Services list
- `src/components/Sponsors.vue` - Technology partners

## 🚀 Deployment

### **Build for Production**
```bash
npm run build
```

### **Preview Production Build**
```bash
npm run preview
```

### **Deploy to Vercel**
1. Connect your GitHub repository to Vercel
2. Set environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

### **Deploy to Netlify**
1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Configure environment variables

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- **Email**: AICODESHUB@GMAIL.COM   
- **Phone**: +923328222026
- **Website**: AICODESHUB@GMAIL.COM

## 🙏 Acknowledgments

- **shadcn/ui** for beautiful components
- **Lucide** for amazing icons
- **PrimeVue** for smooth animations
- **Tailwind CSS** for utility-first styling
- **Vue.js** for the amazing framework

---

**Built with ❤️ by AICODESHUB TEAM(maryam faizan & abdulsamad)**

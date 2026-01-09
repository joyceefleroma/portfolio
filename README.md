# Joycee Fleroma Vanja - Portfolio Website

A modern, responsive portfolio website showcasing my work as a UI/UX and Graphic Designer.

## 🎨 Features

- **Modern Design**: Elegant pink and blue color palette with soft gradients
- **Fully Responsive**: Mobile-first approach with smooth navigation
- **Interactive Elements**: Hover effects, smooth scrolling, and animations
- **Professional Layout**: Card-based design with clean typography
- **Profile Showcase**: Prominent profile image with gradient glow effect

## 📁 Project Structure

```
my_portfolio/
├── index.html          # Main HTML file
├── js/
│   └── script.js      # JavaScript for interactions
├── assets/
│   └── images/
│       └── profile.jpg # Profile picture (add your image here)
└── README.md          # This file
```

## 🚀 Quick Start

1. **Clone or download this repository**
   ```bash
   git clone <your-repo-url>
   cd my_portfolio
   ```

2. **Add your profile image**
   - Place your profile picture in `assets/images/profile.jpg`
   - Recommended size: 800x800px (square image)
   - Format: JPG, PNG, or WebP

3. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for better experience:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

## 🌐 Deployment

### Option 1: GitHub Pages

1. **Push your code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio website"
   git branch -M main
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click on **Settings** → **Pages**
   - Under **Source**, select `main` branch
   - Click **Save**
   - Your site will be live at: `https://<username>.github.io/<repository-name>`

### Option 2: Vercel

1. **Install Vercel CLI** (optional)
   ```bash
   npm i -g vercel
   ```

2. **Deploy via Vercel Dashboard**
   - Go to [vercel.com](https://vercel.com)
   - Sign in with GitHub
   - Click **New Project**
   - Import your GitHub repository
   - Vercel will auto-detect settings
   - Click **Deploy**

3. **Deploy via CLI**
   ```bash
   vercel
   ```
   Follow the prompts to deploy your site.

### Option 3: Netlify

1. **Drag and Drop**
   - Go to [netlify.com](https://netlify.com)
   - Drag and drop your project folder
   - Your site will be live instantly

2. **Git Integration**
   - Connect your GitHub repository
   - Netlify will auto-deploy on every push

## 🎯 Website Flow Chart

```
┌─────────────────────────────────────────────────────────────┐
│                         PORTFOLIO WEBSITE                     │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
                    ┌─────────────────┐
                    │   NAVIGATION    │
                    │     (Fixed)     │
                    └─────────────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
┌──────────────┐    ┌──────────────┐    ┌──────────────┐
│     HOME     │───▶│    ABOUT     │───▶│    SKILLS    │
│              │    │              │    │              │
│ - Profile    │    │ - Career     │    │ - Programming│
│   Image      │    │   Objective  │    │ - Tools      │
│ - Hero Text  │    │ - Background │    │ - Languages  │
│ - CTA Buttons│    │ - Interests  │    │ - OS         │
└──────────────┘    └──────────────┘    └──────────────┘
        │                     │                     │
        │                     ▼                     │
        │            ┌──────────────┐               │
        │            │   PROJECTS   │               │
        │            │              │               │
        │            │ - Travel     │               │
        │            │   Blog       │               │
        │            │ - Aqua       │               │
        │            │   Plastic    │               │
        │            └──────────────┘               │
        │                     │                     │
        │                     ▼                     │
        │            ┌──────────────┐               │
        │            │  EXPERIENCE  │               │
        │            │              │               │
        │            │ - NPTEL      │               │
        │            │ - CISCO      │               │
        │            │ - Infosys    │               │
        │            │ - CORIZO     │               │
        │            └──────────────┘               │
        │                     │                     │
        │                     ▼                     │
        │            ┌──────────────┐               │
        │            │   EDUCATION  │               │
        │            │              │               │
        │            │ - B.Tech CSE │               │
        │            │ - Intermediate│              │
        │            │ - SSC        │               │
        │            └──────────────┘               │
        │                     │                     │
        └─────────────────────┼─────────────────────┘
                              ▼
                    ┌──────────────┐
                    │   CONTACT    │
                    │              │
                    │ - Email      │
                    │ - Phone      │
                    │ - Location   │
                    │ - LinkedIn   │
                    │ - Interests  │
                    └──────────────┘
                              │
                              ▼
                    ┌──────────────┐
                    │    FOOTER    │
                    └──────────────┘
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Poppins font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

### Colors
The color scheme uses Tailwind's pink and blue colors. To customize:
- Edit the gradient classes in `index.html`
- Modify the `gradient-pink-blue` and `gradient-pink-blue-reverse` classes in the `<style>` section

### Content
- Update personal information in the respective sections
- Add/remove projects, skills, or certifications as needed
- Replace placeholder profile image with your own

## 📝 License

This project is open source and available for personal use.

## 📧 Contact

- **Email**: joyceefleromavanja@gmail.com
- **LinkedIn**: [Joycee Fleroma Vanja](https://www.linkedin.com/in/joycee-fleroma-vanja-91695b337)
- **Phone**: 6303960428

---

Made with ❤️ by Joycee Fleroma Vanja













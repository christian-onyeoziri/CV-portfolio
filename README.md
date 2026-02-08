# Christian Onyeoziri - Engineering Portfolio

A modern, professional portfolio website showcasing mechanical engineering expertise, projects, and experience.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `your-username.github.io` (e.g., `christian-onyeoziri.github.io`)
3. Make it **Public**
4. Don't initialize with README (you'll upload files)

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag and drop the `index.html` file
3. Commit the changes

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** → **Pages**
2. Under "Source", select **main** branch
3. Click **Save**
4. Your site will be live at `https://your-username.github.io` in a few minutes!

## 🎨 Design Features

- **Industrial-Modern Aesthetic**: Engineering-inspired design with technical grid background
- **Distinctive Typography**: Space Mono + Manrope font pairing for technical yet refined look
- **Bold Color Scheme**: Dark theme with orange/amber accents for high contrast
- **Smooth Animations**: Scroll-triggered animations for engaging user experience
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Single File**: Everything in one HTML file - easy to deploy and maintain

## ✏️ Customization Guide

### Update Personal Information

#### Contact Details
Find this section around line 180 and update:
```html
<a href="mailto:YOUR-EMAIL@gmail.com" class="contact-card">
<a href="tel:+234YOURNUMBER" class="contact-card">
<a href="https://linkedin.com/in/YOUR-LINKEDIN" target="_blank" class="contact-card">
```

#### GitHub Profile Link
Add your GitHub link to the contact section:
```html
<a href="https://github.com/YOUR-USERNAME" target="_blank" class="contact-card">
    <div class="contact-icon">💻</div>
    <div class="contact-label">GitHub</div>
    <div class="contact-value">YOUR-USERNAME</div>
</a>
```

### Add More Projects

Find the projects section (around line 350) and duplicate this structure:
```html
<div class="project-card scroll-animate">
    <div class="project-icon">🔧</div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-date">Month Year</p>
    <p class="project-description">
        Description of your project and its impact...
    </p>
</div>
```

**Project Icon Options:**
- 🔧 Mechanical/Tools
- ⚙️ Engineering/Gears
- 🔬 Research/Science
- 🏆 Awards/Achievement
- 🚀 Innovation
- 💡 Ideas/Concept
- 📊 Analytics/Data
- 🎯 Precision/Goals

### Change Color Scheme

Colors are defined at the top in CSS variables (around line 10). Modify these:

```css
:root {
    --primary: #0A0E27;        /* Dark background */
    --accent: #FF6B35;         /* Main orange accent */
    --accent-secondary: #F7931E; /* Secondary amber accent */
    --text: #E8E9ED;           /* Main text color */
    --text-muted: #A0A3BD;     /* Muted text */
    --surface: #1A1F3A;        /* Card backgrounds */
    --surface-light: #252B4A;  /* Lighter surfaces */
}
```

**Pre-made Color Palettes:**

**Blue Professional:**
```css
--accent: #2E7CF6;
--accent-secondary: #00D4FF;
```

**Green Tech:**
```css
--accent: #00E396;
--accent-secondary: #00B8D4;
```

**Purple Creative:**
```css
--accent: #9D4EDD;
--accent-secondary: #E0AAFF;
```

### Update Statistics

Find the stats section (around line 220) and update numbers:
```html
<div class="stat-number">7+</div>
<div class="stat-label">Years Experience</div>
```

### Add Resume Download

Add this button to the hero section buttons:
```html
<a href="your-resume.pdf" download class="btn btn-secondary">Download Resume</a>
```
Then upload your PDF resume to the same repository.

## 📱 Social Media Integration

### Add Social Links
Create a social links section in the footer:

```html
<div style="margin: 20px 0;">
    <a href="https://github.com/YOUR-USERNAME" style="margin: 0 10px; color: var(--accent);">GitHub</a>
    <a href="https://linkedin.com/in/YOUR-PROFILE" style="margin: 0 10px; color: var(--accent);">LinkedIn</a>
    <a href="https://twitter.com/YOUR-HANDLE" style="margin: 0 10px; color: var(--accent);">Twitter</a>
</div>
```

## 🔧 Advanced Customization

### Add Dark/Light Mode Toggle
The portfolio is currently dark mode only. To add a toggle, you'll need to:
1. Define light mode color variables
2. Add a toggle button
3. Use JavaScript to switch between themes
4. Store preference in localStorage

### Connect to a Backend
To add a contact form that actually sends emails:
1. Use [Formspree](https://formspree.io) (free tier available)
2. Or integrate with [EmailJS](https://www.emailjs.com/)
3. Replace the contact cards with a form

### Add Analytics
Track visitors with Google Analytics:
1. Get a tracking ID from [Google Analytics](https://analytics.google.com)
2. Add this before `</head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-TRACKING-ID');
</script>
```

## 📝 Content Tips

### Writing Project Descriptions
Focus on:
- **Problem**: What challenge did you solve?
- **Solution**: What did you build/design?
- **Impact**: What were the results? (Use numbers!)

Example:
"Designed automated sorting system that reduced processing time by 40% and improved accuracy to 99.5%"

### Highlighting Achievements
Use action verbs:
- Engineered, Designed, Developed
- Optimized, Improved, Enhanced
- Led, Managed, Coordinated
- Implemented, Executed, Delivered

## 🐛 Troubleshooting

**Site not showing up?**
- Wait 5-10 minutes after enabling GitHub Pages
- Check Settings → Pages to see deployment status
- Make sure repository is public
- File must be named `index.html` (lowercase)

**Fonts not loading?**
- Check internet connection (fonts load from Google Fonts CDN)
- If offline, fonts will fallback to system defaults

**Animations not working?**
- Make sure JavaScript is enabled in browser
- Check browser console for errors (F12)

## 📄 License

Feel free to use this portfolio template for your own projects. Attribution appreciated but not required.

## 🤝 Contributing

If you find issues or want to suggest improvements, feel free to open an issue or submit a pull request!

---

**Made with precision** ⚙️ **by Christian Onyeoziri**

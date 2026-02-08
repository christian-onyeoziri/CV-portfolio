# Quick Setup Guide (Non-Technical)

## What You're Getting
A professional portfolio website that will be hosted at: `https://your-username.github.io`

This is **completely free** and takes about **10 minutes** to set up!

---

## Step-by-Step Setup (With Screenshots Guide)

### Step 1: Create GitHub Account (if you don't have one)
1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process
4. Choose a professional username (e.g., "christian-onyeoziri")

---

### Step 2: Create Your Portfolio Repository

1. **Once logged into GitHub**, click the **"+"** icon in the top-right corner
2. Click **"New repository"**
3. **Name your repository**: `your-username.github.io`
   - ⚠️ **Important**: Replace "your-username" with YOUR actual GitHub username
   - Example: If your username is "christian-onyeoziri", name it: `christian-onyeoziri.github.io`
4. Make sure it's set to **Public** (not Private)
5. **DO NOT** check "Add a README file" or any other options
6. Click **"Create repository"**

---

### Step 3: Upload Your Portfolio File

1. On the new repository page, you'll see "Quick setup" options
2. Click the link that says **"uploading an existing file"**
3. **Drag and drop** the `index.html` file (that's your portfolio!)
4. At the bottom, click **"Commit changes"**

**That's it!** Your file is now uploaded.

---

### Step 4: Make Your Site Live

1. In your repository, click the **"Settings"** tab (top menu)
2. On the left sidebar, click **"Pages"**
3. Under "Source":
   - Select **"main"** from the Branch dropdown
   - Keep "/ (root)" selected
   - Click **"Save"**
4. Wait 2-5 minutes

**Your website is now live!** 🎉

Visit: `https://your-username.github.io`

---

## How to Update Your Portfolio

### Method 1: Edit Directly on GitHub (Easiest)

1. Go to your repository
2. Click on `index.html`
3. Click the **pencil icon** (✏️) that says "Edit this file"
4. Make your changes
5. Scroll down and click **"Commit changes"**
6. Wait 1-2 minutes, then refresh your website to see updates

### Method 2: Upload New Version

1. Go to your repository
2. Click on the existing `index.html` file
3. Click the **trash icon** (🗑️) to delete it
4. Commit the deletion
5. Upload your new `index.html` file following Step 3 above

---

## Common Customizations (No Coding Required)

### 1. Change Your Contact Information

**Find and Replace** (use Ctrl+F or Cmd+F):

**Email:**
- Find: `iconetsenterprise@gmail.com`
- Replace with: `your-email@gmail.com`

**Phone:**
- Find: `+234 803 491 3133`
- Replace with: `your phone number`

**LinkedIn:**
- Find: `linkedin.com/in/christian-onyeoziri`
- Replace with: `linkedin.com/in/your-profile`

### 2. Update Your Name & Title

**Find and Replace:**
- Find: `Christian Onyeoziri`
- Replace with: `Your Full Name`

- Find: `Mechanical Engineer & Innovator`
- Replace with: `Your Professional Title`

### 3. Change Statistics

Find the stats section and update numbers:
```html
<div class="stat-number">7+</div>  <!-- Change to your years -->
<div class="stat-label">Years Experience</div>

<div class="stat-number">70%</div>  <!-- Change to your achievement -->
<div class="stat-label">Max Efficiency Gain</div>
```

### 4. Update Experience

Find each experience card and update:
- Job title
- Company name
- Dates
- Bullet points (the list items)

Just replace the text between the `>` and `<` symbols!

---

## Visual Customization Guide

### Want Different Colors?

Find this section near the top (around line 10-20):

```css
--accent: #FF6B35;         /* Main orange color */
--accent-secondary: #F7931E; /* Secondary color */
```

**Try these color codes instead:**

**Professional Blue:**
```css
--accent: #2E7CF6;
--accent-secondary: #00D4FF;
```

**Modern Green:**
```css
--accent: #00E396;
--accent-secondary: #00B8D4;
```

**Creative Purple:**
```css
--accent: #9D4EDD;
--accent-secondary: #E0AAFF;
```

**Tech Red:**
```css
--accent: #FF3E3E;
--accent-secondary: #FF6B6B;
```

Just copy-paste one of these to replace the orange colors!

---

## Troubleshooting

### "My website isn't showing up!"
**Solution:**
- Wait 5-10 minutes after enabling GitHub Pages
- Check the Settings → Pages section - there should be a green checkmark
- Make sure your repository is **Public**, not Private
- The file MUST be named `index.html` (all lowercase)

### "I see weird code instead of a website"
**Solution:**
- Your file might be named wrong. It should be `index.html` not `index.txt` or anything else
- Re-upload and make sure the extension is `.html`

### "Fonts look different than expected"
**Solution:**
- This is normal! The fonts load from the internet
- If you're offline, different fonts will show
- Once online, refresh the page

### "I broke something while editing"
**Solution:**
- Don't panic! Just re-upload the original `index.html` file
- Or contact me for help

---

## Getting Help

If you're stuck:

1. **Check the README.md** file for more detailed instructions
2. **Google the error message** - GitHub has great documentation
3. **Ask on GitHub Community** - https://github.community
4. **Watch YouTube tutorials** - Search "GitHub Pages setup tutorial"

---

## Next Steps After Setup

✅ **Share your portfolio!**
- Add the link to your LinkedIn profile
- Put it on your resume
- Share it with potential employers/clients

✅ **Keep it updated**
- Add new projects as you complete them
- Update your experience section
- Refresh your skills

✅ **Make it yours**
- Experiment with colors
- Add more sections
- Customize the content

---

## Pro Tips

💡 **Make it easy to find you:**
- Use the same username on GitHub, LinkedIn, and Twitter
- Add your GitHub link to your email signature
- Include it on business cards

💡 **Keep content concise:**
- Each project description: 2-3 sentences max
- Each job bullet point: 1 sentence
- Focus on achievements, not responsibilities

💡 **Update regularly:**
- Set a reminder to update every 3 months
- Add new projects immediately after completion
- Keep skills current

---

**You did it!** 🎉 You now have a professional engineering portfolio online!

Questions? Feel free to reach out!

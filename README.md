[README.md](https://github.com/user-attachments/files/24552729/README.md)
# Shoaib Malik - Personal Portfolio Website

A premium, modern, personal portfolio website built with pure HTML, CSS, and Vanilla JavaScript.

![Portfolio Preview](https://via.placeholder.com/800x400/0a0a0f/00ff88?text=Shoaib+Malik+Portfolio)

## Features

- Fully responsive design (desktop, tablet, mobile)
- Terminal/hacker-inspired aesthetic
- Smooth animations and transitions
- Typing text effect
- Animated counters
- Portfolio filter system
- Testimonials slider
- Contact form
- Scroll progress indicator
- Back-to-top button
- Mobile navigation menu

## Project Structure

portfolio/
├── index.html      # Main HTML file with all code
├── README.md       # This file
└── assets/         # (Optional) Add your images here
    ├── profile.jpg
    ├── projects/
    └── certifications/

```
## 🛠️ Customization

### Change Personal Information
Edit the following sections in `index.html`:

1. **Hero Section**: Update name, title, tagline
2. **About Section**: Update bio, contact info
3. **Skills**: Modify skill names and percentages
4. **Projects**: Add your own project images and descriptions
5. **Social Links**: Update your social media URLs

### Change Colors
Find the `:root` CSS variables at the top of the `<style>` section:

```css
:root {
    --bg-primary: #0a0a0f;
    --accent-primary: #00ff88;
    --accent-secondary: #00d4ff;
    /* ... more variables */
}


### Add Your Photo
Replace the placeholder image URL in the hero section:
```html
<img src="YOUR_IMAGE_URL_HERE" alt="Shoaib Malik" class="hero-image">


---

## 📤 Deployment to GitHub Pages

### Method 1: GitHub Web Interface (Easiest)

#### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click **Sign Up** and create an account
3. Verify your email address

#### Step 2: Create New Repository
1. Click the **+** icon in the top right corner
2. Select **New repository**
3. Repository name: `imshoaibmlk.github.io` (for main portfolio) or `portfolio`
4. Set to **Public**
5. ✅ Check "Add a README file" (optional)
6. Click **Create repository**

#### Step 3: Upload Files
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop your `index.html` file (and any other files)
3. Add commit message: "Initial portfolio upload"
4. Click **Commit changes**

#### Step 4: Enable GitHub Pages
1. Go to repository **Settings** (tab at the top)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select `main` and `/ (root)`
5. Click **Save**

#### Step 5: Access Your Website
- Wait 1-2 minutes for deployment
- Your site will be live at:
  - `https://imshoaibmlk.github.io` (if repo named `imshoaibmlk.github.io`)
  - `https://imshoaibmlk.github.io/portfolio` (if repo named `portfolio`)

---

### Method 2: Using Git Command Line

#### Prerequisites
- Install [Git](https://git-scm.com/downloads)
- Create a GitHub account

#### Step 1: Initialize Git Repository
Open terminal/command prompt in your project folder:

```bash
# Navigate to your project folder
cd path/to/your/portfolio

# Initialize git
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Portfolio website"


#### Step 2: Create GitHub Repository
1. Go to GitHub and create a new repository named `portfolio`
2. Don't initialize with README (since you already have files)

#### Step 3: Push to GitHub
```bash
# Add remote origin (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main


#### Step 4: Enable GitHub Pages
Same as Method 1, Step 4.

---

### Method 3: Using GitHub Desktop (GUI)

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Sign in with your GitHub account
3. **File** → **New Repository**
4. Add your files to the repository folder
5. Write a commit message and click **Commit to main**
6. Click **Publish repository**
7. Enable GitHub Pages in repository settings

---

## 🔧 Updating Your Website

### Via Web Interface
1. Go to your repository on GitHub
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make changes
5. Click **Commit changes**

### Via Command Line
```bash
# Make changes to your files locally

# Stage changes
git add .

# Commit
git commit -m "Updated portfolio content"

# Push to GitHub
git push


---

## 🌐 Custom Domain (Optional)

### Using a Custom Domain
1. Buy a domain from [Namecheap](https://namecheap.com), [GoDaddy](https://godaddy.com), etc.
2. In your repository, go to **Settings** → **Pages**
3. Under **Custom domain**, enter your domain (e.g., `shoaibmalik.com`)
4. Click **Save**

### Configure DNS
Add these records at your domain registrar:

**For apex domain (shoaibmalik.com):**

Type: A
Host: @
Value: 185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153


**For www subdomain:**

Type: CNAME
Host: www
Value: imshoaibmlk.github.io


### Add CNAME File
Create a file named `CNAME` (no extension) with your domain:

shoaibmalik.com


---

## 📱 Testing Responsiveness

Before deploying, test your site on different devices:
- **Chrome DevTools**: Press `F12` → Toggle device toolbar
- **Firefox**: Press `F12` → Responsive Design Mode
- Test on actual mobile devices if possible

---

## 🔒 Enable HTTPS

GitHub Pages provides free HTTPS:
1. Go to **Settings** → **Pages**
2. Check ✅ **Enforce HTTPS**

---

## 📊 Adding Analytics (Optional)

### Google Analytics
1. Go to [Google Analytics](https://analytics.google.com)
2. Create a property for your website
3. Copy the tracking code
4. Add it before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_ID');
</script>


---

## 🐛 Troubleshooting

### Site Not Loading?
- Wait 5-10 minutes after enabling GitHub Pages
- Check repository is **Public**
- Ensure `index.html` is in the root directory
- Clear browser cache

### 404 Error?
- Verify the branch name is correct in Pages settings
- Make sure `index.html` filename is lowercase

### CSS/JS Not Working?
- Check file paths are relative (not absolute)
- Ensure all files are uploaded

---

## 📞 Support

If you need help:
- 📧 Email: imshoaibmlk@gmail.com
- 🐙 GitHub: [@imshoaibmlk](https://github.com/imshoaibmlk)

---
```
## License

This project is open source and available under the [MIT License](LICENSE).

---

Made by Shoaib Malik

# 🔥 HAZMAT TACTICAL TOOL - Website Setup Guide

## 📁 What You Have

Your complete website is in the `hazmat-website` folder:

```
hazmat-website/
├── index.html              # Home page (landing page)
├── app.html               # The full training app
└── downloads/
    ├── Hazmat_Training_Schedule_2026.pdf
    └── Hazmat_Quick_Reference_Card.pdf
```

## ✅ FIXES COMPLETED

1. **Branding**: Changed back to "Hazmat Tactical Tool"
2. **PDF Downloads**: Fixed the file paths - downloads now work correctly!
3. **Website Structure**: Organized everything properly

## 🚀 How to Use

### Option 1: Test Locally (Quick Start)

1. Download the entire `hazmat-website` folder to your computer
2. Open `index.html` in your web browser
3. Click "LAUNCH APP" to test the app
4. Click the download buttons to test PDFs

**Everything should work perfectly!**

---

### Option 2: Host on GitHub Pages (FREE!)

This is what I recommend for Phase 1 - building your brand.

#### Step-by-Step:

1. **Create GitHub Account**
   - Go to github.com
   - Sign up (free)
   - Choose a professional username (like "hazmat-training")

2. **Create New Repository**
   - Click the "+" icon → "New repository"
   - Name it: `hazmat-training` (or whatever you want)
   - Make it PUBLIC
   - Click "Create repository"

3. **Upload Your Files**
   - Click "uploading an existing file"
   - Drag the entire `hazmat-website` folder
   - Commit the changes

4. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from branch
   - Branch: main → /root
   - Click Save

5. **Get Your Live URL**
   - Wait 2-3 minutes
   - Your site will be live at:
   - `https://yourusername.github.io/hazmat-training/index.html`

**Share that link with your team!**

---

### Option 3: Custom Domain (When You're Ready)

Once you're serious about building a business:

1. **Buy a domain** (~$12/year)
   - Examples: `hazmattraining.com`, `hazmat-tactical.com`
   - Use Namecheap, Google Domains, etc.

2. **Point it to GitHub Pages**
   - In your repository, create a file called `CNAME`
   - Put your domain name in it: `hazmattraining.com`
   - Update DNS settings at your domain registrar
   - Wait 24 hours for DNS propagation

3. **Professional Email**
   - Set up email forwarding: you@hazmattraining.com
   - Or use Google Workspace ($6/month for professional email)

---

## 🎯 Testing Checklist

Before sharing with anyone:

- [ ] Home page loads correctly
- [ ] "Launch App" button works
- [ ] App displays chemical search
- [ ] SCBA timer starts/stops/resets
- [ ] Both PDFs download successfully
- [ ] Site looks good on mobile (test on phone)
- [ ] All links work

---

## 🔧 Customization Tips

### Update Contact Email

In `index.html`, find and replace:
```html
mailto:contact@example.com
```
With your actual email:
```html
mailto:yourname@gmail.com
```

### Add Your Branding

You can add:
- Your name/organization in the footer
- Logo image (if you have one)
- Custom colors by editing the CSS variables

### Update for 2027

When 2026 ends:
- Create new training schedule PDF
- Upload to `downloads/` folder
- Update the year in descriptions

---

## 📱 Mobile Experience

The site is fully responsive and works great on:
- Desktop computers
- Tablets
- Smartphones (best in landscape for the app)

---

## 🎓 Phase 1 Goals

Now that you have this website:

1. **Share with your team** (get feedback)
2. **Test in training drills** (document success stories)
3. **Take screenshots** (for marketing)
4. **Collect testimonials** (from team members who use it)
5. **Network** (show to other departments)

---

## 💡 Marketing Your Website

### When talking to other departments:

**Elevator Pitch:**
"I built a free training platform with chemical database, SCBA timer, radiation calculators, and downloadable training resources. It's helped our team improve drill times and makes training more engaging. Want me to show you?"

**What to Show:**
1. The home page (professional look)
2. Live demo of chemical search
3. SCBA timer during mock drill
4. Downloadable training schedule
5. Offer to customize for their department

---

## 🚀 Next Steps

**Week 1-2: Test & Refine**
- Use it in your own training
- Get team feedback
- Fix any issues

**Week 3-4: Build Credibility**
- Document success stories
- Take professional screenshots
- Maybe record a demo video

**Month 2+: Start Marketing**
- Show to nearby departments
- Post on fire service forums
- Attend training conferences
- Offer customization services

---

## ⚠️ Legal Protection

Always include:
- "Training Tool Only - Not for Field Use"
- Disclaimers about consulting official sources
- Consider forming an LLC if charging money
- Get business liability insurance if profitable

---

## 🆘 Troubleshooting

**PDFs still not downloading?**
- Check file names match exactly (case-sensitive)
- Make sure downloads folder exists
- Try right-click → "Save As" instead

**App not working?**
- Check browser console for errors (F12)
- Try different browser (Chrome, Firefox, Safari)
- Clear cache and reload

**Want to add features?**
- The code is organized and commented
- Edit `app.html` to add functionality
- Test locally before uploading

---

## 📧 Support

This is your project - own it! But feel free to:
- Show it to your training officer
- Get department IT to help with hosting
- Reach out to me if you want more features

**You're ready to launch! 🚀**

Good luck building your brand and your business!

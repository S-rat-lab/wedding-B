# 🌐 How to Share Your Wedding Invitation Online

This guide will help you deploy your wedding invitation website and get a shareable link for your guests.

---

## 🚀 Option 1: GitHub Pages (Recommended - FREE)

GitHub Pages is perfect for wedding invitations - it's free, fast, and gives you a clean URL.

### Step-by-Step Instructions:

#### 1. Prepare Your Files
```bash
# Navigate to your folder
cd /home/Sharat/Documents/wedding_invite/_1

# Choose your favorite variation and copy it as index.html
# For example, if you like V4_1 (Scroll Frame):
cp index_v4_1_scroll_frame.html index.html

# Make sure you have these files:
# - index.html (your chosen variation)
# - final.jpg (your invitation image)
# - music.mp3 (background music)
```

#### 2. Initialize Git Repository (if not already done)
```bash
cd /home/Sharat/Documents/wedding_invite/_1
git init
git add .
git commit -m "Add wedding invitation website"
```

#### 3. Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create account)
2. Click the "+" icon (top right) → "New repository"
3. Repository name: `wedding-invitation` (or any name you prefer)
4. Make it **Public** (required for free GitHub Pages)
5. Do NOT initialize with README (you already have files)
6. Click "Create repository"

#### 4. Push Your Code to GitHub
```bash
# Replace 'YOUR-USERNAME' with your actual GitHub username
git remote add origin https://github.com/YOUR-USERNAME/wedding-invitation.git
git branch -M main
git push -u origin main
```

#### 5. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in left sidebar
4. Under "Source", select branch: **main**
5. Select folder: **/ (root)**
6. Click "Save"
7. Wait 1-2 minutes for deployment

#### 6. Get Your Shareable Link
Your website will be live at:
```
https://YOUR-USERNAME.github.io/wedding-invitation/
```

**That's your shareable link!** 🎉

### Example:
If your GitHub username is `sharatprabhakaran`, your link would be:
```
https://sharatprabhakaran.github.io/wedding-invitation/
```

---

## 🚀 Option 2: Netlify (Even Easier - FREE)

Netlify offers drag-and-drop deployment with a custom URL.

### Step-by-Step Instructions:

#### 1. Prepare Your Files
Create a folder with these files:
- `index.html` (your chosen variation renamed)
- `final.jpg`
- `music.mp3`

#### 2. Deploy to Netlify
1. Go to [netlify.com](https://netlify.com)
2. Sign up for free (use GitHub, Google, or email)
3. Click "Add new site" → "Deploy manually"
4. Drag and drop your folder onto the page
5. Wait 30 seconds - Done!

#### 3. Get Your Link
Netlify gives you a URL like:
```
https://random-name-12345.netlify.app
```

#### 4. (Optional) Customize Your URL
1. Click "Site settings" → "Change site name"
2. Choose a custom name like: `sharat-sreekutty-wedding`
3. Your new URL:
```
https://sharat-sreekutty-wedding.netlify.app
```

---

## 🚀 Option 3: Vercel (Also Great - FREE)

Similar to Netlify, very fast deployment.

### Step-by-Step Instructions:

1. Go to [vercel.com](https://vercel.com)
2. Sign up (use GitHub, GitLab, or Bitbucket)
3. Click "Add New" → "Project"
4. Import your GitHub repository (from Option 1)
5. Click "Deploy"
6. Get your link: `https://your-project.vercel.app`

---

## 🚀 Option 4: Google Drive (Quick & Simple)

Not a proper website, but works for basic sharing.

### Instructions:
1. Upload your HTML file to Google Drive
2. Right-click → "Get link" → "Anyone with the link"
3. Share the link

**⚠️ Note**: This won't look as professional and may not work perfectly in all browsers.

---

## 📱 Short URL (For Any Option Above)

Once you have your link, make it shorter for easy sharing:

### Using Bitly:
1. Go to [bitly.com](https://bitly.com)
2. Paste your full URL
3. Get a short link like: `bit.ly/SharatWedding`

### Using TinyURL:
1. Go to [tinyurl.com](https://tinyurl.com)
2. Paste your full URL
3. Customize: `tinyurl.com/sharat-wedding-2026`

---

## 🎯 Recommended Approach

**For best results:**

1. **Use GitHub Pages or Netlify** (both are free and professional)
2. **Choose a memorable custom name**:
   - `sharat-sreekutty-wedding`
   - `wedding-jan2026`
   - `prabhakaran-sreekandan-wedding`

3. **Create a short URL** for WhatsApp/SMS:
   ```
   bit.ly/SharatWedding
   ```

4. **Test the link** on your phone before sharing

---

## 📲 How to Share with Guests

### WhatsApp Message Template:
```
🪔 Jai Guru Dev 🪔

Dear [Name],

We joyfully invite you to our wedding!

📱 View your invitation:
https://bit.ly/SharatWedding

💐 Sharat & Sreekutty
📅 25th January 2026
📍 Crystal Convention Centre, Nagaroor

Looking forward to your precious presence!
```

### SMS Template:
```
🪔 Wedding Invitation
Sharat & Sreekutty
25th Jan 2026

View invitation:
bit.ly/SharatWedding

- Meena & Bharat Prabhakaran
```

---

## 🔧 Troubleshooting

### Music Not Playing?
- Most browsers block autoplay music for security
- Guests must click/tap to start music
- This is normal and expected

### Image Not Loading?
- Make sure `final.jpg` is in the same folder
- Check file name matches exactly (case-sensitive)

### Site Not Loading?
- Wait 2-5 minutes after deployment
- Clear browser cache (Ctrl+Shift+Delete)
- Try incognito/private mode

---

## 💡 Pro Tips

1. **Test on multiple devices** before sharing widely
   - iPhone (Safari)
   - Android (Chrome)
   - Desktop (Chrome, Firefox)

2. **Keep the URL short** - easier to share in printed cards

3. **QR Code option**: Generate a QR code for your URL
   - Go to [qr-code-generator.com](https://www.qr-code-generator.com)
   - Enter your URL
   - Print QR code on physical invitations
   - Guests can scan to open invitation

4. **Analytics** (optional): Both Netlify and Vercel show visitor stats

---

## 🎊 Final Checklist Before Sharing

- [ ] Chosen your favorite variation
- [ ] Renamed it to `index.html`
- [ ] Verified `final.jpg` loads correctly
- [ ] Verified `music.mp3` is included
- [ ] Deployed to GitHub Pages/Netlify/Vercel
- [ ] Got your shareable link
- [ ] Created a short URL (optional)
- [ ] Tested on mobile phone
- [ ] Tested on desktop
- [ ] Prepared WhatsApp/SMS message
- [ ] Ready to share! 🎉

---

## 📞 Need Help?

If you get stuck at any step, you can:
1. Check GitHub Pages documentation
2. Check Netlify/Vercel tutorials on YouTube
3. Ask me for help with specific error messages

---

**Remember**: GitHub Pages, Netlify, and Vercel are all **100% FREE** for hosting wedding invitation websites!

Choose the one that seems easiest to you and follow the steps above. 💐

**Good luck with your wedding preparations!** 🎊

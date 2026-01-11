# 🐙 GitHub Pages Deployment - Step by Step

Follow these steps to deploy your wedding invitation using GitHub Pages.

---

## ✅ Pre-Deployment Checklist

✅ index.html is ready (V4_1 Scroll Frame)
✅ final.jpg is included
✅ music.mp3 is included
✅ All files are committed to git
✅ Ready to deploy!

---

## 📋 Step-by-Step Instructions

### Step 1: Create GitHub Account (if needed)

If you don't have a GitHub account:
1. Go to: **https://github.com/signup**
2. Enter your email, create password, choose username
3. Verify your email
4. Done!

---

### Step 2: Create New Repository

1. **Go to**: https://github.com/new

2. **Fill in details**:
   - Repository name: `wedding-invitation`
   - Description: (optional) "Sharat & Sreekutty Wedding Invitation"
   - **Make it PUBLIC** ⚠️ (required for free GitHub Pages)
   - **DO NOT check** "Add a README file"
   - **DO NOT choose** a .gitignore or license
   - Leave everything else as default

3. **Click**: "Create repository"

4. **Copy the repository URL** - it will look like:
   ```
   https://github.com/YOUR-USERNAME/wedding-invitation.git
   ```

---

### Step 3: Connect Your Local Repository to GitHub

Open terminal and run these commands:

```bash
# Navigate to your project
cd /home/Sharat/Documents/wedding_invite/_1

# Add GitHub as remote (replace YOUR-USERNAME with your actual GitHub username)
git remote add origin https://github.com/YOUR-USERNAME/wedding-invitation.git

# Verify remote was added
git remote -v
```

You should see:
```
origin  https://github.com/YOUR-USERNAME/wedding-invitation.git (fetch)
origin  https://github.com/YOUR-USERNAME/wedding-invitation.git (push)
```

---

### Step 4: Push Your Code to GitHub

```bash
# Push your code to GitHub
git push -u origin main
```

**You'll be prompted for credentials:**

#### Option A: Username and Personal Access Token (Recommended)
- **Username**: Your GitHub username
- **Password**: You need a Personal Access Token (NOT your GitHub password)

**To create a Personal Access Token:**
1. Go to: https://github.com/settings/tokens/new
2. Note: "Wedding Invitation Deploy"
3. Expiration: Choose "90 days" or "No expiration"
4. Check **ONLY** this permission: ☑️ **repo** (Full control of private repositories)
5. Scroll down, click "Generate token"
6. **COPY THE TOKEN** (you won't see it again!)
7. Paste it as the password when git asks

#### Option B: GitHub CLI (if you have it)
```bash
gh auth login
```

---

### Step 5: Verify Code is on GitHub

1. Go to: `https://github.com/YOUR-USERNAME/wedding-invitation`
2. You should see your files:
   - index.html
   - final.jpg
   - music.mp3
   - README.md
   - All other files

---

### Step 6: Enable GitHub Pages

1. **Go to your repository**: `https://github.com/YOUR-USERNAME/wedding-invitation`

2. **Click** the "Settings" tab (top right, gear icon)

3. **Click** "Pages" in the left sidebar (under "Code and automation")

4. **Under "Build and deployment"**:
   - Source: Select "Deploy from a branch"
   - Branch: Select "main" (not "None")
   - Folder: Select "/ (root)"

5. **Click "Save"**

6. **Wait 1-2 minutes** for deployment

---

### Step 7: Get Your Live URL! 🎉

1. Refresh the GitHub Pages settings page

2. At the top, you'll see a success message:
   ```
   Your site is live at https://YOUR-USERNAME.github.io/wedding-invitation/
   ```

3. **Click the link** to test your invitation!

4. **This is your shareable URL!** 🎊

---

## 🔗 Create a Short Link

Your GitHub Pages URL might be long. Create a short version:

### Using Bitly:
1. Go to: https://bitly.com (sign up free)
2. Click "Create" → "Link"
3. Paste: `https://YOUR-USERNAME.github.io/wedding-invitation/`
4. Customize to: `bit.ly/SharatWedding`
5. Click "Create"

### Using TinyURL:
1. Go to: https://tinyurl.com
2. Paste your GitHub Pages URL
3. Custom alias: `sharat-sreekutty-2026`
4. Get: `tinyurl.com/sharat-sreekutty-2026`

---

## 📱 Share with Guests

Now you can share your link!

### WhatsApp Message:
```
🪔 Jai Guru Dev 🪔

Dear [Name],

We are delighted to invite you to the wedding of:

💐 Sharat Prabhakaran & Sreekutty Sreekandan

📅 Saturday, 25th January 2026
⏰ Muhurtham: 12:11 PM - 12:31 PM
📍 Crystal Convention Centre, Nagaroor

📱 View your invitation:
[YOUR SHORT LINK]

Looking forward to your precious presence and blessings!

🙏 Meena Prabhakaran & Bharat Prabhakaran
```

### SMS:
```
🪔 Wedding Invitation

Sharat & Sreekutty
25 Jan 2026, 12:11 PM
Crystal Convention Centre

View: [SHORT LINK]

- Prabhakaran Family
```

---

## 🔄 Making Updates Later

If you need to make changes to your invitation:

```bash
# Make your edits to files
# Then:
cd /home/Sharat/Documents/wedding_invite/_1

git add .
git commit -m "Update invitation"
git push

# Wait 1-2 minutes, changes will be live!
```

---

## 🆘 Troubleshooting

### Error: "remote origin already exists"
```bash
# Remove the old remote
git remote remove origin

# Add the new one
git remote add origin https://github.com/YOUR-USERNAME/wedding-invitation.git
```

### Error: "Permission denied" when pushing
- Make sure you're using a Personal Access Token, not your password
- Token must have "repo" permission checked
- Create new token at: https://github.com/settings/tokens/new

### Error: "Repository not found"
- Check you spelled the repository name correctly
- Make sure the repository is created on GitHub
- Verify your username is correct

### Page shows README instead of invitation
- Make sure you have `index.html` in the root folder
- Check GitHub Pages settings: should deploy from "main" branch, "/ (root)" folder
- Wait 2-3 minutes for changes to take effect

### 404 Error when visiting the page
- Wait 2-5 minutes after enabling GitHub Pages
- Check the URL is correct: `https://YOUR-USERNAME.github.io/wedding-invitation/`
- Make sure repository is PUBLIC

### Images or music not loading
- Check files are committed: `git status`
- Check filenames match exactly: `final.jpg` and `music.mp3` (case-sensitive)
- Look at browser console (F12) for errors

---

## 📊 View Visitor Stats (Optional)

GitHub doesn't provide built-in analytics, but you can:

1. **GitHub Insights**: See how many people visited
   - Go to your repository
   - Click "Insights" tab
   - Click "Traffic" (shows visitors in last 14 days)

2. **Google Analytics**: For detailed stats
   - Sign up at: https://analytics.google.com
   - Add tracking code to index.html
   - See real-time visitors, locations, devices

---

## ✨ What Guests Will See

When guests click your link:
1. 🪔 Beautiful glowing lamp with "Tap to Unfurl"
2. 📜 Elegant rolled scroll with wooden rods
3. ✨ Golden borders with beautiful glow effect
4. [CLICK] Smooth 2.5-second unfurl animation
5. 🎵 Background music starts playing
6. ⭐ Golden sparkles cascade down
7. 💌 Your crystal-clear invitation image reveals
8. 📱 Perfect display on any device (mobile/tablet/desktop)

---

## 🎯 Quick Command Reference

```bash
# Check status
git status

# See recent commits
git log --oneline -5

# Check remote
git remote -v

# Add all files
git add .

# Commit changes
git commit -m "Your message here"

# Push to GitHub
git push

# View files
ls -lh index.html final.jpg music.mp3
```

---

## 🎊 Success Checklist

Once deployed, verify:
- [ ] Can open the GitHub Pages URL
- [ ] "Tap to Unfurl" text appears
- [ ] Clicking unfurls the scroll smoothly
- [ ] Invitation image loads crystal clear
- [ ] Music plays (after clicking)
- [ ] Golden sparkles appear
- [ ] Works on mobile phone
- [ ] Works on desktop browser
- [ ] Short link created (optional)
- [ ] Ready to share with guests! 🎉

---

## 💡 Pro Tips

1. **Test on multiple devices** before mass sharing
   - Your phone (Android/iPhone)
   - Friend's phone
   - Desktop browser (Chrome, Firefox, Safari)
   - Tablet (if available)

2. **Send test invite to yourself** first via WhatsApp/SMS

3. **QR Code for printed cards**:
   - Go to: https://www.qr-code-generator.com
   - Enter your GitHub Pages URL
   - Download high-res PNG
   - Add to printed invitation cards
   - Guests can scan to view online version!

4. **Custom Domain** (optional, advanced):
   - Buy domain like: `sharatwedding.com` (~$10/year)
   - Point it to GitHub Pages
   - Guide: https://docs.github.com/pages/custom-domain

---

**Ready to deploy? Start with Step 1 above!** 🚀

Your invitation is beautiful and ready to share with the world! 💐

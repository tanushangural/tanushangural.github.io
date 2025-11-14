# 🚀 Deploy Your Portfolio to GitHub Pages - Step by Step

## ✅ Your code is ready! Now follow these steps:

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon (top right) → **"New repository"**
3. **Repository name**: Choose one of these options:
   - **Option A (Recommended)**: `tanushangural.github.io` 
     - This creates your personal site at: `https://tanushangural.github.io`
   - **Option B**: Any name like `portfolio` 
     - This creates: `https://tanushangural.github.io/portfolio`
4. Make sure it's **Public** (required for free GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click **"Create repository"**

### Step 2: Push Your Code to GitHub

Copy the commands GitHub shows you, OR use these (replace with your repo URL):

```bash
# Set your GitHub username and email (if not already set)
git config --global user.name "tanushangural"
git config --global user.email "tanusharya7@gmail.com"

# Add GitHub repository as remote
git remote add origin https://github.com/tanushangural/tanushangural.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**If you get prompted for credentials:**
- Username: `tanushangural`
- Password: Use a **Personal Access Token** (not your GitHub password)
  - Go to: GitHub → Settings → Developer settings → Personal access tokens → Generate new token
  - Select "repo" scope → Generate → Copy the token

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top menu)
3. Click **"Pages"** (left sidebar)
4. Under **"Source"**, select:
   - Branch: **main**
   - Folder: **/ (root)**
5. Click **"Save"**

### Step 4: Wait & Visit Your Site! 🎉

- GitHub will build your site (takes 1-3 minutes)
- Your portfolio will be live at:
  - `https://tanushangural.github.io` (if using Option A)
  - `https://tanushangural.github.io/portfolio` (if using Option B)

---

## 🔄 To Update Your Portfolio Later

When you make changes:

```bash
git add .
git commit -m "Updated portfolio"
git push
```

Changes will be live in 1-2 minutes!

---

## ❓ Troubleshooting

**Problem: "Repository not found"**
- Make sure you created the repository on GitHub first
- Check the repository URL in the command

**Problem: "Authentication failed"**
- Use a Personal Access Token instead of password
- Or use SSH keys

**Problem: "Site not loading"**
- Wait 5-10 minutes after first deployment
- Check GitHub Pages settings are enabled
- Make sure repository is Public

**Problem: "Images not loading"**
- All files (profile.jpg, etc.) are in the root directory ✅
- Paths in HTML are relative ✅

---

## 📋 Quick Checklist

- [ ] Git repository initialized ✅ (Done)
- [ ] Files committed ✅ (Done)
- [ ] GitHub account ready
- [ ] Repository created on GitHub
- [ ] Code pushed to GitHub
- [ ] GitHub Pages enabled
- [ ] Portfolio is live! 🚀

---

## 🎯 Next Steps After Deployment

1. **Share your URL** on LinkedIn, resume, email signature
2. **Test all links** (email, phone, GitHub, LeetCode)
3. **Test on mobile** to ensure responsiveness
4. **Share with recruiters** and include in job applications
5. **Update resume** to include portfolio URL

---

## 💡 Pro Tips

- Your Google Drive resume link will always stay updated
- Profile picture is optimized and ready
- All social links are configured
- Color scheme optimized for recruiter engagement
- Mobile responsive and fast loading

**Your portfolio is ready to impress recruiters! 🌟**

Need help with any step? Just ask!

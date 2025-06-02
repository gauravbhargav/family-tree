# 🌳 Family Tree - GitHub Pages Setup Guide

## 📁 Files You Need

1. **`index.html`** - The main family tree application
2. **`family-data.json`** - The family data (separate from app code)

## 🚀 GitHub Pages Setup

### Step 1: Create Repository
1. Go to [GitHub.com](https://github.com) and sign up (free)
2. Click "+" → "New repository"
3. Name: `family-tree` (or your preferred name)
4. Make it **Public**
5. Check "Add a README file"
6. Click "Create repository"

### Step 2: Upload Files
1. Click "uploading an existing file"
2. Drag both files: `index.html` and `family-data.json`
3. **Important:** Make sure the HTML file is named exactly `index.html`
4. Add commit message: "Initial family tree upload"
5. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository **Settings** tab
2. Scroll down to **"Pages"** section
3. Under "Source": Select "Deploy from a branch"
4. Branch: Select "main" 
5. Folder: Select "/ (root)"
6. Click **"Save"**

### Step 4: Access Your Family Tree
- Your app will be available at: `https://yourusername.github.io/family-tree`
- Takes 5-10 minutes to activate initially
- Share this URL with family members!

## ✏️ Updating Family Data

### Method 1: Direct GitHub Editing (Quick)
1. Go to your repository on GitHub.com
2. Click on `family-data.json`
3. Click the "Edit" button (pencil icon)
4. Make your changes in JSON format
5. Click "Commit changes"
6. Changes appear on your website immediately!

### Method 2: App Interface (Complex Changes)
1. Open your family tree app
2. Click "🔐 Admin Panel" → Login with password
3. Make changes using the interface
4. Click "💾 Save Updated Data"
5. Click "📧 Send to Admin" 
6. Copy JSON from email and update GitHub file

## 🔐 Admin Setup

**Before sharing, update the admin email:**
1. Edit `index.html` 
2. Find line: `const adminEmail = 'xxxx@yyyy.com';`
3. Replace with your actual email address
4. Commit changes to GitHub

**Default admin password:** `admin123`
- To change: Find `atob('YWRtaW4xMjM=')` and replace with new base64 encoded password

## 👥 Sharing with Family

**Share this URL:** `https://yourusername.github.io/family-tree`

**User Instructions:**
- Anyone can view the family tree
- To suggest changes: Click "🔐 Admin Panel" → "📧 Request Edit Access"
- Fill out forms and submit - admin gets email with changes
- Admin reviews and updates the data

## 📧 User Workflow for Changes

1. **View**: Anyone can browse the family tree
2. **Suggest**: Users click "Add Person" or "Edit" 
3. **Submit**: Choose "📧 Request Update" option
4. **Email**: Admin receives detailed change request
5. **Review**: Admin approves and updates JSON file
6. **Live**: Changes appear immediately on website

## 🔄 Benefits of This Approach

- ✅ **Professional hosting** on GitHub Pages
- ✅ **Version control** - see all changes over time
- ✅ **Multiple admins** - give GitHub access to family members  
- ✅ **Mobile editing** - update data from your phone
- ✅ **Always online** - no file downloads needed
- ✅ **Free forever** - GitHub Pages is completely free
- ✅ **Easy updates** - edit JSON directly or use app interface

## 🆘 Troubleshooting

**Website shows source code instead of app:**
- Make sure file is named `index.html` (not `family-tree.html`)
- Wait 10 minutes after enabling Pages
- Check Pages is enabled in repository Settings

**Data not loading:**
- Ensure `family-data.json` is in the same repository
- Check JSON syntax is valid
- Look at browser console for error messages

**Need help?**
- Create an "Issue" in your GitHub repository
- GitHub community is very helpful for beginners!

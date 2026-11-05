# 📱 Complete Guide: Build APK on GitHub (Mobile-Friendly)

**A step-by-step guide to build your Android APK using GitHub Actions — works entirely from your mobile phone!**

---

## 📖 Table of Contents

1. [What is GitHub Actions?](#what-is-github-actions)
2. [What You Need](#what-you-need)
3. [Step 1: Create GitHub Account](#step-1-create-github-account)
4. [Step 2: Create Repository](#step-2-create-repository)
5. [Step 3: Download Project Code](#step-3-download-project-code)
6. [Step 4: Upload Code to GitHub](#step-4-upload-code-to-github)
7. [Step 5: Start the Build](#step-5-start-the-build)
8. [Step 6: Wait for Build](#step-6-wait-for-build)
9. [Step 7: Download Your APK](#step-7-download-your-apk)
10. [Step 8: Install the APK](#step-8-install-the-apk)
11. [Troubleshooting](#troubleshooting)
12. [FAQ](#faq)

---

## 🤔 What is GitHub Actions?

**GitHub Actions** is a free service that builds software for you in the cloud.

### How It Works:

```
YOUR PHONE                GITHUB CLOUD              YOUR PHONE
    |                          |                         |
    |-- 1. Upload code ------->|                         |
    |                          |-- 2. Build APK (5 min)  |
    |                          |-- 3. Save APK           |
    |<-- 4. Download APK --------------------------------|
    |                          |                         |
    |--- 5. Install & Use -----|                         |
```

**Think of it like:**
- You send ingredients (code) to a cloud kitchen (GitHub)
- They cook it (build APK) using professional tools
- They send back the finished dish (APK file)
- You enjoy it (install and use the app)

**Cost:** FREE for public repositories  
**Time:** 15-20 minutes total  
**Difficulty:** Easy (follow steps exactly)

---

## ✅ What You Need

### Required:
- ✅ A mobile phone (Android or iPhone)
- ✅ Internet connection
- ✅ Email address (for GitHub account)
- ✅ 100MB free storage space (for APK)
- ✅ 15-20 minutes of time

### Apps to Install:
1. **GitHub** (optional, can use browser)
   - Play Store: Search "GitHub"
   - Or use: github.com in Chrome/browser

2. **Files by Google** (for managing downloads)
   - Already on most Android phones
   - Or install from Play Store

3. **Chrome** or any browser
   - Already on your phone

---

## Step 1: Create GitHub Account

### What is GitHub?
GitHub is a website where developers store and share code. It's like Google Drive for programmers, but with extra features like automatic building.

### Instructions:

**1.1 Open GitHub**
- Open Chrome browser
- Go to: **github.com**

**1.2 Start Signup**
- Tap **"Sign up"** button (top right)
- OR tap **"Sign up for GitHub"** (center of page)

**1.3 Enter Email**
- Type your email address
- Example: `yourname@gmail.com`
- Tap **"Continue"**

**1.4 Create Password**
- Password must be:
  - At least 8 characters
  - Include numbers or special characters
- Example: `StepTracker2024!`
- Tap **"Continue"**

**1.5 Choose Username**
- This will be your GitHub profile name
- Use letters, numbers, and hyphens only
- Example: `steptracker-user` or `yourname123`
- Tap **"Continue"**

**1.6 Email Preferences**
- Choose: **"Receive occasional product updates"** (or not)
- Type **"y"** for yes or **"n"** for no
- Tap **"Continue"**

**1.7 Solve Puzzle (Verify You're Human)**
- You'll see a puzzle or image selection
- Follow the instructions (usually select images with specific objects)
- Tap **"Continue"**

**1.8 Check Your Email**
- GitHub sent a verification code to your email
- Open your email app (Gmail, etc.)
- Find email from GitHub
- Copy the 6-digit code
- Go back to GitHub and enter the code
- Tap **"Continue"**

**1.9 Complete Setup**
- Answer a few questions (you can skip most)
- Tap **"Submit"** or **"Skip"** as needed

✅ **Congratulations! Your GitHub account is created!**

You should now see your GitHub dashboard.

---

## Step 2: Create Repository

### What is a Repository?
A repository (or "repo") is like a folder where your project code lives. Think of it as a project box that holds all your files.

### Instructions:

**2.1 Start New Repository**
- On GitHub website, tap the **"+"** icon (top right, next to your profile picture)
- Tap **"New repository"**

**OR**

- Go directly to: **github.com/new**

**2.2 Fill in Repository Details**

**Repository name:**
```
StepTracker
```
- Must be exactly this (or any name you prefer)
- No spaces allowed

**Description (optional):**
```
Android step tracking app with activity detection
```
- This is just a short description
- You can skip this if you want

**Public or Private:**
- Select: **Public** ⚠️ IMPORTANT!
- Why? GitHub Actions is free only for public repositories
- Private repositories require paid plan

**Initialize this repository with:**
- ✅ Check: **"Add a README file"**
- This creates a basic file so the repository isn't empty

**Other options:**
- Leave "Add .gitignore" as **"None"**
- Leave "Choose a license" as **"None"**

**2.3 Create Repository**
- Scroll down
- Tap the green **"Create repository"** button
- Wait 2-3 seconds

✅ **Your repository is ready!**

You should now see your new repository page with:
- Repository name at top
- README.md file in the file list
- Tabs: Code, Issues, Pull requests, Actions, etc.

---

## Step 3: Download Project Code

### What You Need to Download:
The complete StepTracker project folder with all 61 files.

### Instructions:

**3.1 Go to This Workspace**
- You're already here in this conversation
- Scroll up to see the StepTracker project

**3.2 Download the Project**

**Option A: Download as ZIP (Easiest)**
- Look for a **"Download"** button in this workspace
- Tap it
- Choose **"Download as ZIP"**
- Wait for download to complete
- File will be saved to your **Downloads** folder
- Name: `StepTracker.zip` or similar

**Option B: If No Download Button**
- You'll need to copy files manually (tedious but works)
- Skip to Section 4 and I'll show you an alternative method

**3.3 Extract the ZIP File**
- Open **"Files"** app (or "Files by Google")
- Go to **"Downloads"** folder
- Find the downloaded ZIP file
- Tap on it
- Tap **"Extract"** or **"Unzip"**
- Choose where to extract (Downloads folder is fine)
- Wait for extraction to complete
- You should now see a folder called **"StepTracker"** with all the project files

✅ **Code is ready to upload!**

---

## Step 4: Upload Code to GitHub

### Instructions:

**4.1 Go to Your Repository**
- Open GitHub website
- Go to your StepTracker repository
- URL: `github.com/YOUR-USERNAME/StepTracker`

**4.2 Start Upload**
- Tap **"Add file"** button (above the file list)
- Tap **"Upload files"**

**4.3 Select Files to Upload**

**Method 1: Upload ZIP (if GitHub allows)**
- Tap **"choose your files"**
- Navigate to Downloads folder
- Select the extracted **StepTracker** folder
- Select all files inside it
- Tap **"Open"** or **"Select"**

**Method 2: Upload Individual Files**
If folder upload doesn't work:
- You'll need to upload files one by one or in batches
- Start with these important files first:
  1. `.github/workflows/build-apk.yml` (most important!)
  2. `build.gradle.kts`
  3. `settings.gradle.kts`
  4. `app/build.gradle.kts`
  5. Then upload all other files

**4.4 Create Folder Structure**
GitHub needs the exact folder structure. When uploading:

- For files in subfolders, you need to create the folders first:
  1. Tap **"Add file"** → **"Create new file"**
  2. Type folder path: `.github/workflows/`
  3. Name the file: `build-apk.yml`
  4. Paste the workflow content (from the file in this workspace)
  5. Tap **"Commit new file"**

- Repeat for other folders:
  - `app/src/main/`
  - `app/src/main/java/com/steptracker/app/`
  - etc.

**⚠️ IMPORTANT:** Make sure this file is uploaded correctly:
```
.github/workflows/build-apk.yml
```
This file tells GitHub how to build your APK!

**4.5 Commit the Upload**
- After selecting all files, scroll down
- You'll see **"Commit changes"** section
- Leave the default message: "Add files via upload"
- Tap **"Commit changes"** (green button)
- Wait for upload to complete (1-3 minutes depending on internet speed)

✅ **Code uploaded successfully!**

You should now see all your project files in the repository.

---

## Step 5: Start the Build

### What Happens Now:
When you upload code, GitHub Actions automatically starts building your APK. But let's make sure it's running.

### Instructions:

**5.1 Check if Build Started Automatically**
- Look at the top of your repository page
- You should see a small icon next to your latest commit:
  - 🟡 Yellow circle = Build in progress
  - ✅ Green checkmark = Build completed successfully
  - ❌ Red X = Build failed

**5.2 Go to Actions Tab**
- Tap the **"Actions"** tab (in the menu bar)
- You should see a workflow run in progress or completed

**5.3 If No Build Started, Trigger Manually**
- In Actions tab, tap **"Build APK"** (left sidebar)
- Tap **"Run workflow"** button (right side)
- A dropdown appears
- Leave "Branch: main" as is
- Tap green **"Run workflow"** button
- Build will start in a few seconds

✅ **Build is now running!**

---

## Step 6: Wait for Build

### What's Happening:
GitHub is now:
1. Setting up a virtual computer in the cloud
2. Installing Android SDK and build tools
3. Downloading your code
4. Compiling all the Kotlin files
5. Building the APK
6. Saving the APK for you to download

### Instructions:

**6.1 Monitor Progress**
- Stay on the **"Actions"** tab
- You'll see a workflow run with status:
  - **"In progress"** (yellow) = Still building
  - **"Success"** (green) = Done!
  - **"Failure"** (red) = Error occurred

**6.2 Wait Time**
- First build: **5-10 minutes**
- Subsequent builds: **3-5 minutes**
- Be patient! Don't close the browser

**6.3 Check Build Details (Optional)**
- Tap on the workflow run name
- You'll see individual steps:
  - ✅ Checkout code
  - ✅ Set up JDK 17
  - ✅ Grant execute permission
  - 🔄 Build Debug APK (this takes longest)
  - ⏳ Upload APK

**6.4 If Build Fails**
- Don't panic! Common reasons:
  - Missing files (check upload was complete)
  - Syntax error in code (rare)
  - GitHub temporary issue (try again)
- Tap on the failed step to see error details
- Try running workflow again

✅ **Build completed successfully!**

When you see a green checkmark, your APK is ready!

---

## Step 7: Download Your APK

### Instructions:

**7.1 Open Completed Build**
- In Actions tab, tap on the completed workflow run
- It should have a green checkmark ✅

**7.2 Find Artifacts Section**
- Scroll down to the bottom of the page
- Look for **"Artifacts"** section
- You should see: **"StepTracker-APK"**

**7.3 Download APK**
- Tap on **"StepTracker-APK"**
- Download will start automatically
- File name: `StepTracker-APK.zip`
- Size: ~15-20 MB
- Wait for download to complete

**7.4 Locate Downloaded File**
- Open **"Files"** app
- Go to **"Downloads"** folder
- Find `StepTracker-APK.zip`

✅ **APK downloaded!**

---

## Step 8: Install the APK

### Instructions:

**8.1 Extract the ZIP**
- In Files app, tap on `StepTracker-APK.zip`
- Tap **"Extract"** or **"Unzip"**
- Choose location (Downloads folder is fine)
- Wait for extraction
- You'll see a file called `app-debug.apk`

**8.2 Install the APK**
- Tap on `app-debug.apk`
- You'll see a security warning:
  
  **"Install unknown apps"** or **"Allow from this source"**
  
- Tap **"Settings"** or **"Allow"**
- Enable permission for your file manager or browser
- Go back and tap the APK again
- Tap **"Install"**

**8.3 Wait for Installation**
- Installation takes 5-10 seconds
- You'll see: **"App installed"**
- Tap **"Open"** to launch the app

**8.4 First Launch**
- App will open
- You'll see the onboarding screen
- Follow the prompts to grant permissions
- Start tracking your steps!

✅ **Congratulations! Your app is installed and running!**

---

## 🆘 Troubleshooting

### Problem: "Install from unknown sources" blocked

**Solution:**
1. Go to phone **Settings**
2. Tap **"Apps & notifications"** (or "Apps")
3. Tap **"Special app access"**
4. Tap **"Install unknown apps"**
5. Find your browser or file manager (Chrome, Files, etc.)
6. Enable **"Allow from this source"**
7. Try installing APK again

---

### Problem: APK won't install - "App not installed"

**Solutions:**
1. **Uninstall existing app** (if you have an old version)
   - Settings → Apps → StepTracker → Uninstall

2. **Check storage space**
   - Need at least 50MB free
   - Delete some photos/videos if needed

3. **Restart phone**
   - Hold power button
   - Tap "Restart"
   - Try installing again

4. **Check Android version**
   - App requires Android 8.0 or higher
   - Check: Settings → About phone → Android version

---

### Problem: Build failed on GitHub

**Common Errors and Solutions:**

**Error 1: "No workflow files found"**
- **Cause:** `.github/workflows/build-apk.yml` file is missing
- **Solution:** Re-upload the file, make sure it's in the correct folder

**Error 2: "Build failed with exit code 1"**
- **Cause:** Code compilation error
- **Solution:** Check that all files were uploaded correctly, especially:
  - `build.gradle.kts`
  - `app/build.gradle.kts`
  - All `.kt` files in `app/src/main/java/`

**Error 3: "Gradle build failed"**
- **Cause:** Missing dependencies or syntax error
- **Solution:** 
  - Try running workflow again (sometimes temporary)
  - Check that `gradle-wrapper.properties` exists
  - Verify all Gradle files are complete

**Error 4: "Out of memory"**
- **Cause:** Build needs more RAM
- **Solution:** This is rare, but try again later

**How to Check Error Details:**
1. Go to Actions tab
2. Tap on the failed workflow run
3. Tap on the failed step (red X)
4. Read the error log
5. Copy error message and search online

---

### Problem: Can't find downloaded APK

**Solution:**
1. Open **Files by Google** app
2. Tap **"Downloads"** category
3. Look for `StepTracker-APK.zip` or `app-debug.apk`
4. Or use search: type "apk" or "StepTracker"
5. Check notification panel for download notification

---

### Problem: GitHub account creation fails

**Solutions:**
1. Use a different email address
2. Try different browser (Chrome, Firefox, Edge)
3. Clear browser cache and cookies
4. Make sure you're 13+ years old (GitHub requirement)
5. Check email for verification code (check spam folder too)

---

### Problem: Can't upload files to GitHub

**Solutions:**
1. Make sure you're logged in to GitHub
2. Check internet connection
3. Try uploading smaller batches of files
4. Use Chrome browser (most compatible)
5. If folder upload doesn't work, upload files individually

---

## ❓ FAQ (Frequently Asked Questions)

### Q: Is this really free?
**A:** Yes! GitHub Actions is free for public repositories. You get 2,000 minutes per month (that's 33 hours of build time).

---

### Q: How long does the build take?
**A:** 
- First build: 5-10 minutes
- Later builds: 3-5 minutes
- Total time (including upload): 15-20 minutes

---

### Q: Can I build multiple times?
**A:** Yes! Every time you change code and push to GitHub, it automatically builds a new APK.

---

### Q: Is the APK safe to install?
**A:** Yes! It's your own code being built in GitHub's secure cloud. No one else can access it.

---

### Q: Can I share the APK with friends?
**A:** Yes! Send them the APK file via WhatsApp, Telegram, or any file sharing app.

---

### Q: What if I want to update the app later?
**A:** 
1. Edit the code files in your GitHub repository
2. Commit changes
3. Wait for new build (5 minutes)
4. Download new APK
5. Install (will update existing app)

---

### Q: Can I build a release version (not debug)?
**A:** Yes, but release APKs need to be signed with a keystore. For now, use debug APK (works perfectly fine).

---

### Q: What's the difference between debug and release APK?
**A:** 
- **Debug APK:** For testing, easier to build, slightly larger
- **Release APK:** For Play Store, optimized, needs signing
- Both work the same for personal use

---

### Q: Can I publish this to Google Play Store?
**A:** Yes, but you'll need:
- Google Play Developer account ($25 one-time fee)
- Signed release APK
- App screenshots and description
- Privacy policy

---

### Q: Will the app work on all Android phones?
**A:** The app works on Android 8.0 (Oreo) and higher. That's about 95% of phones in use today.

---

### Q: Can I modify the code after building?
**A:** Yes! Edit any file in your GitHub repository, commit changes, and a new APK will build automatically.

---

### Q: What if GitHub changes their free plan?
**A:** GitHub has offered free Actions for public repos since 2019. It's unlikely to change, but if it does, you can:
- Use GitLab CI (also free)
- Use Bitbucket Pipelines (free tier)
- Build locally on a computer

---

### Q: How much storage does the APK use?
**A:** 
- APK file: ~15-20 MB
- Installed app: ~30-50 MB
- App data (step history): ~5-10 MB over time

---

### Q: Can I delete the repository after downloading APK?
**A:** Yes, but then you won't be able to rebuild or update the app. Keep the repository if you want to make changes later.

---

### Q: What if I lose the APK file?
**A:** No problem! Go to your GitHub repository → Actions tab → Find the build → Download APK again. Artifacts are kept for 30 days.

---

## 🎯 Quick Reference Checklist

Use this checklist to track your progress:

- [ ] Created GitHub account
- [ ] Created StepTracker repository (public)
- [ ] Downloaded project code from workspace
- [ ] Extracted ZIP file
- [ ] Uploaded all files to GitHub
- [ ] Verified `.github/workflows/build-apk.yml` exists
- [ ] Started the build (Actions tab)
- [ ] Waited for build to complete (green checkmark)
- [ ] Downloaded StepTracker-APK.zip from Artifacts
- [ ] Extracted the ZIP
- [ ] Enabled "Install unknown apps" permission
- [ ] Installed app-debug.apk
- [ ] Opened app and completed onboarding
- [ ] Started tracking steps! 🎉

---

## 📞 Need Help?

### If You're Stuck:

1. **Check this guide again** — most answers are here
2. **Look at error messages** — they usually tell you what's wrong
3. **Try again** — sometimes it's just a temporary glitch
4. **Ask a friend** — someone tech-savvy can help
5. **Search online** — Google the error message

### Common Issues Quick Fix:

| Problem | Quick Fix |
|---------|-----------|
| Can't sign up | Use different email |
| Upload fails | Try smaller batches |
| Build fails | Check all files uploaded |
| APK won't install | Enable "unknown sources" |
| Can't find APK | Check Downloads folder |

---

## 🎉 Success!

If you've completed all steps, congratulations! You've:

✅ Created a GitHub account  
✅ Set up automatic APK building  
✅ Built an Android app from source code  
✅ Installed and configured the app  

**You're now tracking your steps with an app you built yourself!**

---

## 📚 What's Next?

### Learn More:
1. **Explore the code** — tap on files in your repository to see the code
2. **Make changes** — edit colors, text, or features
3. **Rebuild** — commit changes and get a new APK
4. **Share** — send APK to friends and family

### Advanced Topics:
- Add more features to the app
- Change the app icon and name
- Create a release version for Play Store
- Set up automatic testing

---

**Thank you for following this guide! Happy step tracking! 🚶‍♂️📱**

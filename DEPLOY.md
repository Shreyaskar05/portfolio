# How to Deploy Your Portfolio

Since you want to deploy your site and easily make changes later, **GitHub Pages** is the best free option. It hosts your website directly from your code.

## Option 1: The "No-Code" Way (Easiest)

You can upload your files directly to GitHub using your web browser.

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com/) and sign up for a free account if you don't have one.

### Step 2: Create a Repository
1. Click the **+** icon in the top-right corner and select **New repository**.
2. Name it something like `portfolio` or `my-website`.
3. Make sure **Public** is selected.
4. Click **Create repository**.

### Step 3: Upload Your Files
1. On the next screen, look for the link that says **uploading an existing file**.
2. Drag and drop **ALL** your project files (`index.html`, `css` folder, `js` folder, etc.) into the upload box.
3. **Important:** Wait for all files to finish uploading.
4. In the "Commit changes" box at the bottom, type "Initial upload" and click **Commit changes**.

### Step 4: Turn on the Website
1. In your repository, click on **Settings** (top tab).
2. On the left sidebar, click on **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and save.
4. Wait a minute or two. Refresh the page. You will see a box appear at the top saying:  
   "Your site is live at `https://your-username.github.io/portfolio/`"

**Done!** Click that link to see your site.

---

## How to Make Changes Later

To update your site (e.g., add a new project):
1. **Edit the file on your computer** (like you are doing now with me).
2. Go back to your GitHub repository page.
3. Click **Add file** > **Upload files**.
4. Drag the *updated* file(s) (e.g., just `index.html`) into the box.
5. Click **Commit changes**.

GitHub will automatically update your live website within 1-2 minutes.

---

## Option 2: The "Pro" Way (Installing Git)

If you want to feel like a real developer and handle updates faster:
1. Download and install [Git for Windows](https://git-scm.com/download/win).
2. Open your terminal in VS Code.
3. Run these commands one by one:
   ```bash
   git init
   git add .
   git commit -m "First commit"
   # (You will need to run the commands GitHub gives you to link the repo)
   git push -u origin main
   ```
This allows you to push changes directly from VS Code!

# How to Deploy Your Professional Portfolio

Follow these steps to get your portfolio live on GitHub Pages.

## Step 1: Create a New Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: **portfolio** (or your preferred name)
3. Description: "Professional Tourism & Operations Portfolio"
4. Choose **Public**
5. Click "Create repository"

## Step 2: Add the Files

You can do this in two ways:

### Option A: Upload via Web Interface (Easiest)
1. Go to your new repository
2. Click "Add file" → "Create new file"
3. Create each file as listed below:
   - `README.md`
   - `index.html`
   - `CV.md`

### Option B: Use Git Command Line
```bash
# Clone your repository
git clone https://github.com/ayitsmejivan/portfolio.git
cd portfolio

# Add files (copy the content into these files)
echo "# Jivan Parajuli | Tourism & Operations Professional" > README.md
# Add other files...

# Commit and push
git add .
git commit -m "Initial portfolio setup"
git push origin main

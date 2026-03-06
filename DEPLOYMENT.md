# 🚀 Deployment Guide

Step-by-step instructions to deploy **Jivan Parajuli's Professional Portfolio** to GitHub Pages and integrate it with LinkedIn.

---

## 📋 Prerequisites

- A GitHub account (free at [github.com](https://github.com))
- The portfolio files: `index.html`, `README.md`, `CV.md`

---

## 🌐 Step 1: Deploy to GitHub Pages

### Option A: Enable Pages on the Existing Repository

1. Go to your repository: `https://github.com/ayitsmejivan/Portfolio`
2. Click the **Settings** tab
3. In the left sidebar, click **Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **Branch**: `main` (or `master`) and **Folder**: `/ (root)`
6. Click **Save**
7. Wait 1–2 minutes — your site will be live at:
   ```
   https://ayitsmejivan.github.io/Portfolio
   ```

### Option B: Create a Dedicated Portfolio Repository

If you want the portfolio at `https://ayitsmejivan.github.io` (root URL):

1. Go to [github.com/new](https://github.com/new)
2. Set the repository name to exactly: **`ayitsmejivan.github.io`**
3. Make it **Public**
4. Click **Create repository**
5. Upload `index.html`, `README.md`, `CV.md`, and `DEPLOYMENT.md`
6. GitHub Pages is automatically enabled for this special repository name
7. Your portfolio will be live at:
   ```
   https://ayitsmejivan.github.io
   ```

---

## 🔄 Step 2: Update Portfolio Files via Git

```bash
# Clone the repository
git clone https://github.com/ayitsmejivan/Portfolio.git
cd Portfolio

# Make your changes to index.html, README.md, CV.md, etc.

# Stage and commit changes
git add .
git commit -m "Update portfolio content"

# Push to GitHub (triggers automatic deployment)
git push origin main
```

Changes go live automatically within ~1–2 minutes after pushing.

---

## 💼 Step 3: LinkedIn Integration

### 3.1 Add Portfolio URL to LinkedIn Profile

1. Go to [linkedin.com](https://www.linkedin.com) and log in
2. Click your profile picture → **View Profile**
3. Click the **Edit** (pencil) icon on your profile header
4. Scroll down to **Contact info** → click **Edit**
5. Under **Website**, click **Add website**
6. Enter:
   - **URL**: `https://ayitsmejivan.github.io/Portfolio`
   - **Type**: Portfolio
   - **Title**: Professional Portfolio
7. Click **Save**

### 3.2 Add LinkedIn Profile Link to the Portfolio

The portfolio already includes your LinkedIn profile link:
```
https://www.linkedin.com/in/jivan-parajuli-986742144
```

This is embedded in:
- The hero section LinkedIn badge
- The social media links
- The contact section
- The footer

### 3.3 Share Your Portfolio on LinkedIn

1. Go to your LinkedIn profile
2. Click **Add section** → **Featured** → **Link**
3. Paste: `https://ayitsmejivan.github.io/Portfolio`
4. Add title: "My Professional Portfolio"
5. Click **Save**

This will showcase your portfolio directly on your LinkedIn profile page.

### 3.4 LinkedIn Profile Consistency

Ensure your LinkedIn profile matches the portfolio:

| Field | Value |
|-------|-------|
| Name | Jivan Parajuli |
| Headline | Tourism & Operations Professional \| MBA Student at Hochschule Bremen |
| Location | Bremen, Germany |
| Current Education | Hochschule Bremen – MBA International Tourism Management |
| Most Recent Role | Operations Manager at Holidays to Nepal |
| Contact Email | jivaneklo@gmail.com |
| GitHub | https://github.com/ayitsmejivan |

---

## 🔍 Step 4: SEO Optimization

The portfolio already includes meta tags for SEO. To improve visibility further:

### Google Search Console
1. Go to [search.google.com/search-console](https://search.google.com/search-console)
2. Click **Add property** → **URL prefix**
3. Enter: `https://ayitsmejivan.github.io/Portfolio`
4. Verify ownership (HTML tag method recommended for GitHub Pages)
5. Submit your sitemap (just the URL for a single-page site)

### Share on Professional Networks
After deployment, share your portfolio URL in:
- LinkedIn posts
- Email signatures
- Job applications
- Your GitHub profile bio

---

## ✅ Deployment Checklist

- [ ] Repository is public on GitHub
- [ ] GitHub Pages is enabled (Settings → Pages)
- [ ] Portfolio is accessible at the public URL
- [ ] LinkedIn profile URL added to portfolio (already in `index.html`)
- [ ] Portfolio URL added to LinkedIn profile (Contact info → Website)
- [ ] Portfolio featured in LinkedIn Featured section
- [ ] Email signature updated with portfolio URL
- [ ] All links in portfolio tested (email, phone, LinkedIn, GitHub)

---

## 🛠️ Troubleshooting

### Site not loading after enabling Pages?
- Wait 5–10 minutes for initial deployment
- Ensure the repository is **Public** (not private)
- Check Settings → Pages to confirm deployment status

### Font Awesome icons not showing?
- The portfolio loads Font Awesome from `cdnjs.cloudflare.com`
- Ensure you have an internet connection when viewing
- Check the browser console for any blocked resource errors

### LinkedIn link not working?
- The LinkedIn URL in the portfolio is: `https://www.linkedin.com/in/jivan-parajuli-986742144`
- Verify this matches your actual LinkedIn profile URL
- LinkedIn profile must be set to **Public**

---

## 📞 Support

For questions about the portfolio:
- **Email**: [jivaneklo@gmail.com](mailto:jivaneklo@gmail.com)
- **LinkedIn**: [jivan-parajuli-986742144](https://www.linkedin.com/in/jivan-parajuli-986742144)
- **GitHub**: [ayitsmejivan](https://github.com/ayitsmejivan)

---

*Last updated: March 2026*

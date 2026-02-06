# The LAN House Website

## Setup Instructions

### Email Form Integration

Your contact form is configured to use **Formspree** (100% free for up to 50 submissions/month).

**Setup Steps:**

1. Go to [formspree.io](https://formspree.io)
2. Sign up for a free account
3. Create a new form
4. Copy your form endpoint (looks like: `https://formspree.io/f/xyzabc123`)
5. Open `the-lan-house-website.html`
6. Find line with: `action="https://formspree.io/f/YOUR_FORM_ID"`
7. Replace `YOUR_FORM_ID` with your actual Formspree form ID
8. Save the file

Now all form submissions will be sent directly to your email!

---

## Free Hosting Options

### Option 1: GitHub Pages (Recommended - Easiest)
**100% FREE, Custom domain supported**

1. Create a free GitHub account at [github.com](https://github.com)
2. Create a new repository named: `the-lan-house`
3. Upload all files from this folder:
   - `the-lan-house-website.html` (rename to `index.html`)
   - The entire `images` folder
4. Go to Settings → Pages
5. Select "Deploy from main branch"
6. Your site will be live at: `https://yourusername.github.io/the-lan-house`

**Custom Domain:**
- Buy a domain from Namecheap, GoDaddy, etc. (around $12/year)
- Add a CNAME file pointing to your domain
- Configure DNS settings (GitHub provides instructions)

---

### Option 2: Netlify (Also Great)
**100% FREE, Drag & drop, Custom domain**

1. Go to [netlify.com](https://netlify.com)
2. Sign up for free
3. Drag and drop your entire folder
4. Site goes live instantly!
5. Free subdomain: `your-site-name.netlify.app`
6. Can add custom domain for free

---

### Option 3: Vercel
**100% FREE, Very fast**

1. Sign up at [vercel.com](https://vercel.com)
2. Import your GitHub repository OR drag & drop files
3. Deploy automatically
4. Free subdomain + custom domain support

---

## File Structure

```
/the-lan-house-website/
├── index.html (rename from the-lan-house-website.html)
└── images/
    ├── IMG_5950.jpeg
    ├── IMG_2415.jpeg
    ├── IMG_5098.jpeg
    ├── IMG_4702.jpeg
    ├── IMG_4570.jpeg
    ├── IMG_4421.jpeg
    ├── DSC_1770.jpeg
    ├── DSC_1773.jpeg
    ├── DSC_1772.jpeg
    ├── DSC_1774.jpeg
    └── DSC_1371.jpeg
```

**IMPORTANT:** 
- Rename `the-lan-house-website.html` to `index.html` before uploading
- Keep all images in the `images` folder

---

## Customization

### Update Social Media Links
In the footer section, replace with your actual links:
```html
<a href="https://instagram.com/yourhandle" target="_blank">Instagram</a>
<a href="https://tiktok.com/@yourhandle" target="_blank">TikTok</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://facebook.com/yourpage" target="_blank">Facebook</a>
```

### Add More Portfolio Items
To add more builds, copy this block in the portfolio section:
```html
<div class="portfolio-item">
    <img src="images/your-new-image.jpeg" alt="Description of build">
</div>
```

---

## Support

If you need help:
1. GitHub Pages Guide: [pages.github.com](https://pages.github.com)
2. Netlify Docs: [docs.netlify.com](https://docs.netlify.com)
3. Formspree Docs: [help.formspree.io](https://help.formspree.io)

---

## Quick Start Summary

1. ✅ Rename HTML file to `index.html`
2. ✅ Setup Formspree account & update form action
3. ✅ Choose hosting (GitHub Pages recommended)
4. ✅ Upload files
5. ✅ Update social media links
6. ✅ (Optional) Add custom domain

**Your site can be live in under 10 minutes!**

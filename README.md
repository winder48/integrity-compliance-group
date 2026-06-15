[README.md](https://github.com/user-attachments/files/28958329/README.md)
# Integrity Compliance Group Website

## Site Structure

```
index.html                                  ← Main page (upload to root)
guides/
  Texas_Air_Permitting_Guide_product.html   ← Texas guide product page
  Indiana_Air_Permitting_Guide_product.html ← Indiana guide product page
documents_and_templates.html               ← Internal use only (not linked on site)
```

## Setup Instructions

1. Upload all files to your GitHub repository
2. Go to **Settings → Pages** in your repo
3. Set Source to **Deploy from branch → main → / (root)**
4. Your site will be live at `https://yourusername.github.io/repository-name`

## Before Going Live

- Replace `https://buy.stripe.com/YOUR_LINK_HERE` in both guide pages with your real Stripe checkout links

## Notes

- `documents_and_templates.html` is a backup of your Documents & Procedures — not published on the site
- Logo is embedded directly in each HTML file — no separate image folder needed

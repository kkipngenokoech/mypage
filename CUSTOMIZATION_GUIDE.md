# Website Customization Guide

This guide will help you customize your academic website template. The website has been pre-configured with placeholder content that you should replace with your own information.

## Quick Start Checklist

### 1. Update Basic Information in `config.yml`

- [ ] Replace "Your Name" with your actual name (appears in multiple places)
- [ ] Update the site description
- [ ] Add your email address
- [ ] Update social media links (GitHub, Twitter, LinkedIn, Google Scholar)
- [ ] Update the profile image filename (currently set to "picture.png")

### 2. Replace Profile Image

- [ ] Add your profile picture as `static/picture.png` (160x160px recommended)
- [ ] Or update the image filename in `config.yml` if you use a different name

### 3. Update Content Pages

#### About Me (`content/moreaboutme/_index.md`)
- [ ] Replace template content with your academic background
- [ ] Add your research interests
- [ ] Include personal interests and hobbies

#### Research (`content/papers/_index.md`)
- [ ] Add your publications
- [ ] Include ongoing projects
- [ ] Add links to papers, preprints, and code repositories

#### Teaching (`content/teaching/_index.md`)
- [ ] Add courses you've taught
- [ ] Include teaching materials and resources
- [ ] Add workshop or tutorial content

#### Contact Information
- [ ] Update `content/location.md` with your office address
- [ ] Update `content/officehours.md` with your availability
- [ ] Replace the CV file at `content/cv.pdf` with your own

### 4. Customize Menu Items

In `config.yml`, you can modify the navigation menu:
- Add/remove menu items
- Change URLs
- Adjust the order (weight parameter)

### 5. Add Your Publications

Create individual folders in `content/papers/` for each publication. See the existing examples for structure.

### 6. Social Media Setup

Update these sections in `config.yml`:
- `socialIcons` - for the icon links on your profile
- `social` - for metadata

### 7. Website Deployment

1. Update the `baseURL` in `config.yml` to your GitHub Pages URL
2. Commit and push changes to GitHub
3. Enable GitHub Pages in your repository settings
4. The site will be built automatically via GitHub Actions

## File Structure Overview

```
├── config.yml              # Main configuration file
├── content/                 # All website content
│   ├── moreaboutme/        # About page
│   ├── papers/             # Publications and projects
│   ├── teaching/           # Teaching materials
│   ├── location.md         # Contact information
│   ├── officehours.md      # Office hours
│   └── cv.pdf              # Your CV (replace this)
├── static/                 # Static files (images, etc.)
│   └── picture.png         # Your profile image (add this)
└── themes/PaperMod/        # Theme files (don't modify)
```

## Tips for Customization

1. **Start with `config.yml`** - This is the most important file to customize first
2. **Test locally** - Run `hugo server` to preview changes before publishing
3. **Keep backups** - Make sure your changes are committed to git
4. **Follow the template structure** - The existing pages provide good examples to follow

## Getting Help

- Hugo documentation: https://gohugo.io/documentation/
- PaperMod theme docs: https://github.com/adityatelange/hugo-PaperMod
- Original template docs: https://pascalmichaillat.org/d5/

---

*This template has been customized for you. Remove the existing example content and replace it with your own information.*

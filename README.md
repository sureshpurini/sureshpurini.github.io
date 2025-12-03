# Personal Academic Website

A professional website for academic profile showcasing research, publications, and teaching.

## Setup Instructions

### 1. Customize Your Content

Edit `index.html` and replace the following placeholders:
- `[Your Name]` - Your full name
- `[Your Department]` - Your department name
- `[Your University]` - Your institution name
- Add your bio, research interests, publications, courses, and contact information

### 2. Add Your Photo (Optional)

- Add your professional photo to the directory (e.g., `photo.jpg`)
- In `index.html`, uncomment the image tag and update the src attribute:
  ```html
  <img src="photo.jpg" alt="Profile Photo">
  ```
- Remove or comment out the placeholder div

### 3. Deploy to GitHub Pages

#### Option 1: Create a GitHub repository via web interface

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right and select "New repository"
3. Name it `username.github.io` (replace `username` with your GitHub username)
4. Make it public
5. Initialize without README (we already have one)
6. Follow the commands below to push your code

#### Option 2: Use GitHub CLI (if installed)

```bash
cd ~/personal-website
git init
git add .
git commit -m "Initial commit: Academic website"
gh repo create username.github.io --public --source=. --push
```

#### Option 3: Manual Git setup

```bash
cd ~/personal-website
git init
git add .
git commit -m "Initial commit: Academic website"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### 4. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" > "Pages"
3. Under "Source", select "main" branch
4. Click "Save"
5. Your site will be available at `https://username.github.io`

## Customization Tips

- Update colors in `style.css` by changing the hex values
- Add more sections as needed
- Include links to your Google Scholar, ResearchGate, or ORCID profiles
- Add PDFs of your papers in a `/papers` folder and link to them

## Local Preview

Open `index.html` in your web browser to preview the site locally before publishing.

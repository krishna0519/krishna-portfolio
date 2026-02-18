# Deployment Instructions for Portfolio Website

## Option 1: Netlify Drop (Easiest - Recommended)

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop the entire `Portfilo` folder onto the page
3. Your site will be deployed instantly and you'll get a free URL like `https://your-site-name.netlify.app`
4. You can customize the domain name in Netlify dashboard

## Option 2: Vercel CLI

1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to the Portfilo folder: `cd Portfilo`
3. Run `vercel --prod`
4. Follow the prompts to deploy

## Option 3: GitHub Pages

1. Create a new repository on GitHub
2. Upload the contents of the Portfilo folder
3. Go to Settings > Pages
4. Select "main" branch and save
5. Your site will be available at `https://yourusername.github.io/repository-name`

## Option 4: Run Locally (Development)

To view locally:

### Using Python:
```
bash
cd Portfilo
python -m http.server 8000
```
Then open http://localhost:8000 in your browser

### Using Node.js:
```
bash
cd Portfilo
npx serve
```
Then open the URL shown (usually http://localhost:3000)

## Files Included:
- `index.html` - Entry point (redirects to portfolio.html)
- `portfolio.html` - Main portfolio website
- `assets/profile.jpg` - Profile image
- `assets/resume.pdf` - Resume PDF
- `netlify.toml` - Netlify configuration for deployment

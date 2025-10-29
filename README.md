# Sabit Kadli Portfolio Website

Professional portfolio website showcasing business analysis and technical skills through interactive games.

## File Structure

```
portfolio-website/
├── index.html              # Main portfolio page
├── games.html              # Interactive games page
├── css/
│   ├── style.css          # Main stylesheet
│   └── games.css          # Game-specific styles
├── js/
│   ├── main.js            # Main site interactions
│   ├── counter.js         # Animated metrics counter
│   ├── games-api.js       # API integration game
│   ├── games-sql.js       # SQL query builder game
│   ├── games-react.js     # React memory game
│   └── games-telephony.js # Telephony routing game
└── assets/
    └── Pics
```

## Setup Instructions

### 1. Add Your Photos

Place your photos in the `assets/` folder with these names:
- `profile.jpg` - Main profile photo (use IMG_20190530_143349.jpg)
- Add any additional images you want to display

### 2. Upload to GitHub

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/yourusername/sabitkadli.com.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to repository Settings
2. Navigate to Pages section
3. Set Source to "main" branch
4. Set folder to "/ (root)"
5. Save

### 4. Configure Custom Domain (Namecheap)

1. In GitHub Pages settings, add custom domain: `sabitkadli.com`
2. In Namecheap, go to Advanced DNS
3. Add these A Records (Host: @):
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
4. Add CNAME Record:
   - Host: www
   - Value: yourusername.github.io

### Alternative: Deploy to AWS S3

For more control and to demonstrate cloud skills:

1. Create S3 bucket named: sabitkadli.com
2. Enable static website hosting
3. Upload all files
4. Set up CloudFront distribution
5. Configure Route 53 for domain
6. Add ACM SSL certificate

## Features

- Fully responsive design
- Mobile-optimized layout
- Animated metrics counters
- 4 interactive skill games:
  - API Integration Matcher
  - SQL Query Builder
  - React Memory Game
  - Telephony Call Routing
- Clean, professional presentation
- Fast loading and performance

## Customization

- Edit content in `index.html` and `games.html`
- Modify colors in CSS variables (`:root` section in `style.css`)
- Adjust game logic in respective JS files
- Update images in `assets/` folder

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Personal portfolio - All rights reserved.

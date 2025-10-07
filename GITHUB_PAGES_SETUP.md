# GitHub Pages Setup Instructions

## How to Enable GitHub Pages for This Repository

1. **Navigate to Repository Settings**
   - Go to the repository: https://github.com/LittleMonkeyLab/FoundationCalendar
   - Click on "Settings" (top menu bar)

2. **Enable GitHub Pages**
   - In the left sidebar, click on "Pages"
   - Under "Build and deployment":
     - Source: Select "Deploy from a branch"
     - Branch: Select `main` (or the current branch)
     - Folder: Select `/ (root)`
   - Click "Save"

3. **Wait for Deployment**
   - GitHub will build and deploy your site (usually takes 1-2 minutes)
   - A notification will appear at the top of the Pages settings with your site URL

4. **Access Your Site**
   - Your site will be available at: `https://littlemonkeylab.github.io/FoundationCalendar/`
   - Main pages:
     - Landing page: `https://littlemonkeylab.github.io/FoundationCalendar/`
     - Weekly calendar: `https://littlemonkeylab.github.io/FoundationCalendar/calendar.html`
     - Full timetable: `https://littlemonkeylab.github.io/FoundationCalendar/timetable.html`
     - Week crosswalk: `https://littlemonkeylab.github.io/FoundationCalendar/weekcrosswalk.html`

## Files Structure

```
FoundationCalendar/
├── index.html          # Landing page with navigation
├── calendar.html       # Weekly teaching schedule
├── timetable.html      # Full timetable view
├── weekcrosswalk.html  # Week mapping reference
└── README.md           # Repository documentation
```

## Notes

- All HTML files are standalone and don't require any build process
- The site uses no external dependencies - everything is inline HTML/CSS
- Mobile responsive design included in all pages

# Asher Zero Website

A single-page, no-scroll website for the Asher Zero creative system. The site serves as a weekly interface for creative drops, featuring a full-screen background image, email capture form, and download links.

## Features

- Full-screen background image that changes weekly
- Email capture form using Tally
- Download link for the weekly drop
- Starter Kit download link
- Social media links
- Fully responsive design
- No-scroll, single-page interface

## Weekly Update Process

### 1. Update Background Image
1. Replace the file: `images/AZ WEEK #1 BACKGROUND IMAGE.png` with your new image
2. Keep the exact same filename format for consistency
3. Recommended image size: 1920x1080px or larger (will be scaled to fit)

### 2. Update Tally Form (if needed)
1. Go to [Tally](https://tally.so) and create a new form
2. Update the form ID in `index.html` (look for `data-tally-embed` and the form action URL)
3. Test the form submission to ensure it works correctly

### 3. Update Weekly Drop Link
1. Upload your weekly drop to Dropbox
2. Update the link in `index.html` (look for the Starter Kit button)
3. Ensure the link has `?dl=1` at the end to force download

### 4. Test the Update
1. Open the site in a browser
2. Verify the new background image displays correctly
3. Test the form submission
4. Test the download links
5. Check on mobile devices to ensure responsiveness

## File Structure

```
asher-zero/
├── css/
│   └── styles.css
├── images/
│   ├── AZ LOGO GRAY.png
│   └── AZ WEEK #1 BACKGROUND IMAGE.png
├── index.html
└── README.md
```

## Troubleshooting

### Background Image Not Showing
1. Check the filename matches exactly (including spaces and capitalization)
2. Verify the image is in the `images` folder
3. Check the browser's developer console for 404 errors
4. Try accessing the image directly: `http://localhost:8000/images/AZ%20WEEK%20%231%20BACKGROUND%20IMAGE.png`

### Form Not Working
1. Verify the Tally form ID is correct
2. Check that the form action URL matches your Tally form
3. Test the form in an incognito window to rule out caching issues

## Credits

- Built with HTML, CSS, and vanilla JavaScript
- Form handling by [Tally](https://tally.so)
- File hosting on Dropbox
- Font: Inter by Google Fonts

# Koshish Charitable Trust - News Site

This is a simple news portal for the Koshish Charitable Trust, built with HTML, CSS (Tailwind utility classes), and JavaScript. It allows admins to add news, and visitors to view the latest updates and filter by category.

## Features

- **Admin Panel**: Add news with title, category, content, and optional image URL.
- **Latest News**: News is shown in reverse chronological order (latest first).
- **Category Filter**: Filter news by category (Community, Health, Education, Environment, Fundraising).
- **Read More Modal**: Click "Read More" to view the full news content in a modal popup.
- **Persistent Storage**: News is saved in the browser's localStorage, so it persists after page reloads.
- **Responsive Design**: Works well on desktop and mobile.

## How to Use

1. **Open `main.html` in your browser.**
2. Click the **Admin Panel** button in the header to open the admin form.
3. Fill in the news details and click **Publish News**.
4. The news will appear at the top of the "Latest News & Updates" section.
5. Use the filter buttons to view news by category.
6. Click **Read More** on any news card to see the full content in a modal.

## Customization

- To change the default image for news, edit the `addNews` function in `main.html` and update the default image URL.
- To reset all news, clear your browser's localStorage for this site.

## Tech Stack
- HTML5
- CSS (Tailwind utility classes, no build step required)
- JavaScript (Vanilla, no frameworks)

## License
This project is for demonstration and educational purposes. Please credit Koshish Charitable Trust if you use or adapt this code.

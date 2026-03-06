# Amsterdam Spots for KubeCon EU 2025

A local's guide to the best coffee, food, and bars in Amsterdam — curated for KubeCon attendees.

**Live site:** `https://YOUR_USERNAME.github.io/amsterdam-kubecon-guide/`

## Deploy to GitHub Pages

### Quick setup (5 minutes)

1. **Create a new GitHub repo**
   - Go to [github.com/new](https://github.com/new)
   - Name it `amsterdam-kubecon-guide`
   - Set it to **Public**
   - Click **Create repository**

2. **Push the files**
   ```bash
   cd /path/to/this/folder
   git init
   git add .
   git commit -m "Initial commit: Amsterdam KubeCon guide"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/amsterdam-kubecon-guide.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repo → **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click **Save**
   - Your site will be live at `https://YOUR_USERNAME.github.io/amsterdam-kubecon-guide/` within a minute or two

### Optional: Add a map

The page includes a placeholder for an embedded Google Map. To add your own:

1. Go to [Google My Maps](https://www.google.com/maps/d/)
2. Create a new map and add pins for each spot
3. Click **Share** → set to "Anyone with the link"
4. Click the three dots menu → **Embed on my site**
5. Copy the `src` URL from the iframe code
6. In `index.html`, replace `YOUR_MAP_ID` in the iframe `src` with your map's embed URL

If you'd rather skip the map, just delete the `<div class="map-wrapper">...</div>` block in `index.html`.

## What's included

- **53 spots** across 7 categories: Coffee, Bakeries, Breakfast, Lunch, Dinner, Fancy Dinner, Bars
- Category filter pills
- Text search across names and descriptions
- Google Maps links for each spot
- Mobile-first, responsive design
- Zero dependencies — just a single HTML file

## Credits

Curated by a local Amsterdamer for the KubeCon EU 2025 community.

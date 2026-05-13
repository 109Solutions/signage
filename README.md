# Sharon Corners — TV Signage

Digital signage displays for Sharon Corners Retirement Living, designed for 1920×1080 TV screens.

---

## Displays

| File | Description |
|------|-------------|
| `birthdays.html` | Monthly birthday display — auto-updates daily and monthly |
| `index.html` | Portal page linking to all displays |

---

## How to Set Up GitHub Pages

1. **Create a new GitHub repository** at [github.com/new](https://github.com/new)
   - Name it something like `sharon-corners-signage`
   - Set it to **Public**

2. **Upload all files** from this folder into the repository

3. **Enable GitHub Pages**
   - Go to your repository → **Settings** → **Pages**
   - Under *Source*, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. **Your site will be live** at:
   ```
   https://YOUR-USERNAME.github.io/sharon-corners-signage/
   ```

---

## Using on a TV

1. Open Chrome or Edge on the TV/display computer
2. Navigate to your GitHub Pages URL (e.g. `https://YOUR-USERNAME.github.io/sharon-corners-signage/birthdays.html`)
3. Press **F11** to go fullscreen
4. The display will stay up to date automatically — no refreshing needed

---

## How the Birthday Display Works

- **Auto-detects the current month** and shows only that month's birthdays
- **Removes past birthdays** each day at midnight — no manual updates needed
- **Highlights today's birthdays** with a 🥳 badge
- **Switches months automatically** — when June 1st arrives, it switches to June
- **No internet required** after the page loads (fonts load from Google Fonts on first load)

---

## Files

```
sharon-corners-signage/
├── index.html          # Portal / home page
├── birthdays.html      # TV birthday display
├── birthdays.csv       # Source birthday data
└── README.md           # This file
```

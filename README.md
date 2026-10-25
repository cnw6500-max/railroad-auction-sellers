# Railroad Collectibles Auction – Seller Overview

A one-page website version of the seller deck, hosted free on GitHub Pages.

- **Live site:** https://cnw6500-max.github.io/railroad-auction-sellers/
- **Repository:** https://github.com/cnw6500-max/railroad-auction-sellers

## What's in the package

| File | What it is |
|---|---|
| `index.html` | The whole website: deck sections, savings calculator, founding seller offer and interest form |
| `images/home-page.jpg` | Screenshot: site home page |
| `images/listing-page.jpg` | Screenshot: auction listing page |
| `images/listing-form.jpg` | Screenshot: listing form |
| `images/seller-dashboard.jpg` | Screenshot: seller dashboard |
| `README.md` | This file |

The `images` folder must stay a folder named `images` next to `index.html`, or the screenshots will not show.

## Upload an update to GitHub

The repository and GitHub Pages are already set up. To publish a new version:

1. **Unzip first.** If you have `railroad-auction-sellers-site.zip`, right-click it → **Extract All…** → **Extract**. GitHub does not unzip files, so never upload the .zip itself.
2. Sign in to https://github.com as **cnw6500-max** and open https://github.com/cnw6500-max/railroad-auction-sellers
3. Click **Add file** (above the file list) → **Upload files**.
4. In File Explorer, open the extracted folder. Select `index.html`, `README.md` and the `images` **folder**, and drag them onto the GitHub page.
   - Drag the `images` folder itself, not the pictures inside it, so they stay in `images/`.
   - Wait until every file is listed under the drop area (6 files).
5. Scroll down to **Commit changes**. Optionally type a note such as "Add savings calculator and founding offer", leave **Commit directly to the main branch** selected, and click **Commit changes**.
6. Wait 1–2 minutes. GitHub rebuilds the site automatically (progress shows under the **Actions** tab, green tick when done).
7. Open the live site and press **Ctrl + F5** to skip the old copy your browser saved.

Files with the same name are replaced; nothing else in the repository is touched.

## Check it worked

- The menu bar shows: Costs · Plans · Calculator · Founding offer · The site · Getting paid · Contact
- **Calculator:** with the example values it shows about **$73 a month** saved; change a number and it updates.
- **Founding offer:** two gold-bordered cards, $80 and $200 for the first year.
- **Contact:** the form at the bottom. Send yourself a test entry; it should arrive by email from Formspree.

## Settings you may want to change later (in `index.html`)

- **Formspree form:** `var FORMSPREE_ID = "mrpppzpp";` — entries go to the email on that Formspree form.
- **Fee rates for the calculator:** the `var FEES = { ... }` block. Each rate has a comment saying what it is.
- **Founding prices:** search for `Founding Collector` and `Founding Dealer`. They appear in the offer cards, the form's drop-down and the calculator's plan list — change all three.

Open `index.html` in Notepad to edit, save, then upload it again with the steps above.

## If something goes wrong

- **Screenshots missing:** the images were uploaded loose instead of in an `images` folder. Upload the `images` folder again.
- **Old version still showing:** wait a couple of minutes, check the **Actions** tab has a green tick, then press Ctrl + F5.
- **Page shows only the repository name:** `index.html` is missing from the top level of the repository. Upload it again.
- **Site not found (404):** in the repository go to **Settings → Pages** and check Source is "Deploy from a branch", branch `main`, folder `/ (root)`.

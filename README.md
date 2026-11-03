# KOTA'S CREATIVE HUB — Official Business Website
**Capture | Create | Celebrate**  
*Kodad, Telangana – 508206, India*

---

## 🌟 Overview
**KOTA'S CREATIVE HUB** is a premier creative photography studio, kids milestone photography destination, luxury private party celebration venue, event decoration hub, and event visual LED screen service provider located in Kodad, Telangana.

This production-ready business website is engineered to reflect a modern, luxury photography aesthetic with soft cream (`#faf9f6`), pristine white (`#ffffff`), soft pastel pink (`#fdf2f4`), deep luxury navy (`#0a1128`), and metallic gold accents (`#c5a059`).

---

## 📍 Business Information & Contacts

- **Business Name:** KOTA'S CREATIVE HUB
- **Tagline:** Capture | Create | Celebrate
- **Studio Address:** 1097 and 1098, 2nd Floor, Chandramouli Complex, Beside Ranga Theater, Kodad, Telangana – 508206.
- **Key Contacts:**
  - **Kota Satwik:** 97054 26842 ([Click to Call](tel:+919705426842))
  - **Kota Srinivas Rao:** 99486 43909 ([Click to Call](tel:+919948643909))
- **Official WhatsApp:** `919705426842` ([Chat on WhatsApp](https://wa.me/919705426842))
- **Instagram Handle:** [@KOTA_S__CREATIVE_HUB](https://www.instagram.com/KOTA_S__CREATIVE_HUB)

---

## 🎯 The Six Official Services

1. **Kids & Newborn Photography** (Starting from ₹2,000)
   - Newborn photoshoots, baby milestone photography, birthday shoots, family portraits, and traditional & modern baby poses.
2. **Creative Photography Studio**
   - Professional studio photoshoots, maternity photography, portraits, and special occasion shoots.
3. **Party Rooms & Decorations** (₹1,500 / 1½ Hours)
   - Private decorated celebration room for birthday parties, baby showers, and milestone family gatherings with capacity for 40–50 guests (package includes up to 10 members).
4. **Creative Sets & Backdrops**
   - Handcrafted creative themes: Moon & Stars, Flower Blossom, Nature & Forest, Musical Piano, Honey Bee Adventure, and Fairytale Storybook.
5. **Professional Editing Studio**
   - High-end digital photo editing, cinematic event video editing, custom album designing, and retouching.
6. **LED Screens & Event Services** (Starting from ₹7,000)
   - High-definition LED display screen rentals, birthday slideshows, live feeds, and event visual support.

### ✨ Additional Celebration Facilities
- **Grand Fire Entry:** Dazzling pyrotechnic cold fire entry effects.
- **Smoke Entry:** Atmospheric low-lying fog and dramatic entrance smoke.
- **Custom Welcome Boards:** Personalized easels and themed entrance signages.
- **Customized Decorations:** Full theme-based balloon setups, arches, and backdrops.
- **Food & Catering Services:** Full catering arrangements tailored to guest counts.
- **40–50 Member Capacity:** Comfortable private celebration hall setting.

---

## 💻 Tech Stack & Features

- **Semantic HTML5 & Schema.org:** Complete `LocalBusiness` JSON-LD structured data for rich search engine indexing.
- **Vanilla CSS3:** Modern responsive layout using CSS Grid, Flexbox, custom variables, responsive typography, and smooth transitions without bulky dependencies.
- **Vanilla JavaScript (ES6+):**
  - **Bilingual Language Switcher:** Separate English and Telugu (`తెలుగు`) controls translate page text, placeholders, accessible labels, form feedback, and WhatsApp enquiry messages. The choice persists in `localStorage`.
  - **Direct WhatsApp Enquiry Forms:** Booking and contact forms validate the customer name, Indian mobile number, service, and booking date, then prepare a localized message for the configured WhatsApp number.
  - **Configurable social destinations:** Edit `SITE_CONFIG` in `js/main.js` to update the WhatsApp number and official Instagram profile used across the site.
  - **Interactive Lightbox Modal:** Full-screen zoom and preview for studio photos with previous/next keyboard and touch navigation.
  - **Category-Filtered Photo Gallery:** Real-time filtering across Baby & Newborn, Celebrations, and Creative Sets. Displayed portfolio photos are selected once each and are not reused across sections.
  - **Service Photography:** The supplied LED event setup and editing-studio graphic appear on their matching service cards, with localized alt text.
  - **Party Room Branding:** The supplied party-decoration photo features the KOTA'S CREATIVE HUB name at the bottom.
  - **Video Showcase:** Embedded native video player presenting the studio tour showreel.

---

## 🚀 Running Locally

You can preview the website instantly using any local web server or by opening `index.html` directly in any modern browser:

```powershell
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

Then visit `http://localhost:8000` in your browser.

## 🔎 Google Search

This project is a static HTML/CSS/JavaScript website (no React build step). It allows crawling through `robots.txt` and indexing meta tags. Google cannot crawl `localhost`, so deploy it publicly first.

### Deploy

- **GitHub Pages:** Create a GitHub repository, upload the complete project (including `index.html`, `css`, `js`, and `media`), then open **Settings → Pages**, choose deployment from the `main` branch and `/ (root)`, and save.
- **Netlify (manual):** From the project root run `node scripts/build.js`, then choose **Add new site → Deploy manually** and upload the generated `dist` folder. It contains the site files and required media, but excludes the unused `media/raw_photos` originals.
- **Netlify (Git):** Push the project to a Git provider and import it in Netlify. The included `netlify.toml` runs `node scripts/build.js` and publishes `dist` automatically.
- **Vercel (Git):** Import the Git repository. The included `vercel.json` selects the static/Other preset, runs `node scripts/build.js`, and publishes `dist`.
- **Vercel (from this computer):** In a terminal at the project root, run `npx vercel login`, finish the browser sign-in, then run `npx vercel --prod`. Select/create the Vercel project when prompted; the checked-in config builds and publishes the site.

After deployment, use the actual public HTTPS URL to add a canonical link and create `sitemap.xml`; do not use a guessed domain. Then add the site to Google Search Console (verify with the HTML tag or DNS record), submit `https://YOUR-LIVE-DOMAIN/sitemap.xml`, and use **URL Inspection → Request Indexing** for the homepage. Google decides whether and when to index or rank a site; indexing and search placement are not guaranteed.

### Netlify manual publishing steps

1. Open a terminal in this project folder.
2. Run `node scripts/build.js`.
3. Confirm the command reports that the static site was prepared in `dist`.
4. Sign in to Netlify, choose **Add new site → Deploy manually**, and drag the project's generated `dist` folder into the upload area.
5. Wait for the deploy to finish, then open the Netlify-provided `*.netlify.app` URL to test the live website.
6. To publish changes later, rerun the build command and upload the new `dist` folder.

### Vercel publishing steps

1. Install Node.js if it is not already available.
2. Open PowerShell in `C:\Users\balaj\OneDrive\Desktop\kotas`.
3. Run `npx vercel login` and complete the Vercel account sign-in in your browser.
4. Run `npx vercel --prod`.
5. Follow the prompts to select your Vercel account/team and create or link the project.
6. Vercel reads `vercel.json`, builds the static site into `dist`, and prints the production URL when deployment succeeds.
7. Open the production URL and test the English/Telugu switcher, gallery, images, booking and WhatsApp links.

You can also deploy through Vercel's Git integration after the repository has been pushed to GitHub and connected to your Vercel account.

---

## 🧪 Testing & Quality Assurance

Run the automated test suites:

```powershell
# Run Python Unit Test Suite (20 tests)
python tests/test_suite.py

# Run Node.js DOM QA Suite (61 assertions)
node tests/dom_qa.js
```

Both suites verify business details, assets, pricing, photo uniqueness, bilingual keys, social destinations, and DOM bindings.

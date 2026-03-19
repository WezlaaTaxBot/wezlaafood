# FuelBox — Deployment & Instagram Ads Guide

---

## STEP 1 — Deploy the website FREE in 3 minutes

### Option A: Netlify (Recommended — easiest)

1. Go to **https://app.netlify.com/drop**
2. Drag and drop the entire `fuelbox` folder onto the page
3. Netlify gives you a live URL instantly — like `random-name.netlify.app`
4. To get a custom URL like `fuelbox.in`, click **Domain Settings → Add custom domain**

**Buy a domain:** Go to **GoDaddy.in** or **Namecheap.com** — search `fuelbox.in` — costs ₹500–800/year.

After buying:
- In Netlify: Add your domain under **Domain Settings**
- In GoDaddy: Point nameservers to Netlify's nameservers (Netlify shows you exactly what to enter)
- SSL/HTTPS is FREE and automatic on Netlify

---

### Option B: Vercel (also free)

1. Go to **https://vercel.com**
2. Click **Add New → Project → Browse** and upload the folder
3. Done — you get a `.vercel.app` URL

---

### Option C: GitHub Pages (free forever)

1. Create account at **github.com**
2. New repository → name it `fuelbox`
3. Upload `index.html` and `netlify.toml`
4. Go to **Settings → Pages → Deploy from main branch**
5. Site goes live at `yourusername.github.io/fuelbox`

---

## STEP 2 — Set Up Meta Pixel (required for Instagram ads)

The Meta Pixel tracks who visited your site so Instagram can show your ad to people who are similar.

### Get your Pixel ID:
1. Go to **business.facebook.com**
2. Click **Events Manager** → **Connect Data Sources** → **Web**
3. Name it "FuelBox Website" → Copy your **Pixel ID** (a long number like `1234567890123456`)
4. Open `index.html`, find this line:
   ```
   fbq('init', 'YOUR_PIXEL_ID');
   ```
   Replace `YOUR_PIXEL_ID` with your actual number
5. Save and re-upload the file

---

## STEP 3 — Create Instagram Ads that link to your page

### In Meta Ads Manager (business.facebook.com/ads):

**Step 3.1 — Campaign Setup:**
- Objective: **Leads** or **Traffic**
- Budget: ₹100–300/day to start

**Step 3.2 — Audience (who sees your ad):**
- Location: India (or specific cities — Ludhiana, Delhi, Bengaluru, Mumbai, Chandigarh)
- Age: 18–35
- Interests: Fitness, Gym, Bodybuilding, Protein supplements, Zomato, Healthy eating, Weight loss
- Behaviours: Engaged shoppers, Online buyers

**Step 3.3 — Ad Creative:**
- Upload your best reel or food photo
- Headline: "Eat what you love. Hit 150g protein. Zero cooking."
- Description: "400+ freeze-dried meals. All India delivery. From ₹100."
- **CTA Button: "Send WhatsApp Message"** ← This sends people directly to your WhatsApp

**Step 3.4 — Destination URL with UTM tracking:**
Use this URL in your ad (replace `fuelbox.in` with your actual domain):

```
https://fuelbox.in/?utm_source=instagram&utm_medium=paid&utm_campaign=fat_loss_reel
```

This way when someone visits from Instagram, their WhatsApp message will automatically say which ad brought them — you'll know which ad is working.

---

## STEP 4 — Instagram Ad URL formats

Use different UTM links for different ad campaigns so you know what's working:

| Ad Type | URL to use |
|---------|-----------|
| Reel — Fat Loss | `https://fuelbox.in/?utm_source=instagram&utm_campaign=fat_loss` |
| Reel — Protein goals | `https://fuelbox.in/?utm_source=instagram&utm_campaign=protein_reel` |
| Story — Burger/Pizza | `https://fuelbox.in/?utm_source=instagram_story&utm_campaign=food_story` |
| Bio link | `https://fuelbox.in/?utm_source=instagram_bio` |

---

## STEP 5 — Direct WhatsApp Ad (most powerful at low budget)

Instead of sending to website, run an ad with **"Send WhatsApp Message"** button:

- Go to Ads Manager → Create Campaign → Objective: **Messages**
- Choose **WhatsApp** as the messaging app
- Set your WhatsApp number: **+91 82830 87757**
- Pre-fill the message: "Hi! I saw your FuelBox ad. I want to know more about your meal plans."

**This is the most powerful option at ₹5,000 budget** — people click and land directly in your WhatsApp without going to any website.

---

## STEP 6 — Free Instagram Strategy (organic content)

Post daily using this formula:

| Day | Content type |
|-----|-------------|
| Mon | "I ate 150g protein this week without cooking" — show the packs |
| Tue | Pain point reel: "Why your gym isn't working" |
| Wed | Macro comparison: "FuelBox burger vs McDonald's" |
| Thu | Behind the scenes: freeze-drying or packaging |
| Fri | Customer review or before/after |
| Sat | "What's in a weekly pack" unboxing |
| Sun | Poll / question story — "Can you hit 150g protein today?" |

Always end every post/reel with: **"Link in bio — Order on WhatsApp ↗"**

---

## Quick checklist before going live

- [ ] Replace `YOUR_PIXEL_ID` in index.html with real Meta Pixel ID
- [ ] Update `og:url` meta tag to your actual domain
- [ ] Test all WhatsApp links on your phone
- [ ] Upload to Netlify / Vercel
- [ ] Add your domain
- [ ] Create Instagram Business account and connect to Meta Business Manager
- [ ] Set up Meta Pixel in Events Manager
- [ ] Run first test ad at ₹100/day for 3 days and check WhatsApp inquiries

---

**Your live URL will be:** https://fuelbox.in (or whatever domain you buy)
**WhatsApp:** +91 82830 87757

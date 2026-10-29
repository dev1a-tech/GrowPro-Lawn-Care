# GrowPro Lawn Care — Website

Concept one-page website for **GrowPro Lawn Care**, 49 Bryant St, Dartmouth, MA · 774-510-2165.
It's mobile-friendly, with click-to-call buttons, services, its 17 five-star Google reviews, a service area, FAQs and a free-estimate form.

![Website preview](screenshots/desktop.png)

## Live site

- **GitHub Pages:** https://YOUR-USERNAME.github.io/growpro-lawn-care/
- **Streamlit:** https://YOUR-APP-NAME.streamlit.app

## Files

| File | What it does |
|---|---|
| `index.html` | **The website.** Open it in any browser. GitHub Pages shows this file. |
| `build_site.py` | Python script that builds `index.html`. Edit the `CONFIG` section to change the text. |
| `app.py` | Streamlit version of the site. |
| `requirements.txt` | Packages Streamlit needs to install. |
| `screenshots/` | Preview images. |

> You don't need Python just to see the site. Double-click `index.html` (on a Mac, right-click → **Open With → Safari**).

## Run it on a Mac

Open **Terminal**, type `cd ` (with a space), drag this folder into the window, press Return, then run:

```
python3 build_site.py              # rebuilds index.html and opens it
pip3 install -r requirements.txt
python3 -m streamlit run app.py    # runs the Streamlit version
```

## Put it online

**GitHub Pages (best for the real business site, always on):**

1. Upload everything in this folder to a **public** repo named `growpro-lawn-care`.
2. Go to **Settings → Pages**, choose branch **`main`** and **`/ (root)`**, then click **Save**.
3. Wait 1–2 minutes. Your link appears at the top of that page.

**Streamlit (shows off the Python side):**

1. Go to **share.streamlit.io** and sign in with GitHub.
2. Click **Create app → Deploy a public app from GitHub**.
3. Repository `YOUR-USERNAME/growpro-lawn-care`, branch `main`, main file path **`app.py`**, then click **Deploy**.

## Before going live, confirm with the owner

Items marked `# CONFIRM` in `build_site.py` are placeholders:

- The services offered, towns served, "Free estimates," "Locally owned," "Reliable weekly service," and the FAQ answers
- Hours, ZIP code and email
- The Google Business Profile link for the reviews button
- Real customer review quotes (used with permission) in place of the placeholder
- Real lawn photos for the gallery
- A form service (such as Formspree) for the quote form. Until one is added, the form asks visitors to call.

## Built with

Python · HTML · CSS · Streamlit

---

*Concept site. Not yet the official website of GrowPro Lawn Care.*

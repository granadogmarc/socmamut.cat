MAMUT — Band Website
====================

PROJECT OVERVIEW
----------------
A single-page website for the band Mamut, built with plain HTML and CSS.
The site is in Catalan and designed as a full-screen scrolling layout
with six sections, each occupying the full viewport height.


COLOR PALETTE
-------------
Dark teal:   #263340  (hero, music, social sections)
Terracotta:  #9B3A29  (about, contact sections)
Cream:       #E5D9CE  (text, logos, streaming section background)


FONTS
-----
EB Garamond (Google Fonts) — elegant serif used for all body text.


FILE STRUCTURE
--------------
WEB_mamut/
  index.html                  — main (and only) HTML page
  css/
    styles.css                — all styles with explanatory comments
  Mamut_brand_pack/
    LOGO_PACK/
      Logotip/                — "mamut" wordmark in 5 color variants
      Isotiop/                — mammoth isotip icon in 5 color variants
      Icon/                   — additional icon variants
      imagotip/               — combined logo + icon versions
    IMATGES_PERFIL/           — profile images
    mamut_brand_guidelines.pdf
  fotos_mamut/
    wetransfer_mamut_finals_01-jpg_2024-12-31_1326/   — 21 band photos
    wetransfer_mamut_finals_21-jpg_2025-01-09_1759/   — 5 more band photos
    wetransfer_mamut_analogic_01-jpg_2025-01-21_1526/ — 7 analogue photos
    wetransfer_mamut_reel_1_2_3_2025-02-14_1643/      — 3 vertical video reels
  screnshots_web_mamut/       — 7 Canva mockup screenshots (reference)
  README.txt                  — this file


SECTIONS
--------
1. HERO (#hero)
   Background: dark teal
   Content: cream "mamut" wordmark logo
   Logo file: Mamut_brand_pack/LOGO_PACK/Logotip/logo_mamut_vector_all-05.png

2. ABOUT (#about)
   Background: terracotta
   Content: band photo strip (MAMUT_FINALS_12.jpg — staircase shot) +
            cream mammoth isotip icon + "som un grup de pop"
   Icon file: Mamut_brand_pack/LOGO_PACK/Isotiop/Isotip_mamut_vector_all-05.png

3. MUSIC (#music)
   Background: dark teal
   Content: Spotify artist embed + band photo (MAMUT_FINALS_09.jpg — blue sky, hands raised)
   *** TO DO: replace YOUR_ARTIST_ID in index.html with mamut's real Spotify artist ID.
       Go to Spotify → mamut artist page → "..." → Share → Copy link.
       The ID is the part after /artist/ in the URL.

4. STREAMING (#streaming)
   Background: cream
   Content: "aquí hi ha la nostra música" + Audiomack + Apple Music icon links
   *** TO DO: replace href="#" for both platform links with the real profile URLs.

5. SOCIAL (#social)
   Background: dark teal
   Content: "aquí ens pots trobar a nosaltres" + Instagram icon link
   *** TO DO: replace href="#" with mamut's real Instagram URL.

6. CONTACT (#contact)
   Background: terracotta
   Content: "i si ens vols contactar per que vinguem a tocar, és aquí" + email icon
   *** TO DO: replace mamutband@gmail.com in index.html with the real booking email.


HOW TO VIEW LOCALLY
-------------------
Open index.html directly in any browser:
  open /Users/marcgranadogonzalez/WEB_mamut/index.html

Or drag the file into a browser window.


PENDING TASKS
-------------
[ ] Add Spotify artist ID (index.html, line ~70)
[ ] Add Audiomack profile URL (index.html, streaming section)
[ ] Add Apple Music profile URL (index.html, streaming section)
[ ] Add Instagram URL (index.html, social section)
[ ] Add real contact/booking email (index.html, contact section)
[ ] Decide on hosting (e.g. GitHub Pages, Netlify, or a custom domain)


LOGO VARIANTS REFERENCE
------------------------
Each logo type comes in 5 color variants:
  Mesa de trabajo 1 — dark teal
  -02               — bright teal
  -03               — terracotta/orange-red
  -04               — dark brown/maroon
  -05               — cream/off-white  ← used on the website (dark backgrounds)

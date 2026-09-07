# Atabəy Rəcəbli landing page: launch checklist

1. Create a public GitHub repo (e.g. `olimpiada`). Upload `index.html` and `og.jpg` to its root. Every page image is already inside `index.html`.
2. Settings → Pages → Source "Deploy from a branch", branch `main`, folder `/ (root)`, Save. Live in 1-2 minutes at `https://<username>.github.io/olimpiada/`.
3. In `index.html` replace `https://SIZIN-SAYT-LINKI/og.jpg` (line 10) with your real link + `/og.jpg`, re-upload. This is the preview picture WhatsApp, Instagram and Telegram show when the link is pasted.
4. Open the live link on your phone from Instagram (bio link), not only from Chrome. Tap through one full quiz, send yourself the WhatsApp message, check the emoji and *bold* lines arrive clean.
5. Ads: destination = this link, objective Traffic (link clicks). There is no pixel on the page (by design, no tracking), so Meta cannot optimize for "conversions"; count conversions yourself: every message that starts with "Saytdakı sorğunu doldurdum" came from the site.

Automatic behaviour, nothing to touch:
- "Qeydiyyata N gün qalıb" recalculates on every page open, Baku calendar days. 19 Sep → "son gün: sabah", 20 Sep → "son gün: bu gün", from 21 Sep 00:00 Baku → "Qeydiyyat bağlanıb" on the top pill, the facts and every result card, and the price card keeps showing so parents still write for the next group.
- Phone back button closes the quiz instead of leaving the site.

Next cohort: change `DEADLINE`, `DEADLINE_TXT`, `START_TXT` (and `PRICE` if needed) in the CONFIG block at the top of the `<script>`, and the two "20 sentyabr / 21 sentyabr" lines in the "Necə keçir?" section.

# Vantage Recon — Free Self-Audit Web Tool (lead magnet)

A **100% client-side** OSINT self-audit page. Visitors type a username (optionally an email/name) and instantly get:
- an **account-footprint grid** across 60+ sites (clickable profile-check links), and
- **exposure-search** links (Google dorks for paste/leak sites, breaches, documents, people-search).

It runs entirely in the browser — **no backend, no API keys, nothing is sent or stored** — then funnels every visitor to your $19.99 Whop store. This is the "free value → buyers" inbound engine from the monetization plan.

Verified working locally (renders, runs, no console errors).

---

## Configure (2 lines, top of the `<script>` in index.html)
- `STORE_URL` — already set to `whop.com/vantage-osint/vantage-osint-lifetime-license`. Update if your store link changes.
- `FORMSPREE_ENDPOINT` — optional email capture. Leave `""` to disable. To collect emails: make a free form at https://formspree.io, copy its endpoint (`https://formspree.io/f/xxxx`), and paste it here.

---

## Put it live for FREE (GitHub Pages — same as your worldbestmodels site)
1. Create a new GitHub repo (e.g. `vantage-recon-audit`), **Public**.
2. Upload **`index.html`** to the repo root.
3. Repo **Settings → Pages → Source: `main` / root → Save**.
4. In ~1 min it's live at `https://<your-username>.github.io/vantage-recon-audit/`.
5. (Optional) point a custom domain or use a free short link.

**Preview locally anytime:** from this folder run `python -m http.server 5174` and open `http://localhost:5174`.

---

## How to use it for traffic
- Put the live URL in your **X / TikTok / IG / YouTube bios** as "🔎 free self-audit tool".
- It's the perfect **reply-grind asset**: under privacy/breach threads, "run a free self-audit on yourself" → link in bio.
- It's **shareable** (people audit themselves → tag friends), and earns **SEO/backlinks** over time.
- Every visitor sees the "2 of 25+ modules" CTA → your store. That's the funnel.

> Ethical framing is built in (authorized/self-audit only). Keep it that way — it's both the right call and what keeps it from getting flagged.

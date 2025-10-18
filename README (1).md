# PracIns — DS360 Mini‑Apps (Starter Pack)

This repo contains three static files you can host anywhere (GitHub Pages, Netlify, etc.).

## Files
- `index.html` — Hub/launcher with tiles and prebuilt trial links
- `pizza-order.html` — Weekday pizza order form (name, qty, day, note → WhatsApp)
- `quick-whatsapp-form-pracins.html` — Clean generic WhatsApp form (title + notice + message)

## How to use
1. Upload all three files to a static host.
2. Share the hub: `index.html`.
3. Change target numbers or titles with URL params:
   - `&phone=5999XXXXXXX` — WhatsApp number (digits only)
   - `&org=PracIns` — Organizer name
   - `&title=My%20Title` — Page title
   - `&notice=Promo%20or%20purpose%20text` — Notice banner
   - `&cta=Send%20Now` — Button text
   - `&header=🧾%20MESSAGE` — First line of WhatsApp message

## Example
```
quick-whatsapp-form-pracins.html?title=Watermeter&notice=Send%20today%27s%20reading&org=PracIns&phone=59995120536
```

---

© PracIns — Practical Instructions | contact@pracins.com

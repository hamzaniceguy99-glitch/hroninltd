# HRONIN — hronin ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `hroninltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/hroninltd.mjs`).
> To change the content, edit that file and run `node build.mjs hroninltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@hroninltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Per item / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
HRONIN LTD manufactures plastic products and retails games and toys from London, both in store and online, and was formed in December 2024. Being new, we claim no history we do not have — what we can point at is the paperwork, which in this trade is the whole of the safety argument. A toy placed on the UK market must have a documented safety assessment, a technical file, a declaration of conformity and UKCA marking, and where we manufacture, that duty is ours rather than a supplier's. Small parts mean an under-three warning stating the actual hazard rather than a generic age label, and chemical migration and flammability are tested against the relevant standards. Toys are also marked so a batch can be traced if anything ever needs recalling. Site: hroninltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |

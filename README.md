
# Kids Safety Contact Page (Open-Source Template)

> A minimal, multilingual, theme-aware static page you can host anywhere (GitHub Pages, Netlify, Vercel). Designed for **one job**: if a child gets lost, the finder scans a QR code and sees clear instructions to contact you.

**This repo contains the *template only*. Do not commit personal information here.**

## Quick start

1. Download this repository as a ZIP or clone it.
2. Replace placeholder content in `index.html` (names, numbers, WhatsApp links, etc.).
3. Deploy:
   - **GitHub Pages**: enable Pages on the repository (Build from `GitHub Actions`), push; the included workflow will publish automatically.
   - **Netlify/Vercel**: drag-and-drop or connect the repo.
4. Generate QR codes that point to your deployed URL (examples below). Print and attach to bags/shoes/wristbands.

## Safer defaults (strongly recommended)

- **Minimal PII**: Show a single *click-to-call* number or WhatsApp link. Avoid last names, addresses, schools, birth dates, or schedules.
- **Alias phone**: Use a dedicated eSIM/alias/VoIP number (Google Voice, etc.).
- **Verification**: Add a short shared passphrase so the caller can confirm they are with the child (e.g., “What's the favorite animal?”).
- **Rotation**: If you publish a URL in a QR, prefer a short redirect you control (Bitly/own domain). You can rotate destinations without reprinting.
- **No tracking**: Disable analytics or keep it privacy-friendly if you must (e.g., Plausible with IP anonymization).

## Multilingual & theme

- Page supports Light/Dark/Auto and English/Hebrew out of the box. Use **T** to toggle theme and **L** to toggle language.
- The page is responsive and print-friendly. Floating controls remain readable in all modes.

## QR code examples

Create a QR code for your final URL, e.g.:

- `https://YOUR-DOMAIN.example/#home`
- Direct call: `tel:+9725XXXXXXXX`
- WhatsApp: `https://wa.me/9725XXXXXXX?text=Found%20a%20child%2C%20please%20help`

You can use any QR generator. For convenience, open `tools/qr_generator.html` (runs locally) to generate and print multiple labels.

## License

MIT — see `LICENSE`. Contributions welcome; please avoid adding real personal data to PRs.

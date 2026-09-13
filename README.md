# paper-aisle

A FreeWebStore template for **business.lifestyle** by **@Aa11rn**.

# The Paper Aisle — Save the Date, Make the Card

An elegant, mobile-first, single-page bridal invitation-card studio
template: ivory and blush surfaces, champagne-gold accents, an elegant
Cormorant Garamond display serif, and SVG-only artwork.

## Features

- Announcement ribbon with cycling season notes, live guest counter, pause + dismiss
- Sticky nav with gold "Save the Date" CTA + mobile drawer menu
- Hero with compact countdown, status chip, and wax-seal emblem
- Card Studio: four invitation designs with palette and mood badges
- Animated count-up statistics band
- Save-the-Date centerpiece: threading countdown (days / hours / minutes / seconds)
- Save-the-Date form: validated email + reminder channels (SMS / Email / WhatsApp),
  loading, success, duplicate-email, and reset states with a persisted guest
  counter + social-proof avatar stack
- Add-to-my-calendar export (.ics) with a clipboard fallback for older phones
- Atelier help cards and share tools (copy-link + social intents)
- Scroll-reveal animations with prefers-reduced-motion support
- Toast notifications, mobile Save bar, and back-to-top
- Fully slot-annotated (`data-fws-slot`) for FreeWebStore content editing

## Included Files

```
paper-aisle/
├── index.html            # Main template page
├── package.json          # Node dependency file (FWS CLI)
├── template.config.json  # FWS template metadata
├── tailwind.config.js    # Tailwind design tokens reference
├── preview.png           # Template preview image (add your own)
└── README.md             # This file
```

## Customization

All editable content regions are marked with `data-fws-slot` attributes. Edit
these directly in the HTML or via the FreeWebStore editor after publishing.
See `slots.md` for the slot reference used by this template.

## Publishing

```sh
npx @freewebstore/cli doctor     # local validation
npx @freewebstore/cli login      # one-time GitHub App install
npx @freewebstore/cli publish    # upload + create repo + queue for review
```

## License

MIT (auto-set by `fws init`). FreeWebStore requires MIT for community
templates — see CONTRIBUTING.md in the platform docs for the why.
MIT — see `template.config.json` for details.
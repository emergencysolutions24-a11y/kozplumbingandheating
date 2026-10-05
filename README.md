# KOZ Plumbing & Heating — Editable Build

## Business details

To change the phone number, email address, company name or address across the whole website, edit `SITE_CONFIG` at the top of `script.js`.

```js
const SITE_CONFIG = {
  companyName: 'KOZ Plumbing & Heating Ltd',
  phoneDisplay: '074 047 517 87',
  phoneLink: '07404751787',
  email: 'info@koz-plumbing.co.uk',
  address: [
    '1 Whitewater Court',
    '12 Mills Grove',
    'London',
    'NW4 1DF'
  ]
};
```

The HTML also contains readable fallback values, so it remains easy to edit manually.

## Run locally

```bash
python3 -m http.server 5173
```

Open `http://localhost:5173`.

## Files

- HTML pages contain the actual website content and layout.
- `styles.css` contains all visual styling and responsive rules.
- `script.js` contains business configuration plus UI behaviour/animations.
- `assets/images/` contains the supplied plumbing and heating images.

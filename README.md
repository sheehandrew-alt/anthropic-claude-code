# FlowWise Irrigation & Automation

Marketing website for a new irrigation company specializing in installing,
servicing, and selling smart irrigation automation (Wi-Fi controllers, soil
sensors, smart valves, and leak/flow monitors) for residential and
commercial properties.

## Structure

- `index.html` — single-page site: hero, services, products, why-us, testimonials, contact
- `css/style.css` — styling (responsive, mobile nav)
- `js/main.js` — mobile nav toggle, footer year, client-side contact form handling

## Running locally

This is a static site with no build step. Open `index.html` directly in a
browser, or serve the directory, e.g.:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Customizing

Update the placeholder phone number, email, and service area in
`index.html` (header and `#contact` section), and swap in real pricing,
product details, and testimonials before launch. The contact form currently
only confirms submission client-side — wire it to an email service or
backend endpoint to actually receive leads.

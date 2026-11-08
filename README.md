# Regenta Resort Vanya Mahal

A responsive single-page website concept and browser-based demo CRM for Regenta Resort Vanya Mahal in Ranthambore.

## Overview

The page includes resort information, stay and experience sections, contact details, enquiry forms, and a guest relationship dashboard for tracking leads and bookings. Form submissions and dashboard changes are stored in the browser's `localStorage` for demonstration purposes.

## Features

- Responsive resort landing page with story, stay, experiences, and contact sections.
- Enquiry form and booking modal.
- Demo CRM dashboard for guest leads and order/booking tracking.
- Search and relationship-status updates for guests.
- Order status filters and inline updates.
- Browser-local persistence using `localStorage`.

## Run locally

This is a static HTML demo and does not require a build step.

1. Clone or download the repository.
2. Open `index.html` in a modern web browser.

If you prefer to serve it locally, run a static HTTP server from the project directory, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Important demo limitations

- CRM records are stored only in the current browser and device. They are not shared across users and may be cleared with browser data.
- Enquiries are not sent to the hotel. A secure backend and service integrations are needed for real enquiry delivery, multi-user updates, payments, notifications, or PMS/POS integration.
- Verify contact details and all resort information before publishing.
- The CRM login control is a demo navigation feature, not authentication. Do not enter or store real guest data in this demo.

## Project contents

- `index.html` — complete static site, styles, and demo CRM logic.

## License

No license has been specified for this project.

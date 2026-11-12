# HostelHub

A responsive, browser-based hostel marketplace prototype for borrowing, renting,
selling, and rescuing items within a hostel community.


The entry point is `index.html`; no build step or package installation is required.

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static-file
server.

## Important prototype limitations

- This is a static front-end prototype. It does not include a server, database,
  authentication, or real-time multi-user synchronisation.
- App state is stored in the visitor's browser, so data is local to that browser
  and device.
- Any sample listings, neighbour activity, requests, and transaction flows are
  simulated by the front end; they are not real bookings or payments.
- Google Fonts are loaded from Google Fonts. If unavailable, system font fallbacks
  are used.

To support real hostel-wide accounts and shared listings, connect the interface
to a backend service and implement authentication, database rules, and server-side
transaction handling.

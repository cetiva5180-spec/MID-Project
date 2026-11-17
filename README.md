# PaaniLink — Frontend Prototype

A responsive frontend-only academic prototype for the Water Tanker Booking and Dispatch System.

## Run the project
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Sign in using one of the demo accounts below.

No Node.js, database, backend server or installation is required.

## Demo accounts
All passwords: `demo123`

| Role | Email |
|---|---|
| Administrator | admin@paanilink.demo |
| Customer | customer@paanilink.demo |
| Zone Officer | officer@paanilink.demo |
| Hydrant Operator | operator@paanilink.demo |
| Driver | driver@paanilink.demo |

## Included functionality
- Role-based navigation and dashboard views.
- Customer booking creation, validation, price estimate and cancellation.
- Subsidy application and officer/admin approval or rejection.
- Hydrant quota and availability management.
- Tanker registration and availability changes.
- Operator tanker/driver assignment and booking status updates.
- Driver trip status updates.
- Booking search, status/type filters and CSV export.
- Reports, customer directory, bills and disputes.
- Browser `localStorage` persistence and notification demo.

## Technology
- HTML5
- CSS3 (Grid, Flexbox and responsive media queries)
- Vanilla JavaScript
- Browser localStorage and sessionStorage for mock data

## Important academic note
This is a frontend prototype. Login is simulated and is not secure authentication. Data is stored in the current browser only. No real booking, payment, CNIC verification, GPS tracking, SMS, API or database connection is performed.

## Suggested viva explanation
The user submits a form; JavaScript validates it; the app updates its mock data object; `localStorage` persists the updated state; the page re-renders the relevant table and dashboard. In the backend phase, the local data functions can be replaced with `fetch()` calls to API endpoints while keeping the UI structure.

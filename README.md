# Cab booking

A React page for choosing a car and filling in a rental form. A running copy is at https://cab-booking-nouviex.netlify.app/

The bar and one route, `/`, come from `src/App.js`. Home is a hero, the booking form, and a fleet picker. The bar also links to `/about`, `/models`, `/testimonials`, `/team`, and `/contact`. Those routes are not defined, so only the bar renders. Sign In and Register both go to `/`. The hero’s book button scrolls to the form.

The form needs a car, a pick-up, a drop-off, and two dates. The cars are Audi A1 S-Line, VW Golf 6, Toyota Camry, BMW 320 ModernLine, Mercedes-Benz GLK, and VW Passat CC. Pick-up and drop-off share one Bengaluru list: Basavanagudi, Bannerghatta Road, Indira Nagar, Electronic City, Jayanagar, Kengeri, Malleshwaram, Hosur Road, and Rajajinagar. Search with any of those empty shows “All fields required!”. A complete form opens a dialog for first name, last name, phone, age, email, address, city, and zip code. Confirm closes the dialog and shows “Check your email to confirm an order.” The values stay in component state.

Under the form, the same six cars are buttons. The selected one shows its photo and the price, model, transmission, and the rest of the fields in `src/components/CarData.js`.

## Run

```bash
npm install
npm start
```

`start` runs the Create React App dev server.

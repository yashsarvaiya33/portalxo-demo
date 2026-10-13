# Portal XO Game Zone — Booking Demo

Live: https://demo.portalxogamezone.fertiletech.co.in
Admin: https://demo.portalxogamezone.fertiletech.co.in/#admin (demo login: `admin` / `portal123`)

Single-file web app (index.html) built by Fertile Tech as a client demo.
- **Player app**: phone + OTP login, profile (name, phone, email, birthdate), game-aware slot booking, Elite Pass hours, WhatsApp confirmation preview.
- **Admin app**: live PS5 board with timers, walk-ins, phone bookings, whole-hour extensions with clash protection, billing (Cash/UPI, Elite hours), players & Elite Pass sales, reports, settings (PS5s, games per PS5, pricing, hours, admin login).

Demo limits: data is stored in the browser (localStorage) per device; OTP and WhatsApp messages are simulated. The production build needs a backend, an SMS OTP provider and the WhatsApp Business API.

# Found fishing gear page

Lost property page opened when someone taps the NFC tag on a buoy written by the Buoy Tracker app.

The tag link carries the owner details after the `#`, e.g.
`https://bluelobsterfishing.github.io/found/#B001*Morning+Star*PD417*name@example.com*Reward+if+returned`
(float, boat, registration, contact, comments; `*` separates fields, `+` = space).

Browsers never send the part after `#` to the server, and the page has no forms,
analytics or cookies, so nothing is stored.


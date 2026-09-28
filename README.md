# visitors

School visitor registration page (Arabic, right-to-left).

`index.html` is a static page. It sends registrations and departures to the
school's Google Apps Script backend with cookie-free `fetch` requests
(`credentials: 'omit'`), so it works in a normal browser even when several
Google accounts are signed in. It contains no visitor data; records are kept
only in the school's private Google Sheet.

- Registration: `https://isharataljasad.github.io/visitors/`
- Departure: `https://isharataljasad.github.io/visitors/?p=out`

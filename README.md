# Ekatra

**A unified citizen gateway that links government services through one sign-in and consent-based data sharing.**

[Live demo](https://ekatra-tech.web.app/)

Citizens today re-upload the same documents and repeat e-KYC on every government portal. Ekatra is a prototype interoperability layer that lets citizens, businesses and departments share verified data without rebuilding existing systems.

## Features

- Single sign-on backed by DigiLocker and Aadhaar, so e-KYC is done once
- Consent-based data sharing between departments, with every access logged
- One dashboard to track applications across linked portals
- Role-based views for citizens, officials and IT teams
- SMS and WhatsApp status alerts (designed)

## Built with

HTML, CSS, JavaScript, Firebase Authentication, Cloud Firestore, Firebase Hosting

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

To use your own Firebase project, replace the values in `firebase-config.js`.

> Independent student prototype. Not affiliated with or endorsed by any government body.

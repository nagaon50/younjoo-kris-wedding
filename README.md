# Younjoo & Kris — Wedding Weekend

A mobile-first, responsive bilingual wedding invitation for 15–16 October 2027 in Jeju, South Korea.

## Features
- Korean / English language toggle
- Responsive navigation and long-scroll editorial layout
- Event venue links and Google Maps routes
- Separate calendar downloads for Welcome Dinner and Wedding Ceremony
- FAQ accordion
- RSVP form that prepares an email to YounjooKris@gmail.com

## RSVP status
This public prototype does not store RSVP data. The form opens a pre-filled email draft, and guests must send the email themselves. Do not treat the form as a completed RSVP until a secure backend and guest response dashboard are connected.

## Before the final invitation launch
- Confirm all venue and accommodation details with the organisers.
- Confirm photo usage rights and replace any reference images with approved photography.
- Confirm additional-night pricing basis, room allocation, and booking process.
- Confirm wet-weather ceremony arrangements.
- Add secure RSVP storage, privacy notice, and organiser-only access.

## Deployment
The GitHub Actions workflow in `.github/workflows/pages.yml` deploys this static site to GitHub Pages on pushes to `main`, once Pages is enabled for the repository.

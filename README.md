# OrganEase

OrganEase is a web app that makes organ donation and transplant coordination faster and simpler.

## The problem
Requesting organs today is mostly manual: data entry, phone calls, faxes and emails to many centres, one by one. Organs can only survive outside the body for a limited time, so delays cost lives.

## What OrganEase does
- Procurement and transplant centres list the organs they have in storage.
- Hospitals see all available organs in one place and send requests.
- Payment works as a confirmation token, and the centre then confirms the request.

## AI features
- **Smart matching:** ranks organs for each request by blood group, urgency, size and distance.
- **Time-left tracking:** shows how long each organ can still be used.
- **Delivery check:** estimates travel time and checks the organ can arrive in time.
- **Help chatbot:** answers questions and fills forms from uploaded reports.

AI only gives suggestions. A medical professional always makes the final decision.

## Tech stack
React, Node.js, Express, MongoDB Atlas, Claude API, Maps API

## Getting started
1. Install Node.js and create a MongoDB Atlas cluster.
2. Copy `.env.example` to `.env` and add your keys.
3. Run `npm install` in both `client` and `server`.
4. Start the server (`npm run start:dev`), then the client (`npm start`).
5. Open http://localhost:3000

## Note
This is a prototype and not a certified medical system. Use sample data only, not real patient data.

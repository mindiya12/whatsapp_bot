WhatsApp Bike Info Bot (n8n + Twilio)
Simple WhatsApp bot built with n8n, Twilio WhatsApp, and Google Sheets to send bike details when a user replies with a number.

How it works
User sends hi (or menu) on WhatsApp.

Bot replies with a main menu listing bikes 1–6 and 7 for agent.

User replies with a number:

1–6: bot reads that bike’s row from Google Sheets and sends full details (price, availability, specs, features, fuel, financing).

7: bot replies with agent contact info.

All bike data is managed in Google Sheets, so non‑technical users can update content without changing the workflow.

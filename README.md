# Nino Kitchen & Bar — Telegram Mini App

A Telegram Mini App for **Nino Kitchen & Bar** in Astana. Guests can browse the menu and book a table without leaving Telegram.

## Features
- 🍽️ **Menu** grouped by category, with dish names and prices in tenge
- 📅 **Table booking** form: name, phone, date, time slot (12:00–22:00) and number of guests
- Booking is sent to the bot with `Telegram.WebApp.sendData`, with a confirmation message for the guest
- 📞 **Contacts** page: phone, opening hours and Instagram
- Bottom navigation between pages; the app expands to full height inside Telegram
- Mobile-first design in an elegant cream, charcoal and gold style

## Tech
HTML · CSS · JavaScript · [Telegram Web Apps API](https://core.telegram.org/bots/webapps) — a single `index.html` file with no build step or dependencies.

## Run
Open `index.html` in a browser to preview, or set its hosted URL as the Web App URL of a Telegram bot (via @BotFather).

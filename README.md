# JDRAN Enterprises Ltd

**Building Dran POS — an offline-first, AI-assisted point-of-sale suite for UK independent retailers and takeaways.**

Independent shops run on thin margins with tills that record sales and do nothing with them. Dran POS puts the intelligence larger chains pay enterprise prices for — demand forecasting, data-driven purchasing, basket-level upsell, an AI phone receptionist — directly on the shop's own hardware, working with or without an internet connection.

## The suite

| Application | What it does |
|---|---|
| 🏪 **Dran POS (Convenience)** | Convenience-store till: billing, stock, demand forecasting, purchase-order automation, price intelligence — Android & Windows |
| 🍔 **Dran POS Takeaway** | Takeaway till: orders, kitchen display, AI upsell & combos, weather-calibrated forecasting — Android & Windows |
| 📞 **Dran POS Receptionist** | AI phone receptionist that answers calls, takes orders and sends them straight to the till |
| 🍳 **DRAN KDS** | Kitchen display — pair any tablet to the till and bump orders with a tap |
| 📋 **Dran POS Assist** | Back-office companion: purchase orders, stock updates and AI invoice scanning on a second device |

## How we build

- **Offline-first** — the till, forecasting and upsell engines run entirely on-device; connectivity only ever adds features
- **On-device intelligence** — basket mining and demand models learn from the shop's own history; sales data never leaves the device
- **Privacy by design** — UK GDPR-first engineering: consent-gated storage, encrypted credentials, minimal data collection
- **Local-network coordination** — till, kitchen display, receptionist and back-office pair over the shop's own WiFi, no cloud required

## Stack

`Android (WebView)` · `Electron` · `Node.js / Fastify` · `PostgreSQL (row-level security)` · `Python / Pipecat` · `Twilio` · `Anthropic Claude` · `Stripe`

---

📫 **Contact:** www.jdranenterprises@gmail.com


# ⚡ PGSAccount — Pokémon GO Multi-Tenant Account Manager

> **Live Web App**: [https://pogo-app-pro.azurewebsites.net/](https://pogo-app-pro.azurewebsites.net/)  
> A real-time, multi-tenant web dashboard designed to manage, monitor, and inspect Pokémon GO accounts, shiny collections, IV appraisals, item bags, and PvP rankings seamlessly.

[![Live Demo](https://img.shields.io/badge/Live_App-pogo--app--pro-2563EB?style=for-the-badge&logo=azure)](https://pogo-app-pro.azurewebsites.net/)
[![Telegram](https://img.shields.io/badge/Telegram-@Joyboy__2106-2CA5E0?style=for-the-badge&logo=telegram)](https://t.me/Joyboy_2106)
[![Platform](https://img.shields.io/badge/Platform-Web-success?style=for-the-badge)]()
[![Pokedex](https://img.shields.io/badge/Pokédex-Gen_1--9-orange?style=for-the-badge)]()

---

## 🌟 Key Highlights

* **🔄 Automated Real-Time Sync**: Ingests Pokémon inventory, item bags, levels, badges, Stardust, and PokéCoins automatically on every in-game login.
* **🛡️ Multi-Tenant Privacy**: Every user gets a private webhook token (`/api/webhook/<token>`) and can only see their own accounts.
* **📊 Complete Gen 1–9 Pokédex**: Automatic species resolution, accurate sprite rendering, and elemental typing.
* **🎯 Exact IV & Level Calculator**: Attack, Defense, and Stamina appraisal breakdown (0–100% IV) alongside accurate Level 1–50+ calculation.
* **⚔️ PvP Great & Ultra League Rankings**: Instantly highlights optimal PvP stat-products for Great League (≤1500 CP) and Ultra League (≤2500 CP).
* **🏷️ Smart Tag Filters**:
  * ✨ **Shinies** & 🌟 **Shundos** (100% IV Shiny)
  * 💯 **Hundos** (100% IV)
  * 📍 **Location Cards (BG)** & Event Memorabilia
  * 🎭 **Costumes** & Special Regional Event Forms
  * 💀 **Shadow** & 🔮 **Purified**
  * 🍀 **Lucky Pokémon**
  * 👑 **Legendaries, Mythicals & Ultra Beasts**
* **🎒 Full Item Bag Inspection**: Exact counts and icons for Poké Balls, Berries, Evolution Items, TMs, Raid Passes, and Incenses.

---

## 📋 Requirements

> [!IMPORTANT]
> To use the live synchronization feature, you must have **PGSharp Standard / Premium Edition**, as the *Export Account Data* feature is available on paid PGSharp versions.

---

## 🚀 How to Set Up & Connect PGSharp (Step-by-Step)

### Step 1: Get Your Webhook Link
1. Visit the web app: [https://pogo-app-pro.azurewebsites.net/](https://pogo-app-pro.azurewebsites.net/)
2. Register an account or log in with your credentials.
3. Open your **Profile** in the dashboard and copy your personal **Webhook URL**:
   ```text
   https://pogo-app-pro.azurewebsites.net/api/webhook/<your_unique_token>

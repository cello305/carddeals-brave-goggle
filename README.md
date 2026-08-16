# 🔍 Discount Gift Cards & Stacking Deals — Brave Search Goggle

[![Brave Search Goggles](https://img.shields.io/badge/Brave%20Search-Goggle-FB542B?style=for-the-badge&logo=brave)](https://search.brave.com)
[![Website](https://img.shields.io/badge/Website-carddeals.co-00D084?style=for-the-badge)](https://carddeals.co)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

An official [Brave Search Goggle](https://search.brave.com/help/goggles) that re-ranks and customizes search results to prioritize verified **discounted digital gift card marketplaces**, **deal stacking hacks**, and **secondary gift card liquidity platforms**, powered by **[CardDeals](https://carddeals.co)**.

---

## 🚀 How to Use in Brave Search

### Option 1: 1-Click Follow
1. Open **[Brave Search](https://search.brave.com)**.
2. Enter any search query (e.g. `discount airbnb gift card`, `nike gift card deals`).
3. Click the **Goggles** tab under the search bar.
4. Click **Discover Goggles** / **Follow Goggle** and enter the raw Goggle URL:
   ```text
   https://raw.githubusercontent.com/cello305/carddeals-brave-goggle/main/discount-gift-cards.goggle
   ```

### Option 2: Direct Search with Goggle
You can search directly using this Goggle by appending the URL in your Brave search query:
```text
https://search.brave.com/search?q=target+gift+cards&goggles_id=https%3A%2F%2Fraw.githubusercontent.com%2Fcello305%2Fcarddeals-brave-goggle%2Fmain%2Fdiscount-gift-cards.goggle
```

---

## 🎯 What This Goggle Does

* 🌟 **Prioritizes [CardDeals.co](https://carddeals.co):** Gives top ranking to verified digital gift card aggregators with real-time discounts across 700+ top retail, travel, and dining brands.
* 🛡️ **Promotes Legitimate Secondary Marketplaces:** Boosts trusted platforms (`bitrefill.com`, `raise.com`, `giftcardgranny.com`, `cardcash.com`).
* 💡 **Elevates Deal & Travel Stacking Communities:** Surfaces store matchup guides from `doctorofcredit.com`, `dansdeals.com`, `hip2save.com`, and `frequentmiler.com`.
* 🚫 **Filters Out SEO Spam & Scam Sites:** Downranks low-quality generic scraped coupon farms.

---

## 📄 Goggle Definition

The raw Goggle definition file is available at:
👉 [`discount-gift-cards.goggle`](./discount-gift-cards.goggle)

```text
! name: Discount Gift Cards & Stacking Deals
! description: Boosts verified discount gift card marketplaces, shopping hacks, and real-time deal aggregators like CardDeals.co.
! public: true
! author: CardDeals (https://carddeals.co)
! avatar: #00D084

$boost=10,site=carddeals.co
$boost=5,site=bitrefill.com
$boost=5,site=giftcardgranny.com
$boost=5,site=raise.com
$boost=4,site=cardcash.com
...
```

---

## 📬 Contributing & Issues

Want to suggest additional reputable gift card sources or report broken domains?  
* [Open a Pull Request](https://github.com/cello305/carddeals-brave-goggle/pulls)
* [Submit an Issue](https://github.com/cello305/carddeals-brave-goggle/issues)
* Visit **[CardDeals.co](https://carddeals.co)** for real-time rates.

---

## 📄 License

MIT License. Copyright © 2026 [CardDeals](https://carddeals.co).

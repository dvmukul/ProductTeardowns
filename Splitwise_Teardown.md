# Splitwise Teardown

## 📱 1. Product Overview & Positioning
* **Product Name:** Splitwise
* **Platform/Version Evaluated:** Web & Mobile Application (General Overview)
* **Target Audience:** Young adults, students, couples, roommates, and travelers (aged 18-35) who frequently share expenses and need a transparent way to track finances.
* **Value Proposition:** Splitwise acts as a neutral third-party ledger that takes the stress and awkwardness out of shared expenses. It differentiates itself with multi-currency support, a simple interface, and its powerful "debt simplification" algorithm.
* **Market Context:** Personal finance and expense sharing is highly competitive, facing direct pressure from P2P payment apps (Venmo, PayPal) and neo-banks/traditional banks (Monzo, Revolut, Chase) that are building native bill-splitting features. However, Splitwise remains the dominant standalone app specifically for tracking ongoing shared expenses over time.

## 🎯 2. Core User Jobs-to-be-Done (JTBD)
* **Job 1:** When I am taking a trip with friends, help me track shared costs across different currencies so we don’t have to do mental math at the end of the trip.
* **Job 2:** When I live with roommates, give me a transparent ledger for rent and utility bills so we can settle up fairly every month.
* **Job 3:** When I am in a relationship, help me seamlessly split groceries and dinners without constantly sending money back and forth.
* **Emotional vs. Functional Jobs:** 
  * *Functional:* Tracking debts, calculating uneven splits, converting currencies, and recording payments.
  * *Emotional:* Eliminating the awkwardness of asking friends for money, preserving relationships by being a neutral arbiter, and feeling organized and in control of personal finances.

## 🎨 3. Key UX Decisions and Why
* **Onboarding Experience:** The sign-up is quick, heavily emphasizing contact list integration. This is necessary because Splitwise is inherently a multi-player app; users must be able to invite their friends quickly to reach the "Aha!" moment of logging a shared expense.
* **Core Loop:** The primary loop revolves around creating a group/friend, adding an expense, selecting the split method (equal, percentages, exact amounts), and saving. The app then instantly updates the balance. It is engaging because it provides immediate clarity and updates the central dashboard.
* **Brilliant Design Choices:** The "Simplify Debts" feature is a standout. Behind the scenes, the algorithm minimizes the total number of transactions needed to settle a group (e.g., if A owes B $10, and B owes C $10, A just pays C $10). Visually, the dashboard neatly categorizes into "You are owed" and "You owe."
* **Friction Points:** Splitwise recently added a harsh restriction of 3 free transactions per day before showing 10-second video ads. This severely disrupts the core loop for active users. Additionally, navigating between multiple large groups to find a specific historical expense can feel clunky, and the overall aesthetic feels slightly dated.

## ⚙️ 4. Business Model Mechanics
* **Monetization Strategy:** Splitwise operates on a freemium model. Core tracking is free, but they heavily push "Splitwise Pro" for ad-free usage, receipt scanning, currency conversion, and charts. Recently, they introduced aggressive ads and transaction limits for free users to boost premium conversion.
* **Acquisition/Growth Loops:** Growth is highly viral and organic. When one person creates a group (e.g., for a bachelor party), they must invite the other attendees to the app. This creates a powerful word-of-mouth and network-effect growth loop.
* **Retention Hooks:** The product is incredibly sticky for roommates and couples because leaving the app means migrating an ongoing financial history. The dashboard acts as a continuous ledger that keeps users checking their balances.

## 💡 5. Recommendations & Takeaways
* **Quick Wins (Low Effort, High Impact):** 
  * Re-evaluate the 3-transaction daily limit for free users. A less intrusive monetization strategy (like limiting the number of active long-term groups or charging for high-volume groups) might preserve user goodwill while still driving Pro conversions. 
  * Refresh the UI to look more like a modern fintech app (glassmorphism, updated typography).
* **Strategic Bets (High Effort, High Impact):** 
  * Deepen native payment integrations globally (similar to their Tink partnership in the UK) so users can settle up instantly within the app, effectively taking a small transaction fee or keeping users in the ecosystem. 
  * Add financial planning features for couples, moving from just "splitting" to "collaborative budgeting".
* **Biggest Risks/Threats:** The largest existential threat is the "unbundling" of this feature by major banking apps and P2P networks. If Venmo, Zelle, or Apple Cash perfects ongoing group expense tracking within their native apps, the need for a standalone app like Splitwise will diminish.

# Swiggy Product Teardown
### A PM-style product analysis by Mrunal Ghode

---

## 1. What is Swiggy?

On-demand food and grocery delivery platform connecting users 
to restaurants and dark stores across India.

**Monetisation:** Delivery fees, restaurant commissions, 
Swiggy One subscriptions, and in-app ads.

---

## 2. Key Metrics

| Metric | Value |
|---|---|
| Orders per month | ~11 million |
| Average delivery time | ~30 minutes |
| Average order value | ~₹420 |
| Orders per user per month | ~2.8x |
| Repeat order rate | ~60% |
| North star metric | DAU/MAU ratio |

---

## 3. User Segments

### 🧑‍💼 The Busy Professional
- Age: 22–35, metro cities
- Orders 4–6x per week
- Values speed over price
- Highest lifetime value (LTV)
- **Primary target segment**

### 👨‍👩‍👧 The Weekend Family
- Orders 1–2x per week
- Large basket size
- Price-sensitive, coupon-driven
- Occasion-based ordering

### 🎓 The College Student
- Extremely price-sensitive
- Late-night orders
- Influenced by offers and peer behaviour
- Orders from PGs and hostels

### 🛒 The Instamart User
- Orders groceries in 10–15 minutes
- High frequency, lower basket
- Fastest growing segment

---

## 4. Core User Journey

| Step | Action | Stage |
|---|---|---|
| 1 | Open app → personalised home feed | Discovery |
| 2 | Browse restaurant → add items to cart | Consideration |
| 3 | Checkout → coupon → address → payment | ⚠️ Drop-off risk |
| 4 | Real-time tracking: restaurant → DE → door | Delivery |
| 5 | Rate order → re-order nudge → cashback | Retention |

---

## 5. User Pain Points

### 🔴 High Severity
- **Delivery time longer than estimated** — kills trust, 
drives cancellations
- **Surge pricing with no explanation** — feels unfair 
and opaque at checkout

### 🟡 Medium Severity
- **Irrelevant push notifications** — causes app fatigue 
and uninstalls
- **Coupon discovery is buried** — users find offers only 
after frustration

### 🟢 Low Severity
- **Group ordering is clunky** — no native way to split 
bills with friends

---

## 6. PM Opportunities

### Opportunity 1 — Predictive Reorder (Retention)
**Problem:** Users have to search for their favourite order 
every time.

**Solution:** Use order history to predict what a user wants 
before they open the app. One-tap reorder on the home screen.

**Success metric:** Orders per user per month

---

### Opportunity 2 — Live ETA Confidence Intervals (Trust)
**Problem:** Swiggy shows one optimistic delivery time. 
When it's wrong, trust breaks.

**Solution:** Show a delivery time range ("25–35 min") 
instead of a single number. 

**Success metric:** CSAT score and cancellation rate

**MVP approach:** Just show a range — no ML model needed 
to start. Ship in 1 sprint.

**Risk:** Over-engineering. Mitigated by keeping MVP simple.

---

### Opportunity 3 — Group Cart (Growth)
**Problem:** Friends ordering together have to coordinate 
manually and one person ends up paying.

**Solution:** Share a live cart link. Everyone adds their 
items. Payment splits automatically.

**Success metric:** New user acquisition and average 
basket size

---

## 7. Interview Answer Framework

If asked "How would you improve Swiggy?" in an APM interview:

**Step 1:** "Swiggy's north star metric is orders per 
active user per month"

**Step 2:** "I'll focus on the busy professional — 
highest LTV"

**Step 3:** "Their biggest pain is delivery time uncertainty"

**Step 4:** "I'd build live ETA confidence intervals — 
measured by CSAT and reorder rate"

**Step 5:** "Risk is over-engineering — MVP is just 
showing a range, not a full ML model"

---

## 8. What I Learned

- Always anchor your analysis to the north star metric
- Pick one user segment and go deep — never solve for everyone
- The best PM opportunities sit at the intersection of 
user pain and business metrics
- MVP thinking beats perfect thinking every time

---

*Analysis by Mrunal Ghode — Aspiring Product Manager*

*Connect with me on [LinkedIn]www.linkedin.com/in/mrunal-ghode*

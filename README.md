# 🍕 Pizza Sales Analytics — MySQL Business Intelligence

A MySQL-driven insight system built on the `pizza_hut` database.  
Turns raw order logs into pricing strategy, demand timing, and menu innovation signals.

---

## 🧠 What This Project Really Is
Instead of treating SQL as retrieval, this project treats SQL as a **decision-simulation layer** for a smart food retail engine:
- Revenue becomes a **product success signal**
- Order time becomes a **demand-prediction feature**
- Pizza pricing becomes a **tier-design mechanism**
- Categories become **market segments**

---

## 🗂️ Database Tables Used

| Table | Role |
|-------|------|
| `orders` | Order timestamps + order IDs |
| `order_details` | Quantity + pizza_id mapping |
| `pizzas` | Pizza size + price |
| `pizza_types` | Category labels (Classic, Supreme, Veggie, Chicken) |

---

## 📊 Core Insights Generated

### Order Volume & Popularity
| Metric | Result |
|--------|--------|
| Total Orders | **21,350+** |
| Most Common Size | **Medium (M)** |
| Top 5 by Demand | Pepperoni, Chicken, Supreme variants lead |

### Revenue Intelligence
| Revenue Metric | Value |
|---------------|-------|
| Total Sales Revenue | **₹84,616.40+** |
| Highest Priced Pizza | **BBQ Chicken Pizza — $35.95** |

### Demand Timing Pattern
| Time Segment | Trend |
|--------------|------|
| After 5 PM | **Peak order density** → ideal for offers & surge pricing |
| Late night | Gradual decline |

### Revenue Share Balance (Market Segment Parity)
| Pizza Category | % of Total Revenue |
|---------------|------------------|
| Classic | 26.73% |
| Supreme | 25.93% |
| Veggie | 24.30% |
| Chicken | 23.04% |

*This near-equal distribution hints at a market ready for dynamic menu rotation instead of static best-seller bias.*

---

## 📈 Growth Interpretation (Beyond Numbers)
- **Premium price outliers** like BBQ Chicken Pizza signal opportunity for a **"Gold Tier Pizza" subscription or priority delivery SKU**
- **Hourly clustering** behaves like an implicit feature for a **future ML model: Promo-Drop Timing AI**
- **Category parity** suggests building an **auto-rotating menu** that adapts weekly to revenue momentum rather than fixed popularity
- **Size dominance (M)** becomes a strong design input for **personalized combo bundling**
- **Cumulative revenue trend** mimics compounding growth — proving loyalty models could scale if layered on top

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Database | MySQL |
| Query Logic | Aggregation, Multi-Join, Time-Series Revenue |
| Innovation Lens | Pricing tiers, demand cycles, menu engineering |

---

## 🚀 Future-Ready Capabilities This Repo Proves
| Capability | What It Enables |
|-----------|---------------|
| Revenue Computation | Pricing strategy, premium tiering |
| Order Hour Analysis | AI-timed marketing automation |
| Category-Wise Ranking | Menu redesign & rotation |
| High-Price Detection | Product tier innovation |

---



> *“Data is not past. Data is product future.”*

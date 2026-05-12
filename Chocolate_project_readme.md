# Chocolate Sales Analysis 🍫

Ever wondered which chocolate sells the most — and why? That's exactly what this project is about.

I analyzed global chocolate sales data spanning from 2022 to 2024 to help a sales team understand how their products are performing across different countries, months, and salespeople. The goal was simple: turn raw sales numbers into clear insights that can help the team make smarter decisions about production, marketing, and distribution.

---

## What's in the data?

The dataset has **3,282 records** covering sales made across 6 countries — Australia, UK, India, USA, Canada, and New Zealand. Each row tells us who sold what, where, when, how many boxes were shipped, and how much money was made.

No missing values. No duplicates. Pretty clean to work with.

---

## What I was trying to find out

- Are sales growing year over year?
- Which months are the best (and worst) for sales?
- Which products make the most money?
- Are there products being shipped in huge quantities but barely making revenue?
- Which countries and salespeople are driving the most sales?
- Is there any relationship between boxes shipped, price, and revenue?

---

## What I found

**Sales are growing every year** — from $6.18M in 2022, to $6.64M in 2023, to $6.96M in 2024. Small but steady growth.

**January is consistently the best month** across all three years, followed by June and July. April is always the slowest month. This pattern repeats every year without fail.

**Smooth Silky Salty** is the top-earning product at $1.12M in total revenue. On the flip side, **70% Dark Bites** brought in the least at $677K.

**Caramel Stuffed Bars** is an interesting case — it has the highest number of boxes shipped (26,576) but one of the lowest revenues. That's a red flag. It might be underpriced.

**Australia** leads all countries in total sales ($3.64M), followed by UK and India. The gap between countries isn't huge though — they're all fairly competitive.

**Ches Bonnell** is the top salesperson ($1.02M), and **Wilone O'Kielt** is at the bottom ($439K) — more than half the revenue gap. That's worth investigating.

---

## Something interesting about correlations

Shipping more boxes doesn't necessarily mean more revenue. The correlation between boxes shipped and revenue is almost zero (-0.01).

But here's the thing — **higher price per box does lead to higher revenue** (correlation of +0.23). So the focus should probably be on pricing strategy, not just volume.

---

## What I'd recommend (if I were advising the team)

- **Stock up in December** to prepare for the January spike. Don't get caught short.
- **Run promotions in April** — discounts or bundle deals could help lift the slowest month.
- **Revisit the pricing of Caramel Stuffed Bars and Drinking Coco** — they're being shipped in large quantities but not generating proportional revenue.
- **Celebrate the top salespeople and learn from them** — what are Ches Bonnell and Oby Sorrel doing differently? That knowledge should be shared.
- **Australia and UK are strong markets** — worth investing more marketing budget there to maintain the lead.

---

## Tools used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## How to run this yourself

```bash
git clone https://github.com/your-username/chocolate-sales-eda.git
cd chocolate-sales-eda
pip install pandas numpy matplotlib seaborn
jupyter notebook chocolate_eda.ipynb
```

---

## A quick note on limitations

The data only covers January to August for each year — the second half of the year is missing. So seasonal trends around the holiday season (which is huge for chocolate) aren't captured here. Any conclusions about "yearly trends" should be taken with that in mind.

---

*Made by Manish Gautam — Please 
feel free to reach out if you have questions or feedback.*

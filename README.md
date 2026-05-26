# Westcoast Auto Sales — F&I Menu

An interactive Finance & Insurance menu built for the dealership finance office. Lets you hot-swap deal variables in real time and instantly see how changes to price, APR, trade, and F&I products affect the customer's monthly payment — across multiple term options.

---

## My Thought Process

I spent years in automotive finance. I know exactly what it's like to sit across from a customer in the F&I office, manually recalculating payments every time they push back on a product or ask "what if I put more down?" It's slow, it's clunky, and it breaks the rhythm of the presentation.

I built this tool to fix that. I used Claude AI to vibe code the whole thing — I came in with deep domain knowledge of how an F&I deal is structured and just described what I wanted until it was right. The fact that I don't write code didn't matter. Knowing the business did.

### What the tool does

It's a live deal calculator that mirrors the structure of a real F&I menu presentation:

- Enter the deal variables: selling price, tax rate, fees, trade allowance, payoff, down payment, and APR
- Set your F&I product pricing (warranty tiers and GAP)
- Toggle which term options to show (60, 72, or 84 months)
- The menu instantly renders every package option — Base, Bronze, Gold, Platinum, and each with GAP — with the monthly payment calculated across all active terms

Every input updates the whole menu in real time. No recalculating manually, no switching between spreadsheet tabs.

### Why this matters in the F&I office

Speed and clarity are everything when you're presenting to a customer. If they ask what the payment looks like at a different term or if they add GAP, you need that answer instantly. This tool makes you look like you have everything memorized — because the math is already done.

### PDF and iPad support

Once you've landed on the right package, you can mark the selected option and print it as a clean PDF to review or leave with the customer. The menu also includes instructions for iPad compatibility — because that's what most finance offices actually use at the desk.

---

## Features

- **Live payment calculator** — adjusts instantly as you change any deal variable
- **7 package options** — Base, Bronze, Gold, Platinum warranty tiers, plus GAP add-on versions of each
- **Configurable terms** — toggle 60, 72, and 84 month options independently
- **Hot-swappable inputs** — price, APR, fees, trade, payoff, down payment, F&I product pricing
- **PDF print** — clean printable version of the selected package
- **iPad compatible** — instructions included for finance office tablet setup

---

## Background

This came directly from my time working in automotive finance at a dealership. I knew the domain inside and out — I just needed a way to build the tool. That's where Claude AI came in.

---

## Built With

- HTML, CSS, JavaScript
- Standard amortization formulas for payment calculations
- Claude AI

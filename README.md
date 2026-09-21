PrintMargin 🧮
PrintMargin is a fast, lightweight 3D printing cost and recommended selling price calculator.

Built for 3D printing hobbyists, makers, and small business owners who want to price their prints accurately using true profit margin calculations—not just simple cost-plus markups.

👉 Live Demo: https://gh0stw33d.github.io/PrintMargin/

✨ Features
True Profit Margin Math: Uses the formula Cost / (1 - Margin%) instead of simple cost-plus markup, calculating the selling price needed to reach your target margin.

Failure & Waste Allowance: Factor in failed prints, support material, and purged filament automatically (applied to the base production cost).

Full Cost Breakdown: Calculates materials, electricity consumption, machine depreciation, labor, and custom packaging fees.

One-Click Quote Summary: Generate a clean summary text block instantly to copy into emails or direct messages.

Multi-Currency Support: Switch between EUR (€), USD ($), and GBP (£).

Zero Dependencies: Pure HTML/CSS/JavaScript. Fast loading and open-source.

💡 How It Works
Most basic calculators simply multiply your cost by a percentage (e.g., $10 cost + 40% markup = $14). However, a true 40% margin on a $14 sale should yield $5.60, leaving you short.

PrintMargin calculates true margin:
Selling Price = Total Production Cost / (1 - Desired Margin %)

With a 40% target margin, the calculated selling price leaves 40% of the sale price as profit after the included costs. Failure & waste allowance is applied to the calculated production cost to account for failed prints, support material, purges, and other material waste.

⚠️ What It Doesn't Include
PrintMargin provides a cost-based starting point for pricing. It does not account for market demand, competitor pricing, model licensing, taxes, payment fees, shipping, or platform fees unless you manually enter them under Packaging/Other.

Your actual selling price may therefore differ from the calculated baseline.

🛠️ Usage / Local Setup
No build steps or external frameworks required.

Clone or download this repository:
git clone https://github.com/Gh0stW33d/PrintMargin.git

Open index.html directly in any modern browser.

🤝 Contributing
Feedback, bug reports, and pull requests are welcome! Feel free to open an issue if you have suggestions.

📄 License
This project is open-source and available under the MIT LICENCE.

# canafford - Money Decision Engine

A calculator that answers real money decisions — "Can I afford this?" — by showing the before/after impact on your monthly cash and long-term wealth.

Not a budget tracker. Not generic advice. A personalized calculation for one decision at a time.

Try it live → <!-- replace with your GitHub Pages URL once live -->

What it does

Enter:

Your monthly take-home income
Fixed monthly expenses
Any existing loan/debt payments
What you currently invest or save each month
A purchase you're considering — either a financed purchase (car, house, anything with a loan) or a one-time expense (vacation, gadget)

It calculates:

Your monthly cash flow before the purchase
Your monthly cash flow after the purchase (including the new loan payment, computed with a real amortization formula)
A plain-English verdict: affordable, a real trade-off, or not affordable
What that decision costs your wealth over 1, 3, and 5 years, assuming you keep investing the difference

Running it locally

No installation needed — it's a single static file.

Clone this repo:
   git clone https://github.com/yourusername/money-decision-engine.git
Open index.html directly in your browser, or serve it locally:
   cd money-decision-engine
   python3 -m http.server 8000

Then visit http://localhost:8000


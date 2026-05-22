# 🏡 First Home Savings Account (FHSA) Calculator

**🔗 [Click here to use the Live Tool!](https://exekyute.github.io/fhsa-calc/)**

This tool helps you map out your path to homeownership.

Because dealing with taxes, contribution limits, and government rules can be intimidating, this humble tool does some of the work for you right in your browser.

## ✨ What does it do?
You just move a few sliders (like your income and how much you want to save), and the calculator will automatically show you:

* **Your Total Down Payment:** How much cash you will actually have to buy a house.
* **Your Tax Savings:** An estimate of how much money you'll get back at tax time.
* **The "Whose Money Is It?" Bar:** A colorful visual showing how much of the final total is your own cash, how much is government tax refunds, and how much is pure investment growth.

## 🛠️ Features (Why it's cool)
* **Auto-Saves:** If you accidentally close the tab, don't panic. It remembers your numbers for the next time you visit.
* **Download to Excel:** Want to keep a copy of your plan? Hit the **Export CSV** button to download your year-by-year schedule.
* **Printer-Friendly:** If you hit `Ctrl+P` (or `Cmd+P` on Mac) to print a copy, the tool automatically hides all the buttons and sliders to give you a clean, professional paper report.
* **Built-In Rulebook:** It won't let you break the rules. It automatically stops your contributions if you hit the government's $40,000 lifetime limit, and it warns you about the strict 15-year account expiry rule.
* **Reinvest Toggle:** A handy switch to see what happens if you take your tax refund every spring and immediately dump it back into your savings.

## 🚀 How to run it
You can try it out instantly by clicking the live web link at the top of this page!

Alternatively, if you want to run it offline on your computer:
1. Simply download the `index.html` file from this repository.
2. Double-click it.
3. It will open securely in your favorite web browser (Chrome, Safari, Edge, etc.) and work instantly without needing any internet connection.

## 🇨🇦 The Canadian Rules it Follows
This calculator is strictly coded to follow the official guardrails of the Canadian FHSA:
* **Annual Limit:** Maximum $8,000 per year.
* **Lifetime Limit:** Maximum $40,000 total out-of-pocket.
* **Carry-Forward:** Unused room rolls over, but is capped at a max of $8,000 carried over per year.
* **Maturity:** The account can only stay open for 15 years before you must use it or transfer it.
* **Tax Rates:** It uses a built-in cheat sheet to estimate your marginal tax bracket based on the income you enter.

## 💻 Tech Details (For the curious)
* **React:** Makes all the sliders fast and interactive.
* **Tailwind CSS:** Makes it look pretty and work great on mobile phones.
* **Babel:** Translates the code directly in your browser so you don't need a build server. 

*Disclaimer: This is a planning tool, not financial advice. Marginal tax rates are estimates based on simplified Federal + average Provincial brackets. Always talk to a certified accountant or financial advisor before making big money moves.*

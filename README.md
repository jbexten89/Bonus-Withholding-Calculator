# Bonus Withholding Calculator

A single-page calculator for estimating the withholding and net deposit on a bonus check paid in Ohio.

Enter the bonus amount, your pre-tax 401(k) % and Roth %, and it shows:

- The direct deposit you should expect
- Federal (22% supplemental rate), Social Security, Medicare, Ohio and school district withholding
- A rough estimate of extra federal tax owed (or refunded) at filing, based on your bracket
- A line-by-line statement preview laid out like a pay stub

2026 uses Ohio's 2.75% supplemental rate; 2025 and earlier use 3.5%. The school district rate and exemptions can be changed under Advanced.

## Your bonus history (private)

Open **My bonus history** and tap **Load history file** to pick a `bonus-history.json` backup from your device. The file is read in your browser and saved only in that browser, so it never goes to GitHub or anywhere else, and other visitors only see the plain calculator. Tap a row to load that bonus into the calculator. **Export backup** saves an updated copy, and **Remove from this device** clears it.

Load the file once on each device or browser you use. `.gitignore` blocks history files from being committed by accident.

## Use

Open `index.html` in any browser. No build step or dependencies. Your last inputs are remembered in the browser.

Estimates only. Payroll can change rates or methods.

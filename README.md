# Caregiver Salary Calculator

A mobile-first, single-page calculator for a caregiver's monthly payment (₪ / ILS).
Plain HTML, CSS and JavaScript in one file (`index.html`). There is no backend and nothing is stored.

**Live:** https://tarablusyuval-source.github.io/caregiver-salary/

## Formula

```
Total Salary = Base Salary + Saturdays × (Weekend Pay + Pocket Money + Food Money)
Final Amount = Total Salary − Agency Paid − Early Allowance + Additional Expenses
```

## Defaults

- **Month:** the previous month, since salary is paid for the month that just ended.
- **Number of Saturdays:** counted automatically from the selected month. You can still edit it.
- **Base Salary:** ₪6,500. **Per Saturday:** Weekend Pay ₪440 + Pocket Money ₪100 + Food Money ₪200.
- **Clear / Reset** goes back to these defaults.

## Use

- Open the live link on your phone and choose **Add to Home Screen**.
- Fill in the fields. The summary updates as you type.
- Use **Copy**, **Share**, or **Send via WhatsApp** to send the summary.
- You can also open `index.html` directly in any browser.

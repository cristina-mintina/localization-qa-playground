# BUG-001: Variable mismatch in subscription renewal notice (IT)

## Summary
The Italian localized string for the subscription renewal notice uses an
incorrect variable token, which does not match the English source.

## Environment
- Language: Italian (IT)
- File: `strings/ui_strings_it.csv`
- Key: `subscription_renewal_notice`

## Steps to Reproduce
1. Open `ui_strings_en.csv`.
2. Locate the key `subscription_renewal_notice`.
3. Note the variable `{date}` in the English source.
4. Open `ui_strings_it.csv`.
5. Locate the same key in the Italian file.
6. Observe the variable `{data}`.

## Expected Result
The Italian string uses the same variable as the source:

## Actual Result
The Italian string uses a different variable:

## Severity
**High**

Incorrect variables can cause runtime errors or display raw placeholders
to users in production.

## Notes
This issue was identified during localization QA review and should be fixed
by aligning variable usage with the source string.

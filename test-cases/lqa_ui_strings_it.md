# Test Case: Localization QA – Italian UI Strings

## Objective
Verify that Italian UI strings meet localization quality standards, including
linguistic accuracy, consistency with source content, and correct variable usage.

## Scope
This test case covers Italian UI strings defined in `ui_strings_it.csv`.

## Preconditions
- English source strings are available in `ui_strings_en.csv`
- Italian localized strings are available in `ui_strings_it.csv`

## Test Steps
1. Review each Italian string against the English source.
2. Check grammatical gender and agreement.
3. Verify punctuation consistency with the source language.
4. Confirm that all variables match the source exactly (e.g. `{date}`).
5. Review UI labels for naturalness and completeness.

## Expected Results
- Italian strings are grammatically correct and natural.
- Punctuation is consistent with the source where appropriate.
- All variables match the source exactly.
- No truncation or ambiguity is introduced.
- Known issues are documented in the bug-reports/ directory.

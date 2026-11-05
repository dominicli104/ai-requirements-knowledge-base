# Manual Test Scenarios — Fictional Requirements Knowledge Base

These are **test scenarios / expected results**; they are not evidence of a production-system UAT sign-off.

| ID | Action | Expected result |
|---|---|---|
| KB-T01 | Open `index.html` | 18 sample requirements and default detail are visible |
| KB-T02 | Search `DEMO-REQ-005` | One exact matching requirement and its source section display |
| KB-T03 | Search `credit` | All matching sample credit requirements are listed |
| KB-T04 | Search `TS-011` | The linked transaction-log requirement is found |
| KB-T05 | Choose `Organisation Portal` | Results are limited to that portal |
| KB-T06 | Choose status `Wishlist` | Only wishlist items appear |
| KB-T07 | Search an invented ID | A no-evidence message appears; no fabricated match |
| KB-T08 | Click a result | Original statement, version, source and test reference update |
| KB-T09 | Click Clear filters | Entire result set becomes visible |
| KB-T10 | Open on a narrow mobile viewport | Layout stacks without losing controls |

**Note:** The demonstration is not a retrieval-augmented-generation engine and does not itself parse PDFs, search your ChatGPT files or call external APIs.

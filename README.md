# Stirling Help Centre

Source for the customer-facing help site for Stirling.

## How it works

- Pages live in `docs/` as markdown, one page per task.
- `mkdocs.yml` holds the site name, theme and the left-hand menu. A new page must be added to `nav` there.
- Every push to `main` rebuilds and publishes the site through GitHub Pages.

## Preview on your own machine

```
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000.

## Rules for this repository

This site is public. Before committing, check that the change contains:

- no real customer or client names, addresses, phone numbers or case details, in text or in screenshots
- no staff email addresses
- no internal notes, test findings or supplier names that partners do not need

Screenshots use invented details only, never the live system.

`production/` holds video scripts and other working material. It is not published to the site.

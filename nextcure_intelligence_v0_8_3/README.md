# NextCure Intelligence System v0.8.1

Executive UI clarity patch on top of v0.8.

## What changed

- Rebuilt the Executive Summary snapshot cards into a responsive grid so cards no longer collapse into narrow vertical columns.
- Added detail-route pills under each snapshot card so Michael knows which analysis tab explains the number.
- Compressed the Executive Readout into three high-priority decision cards, with channel details moved behind an expander.
- Replaced remaining vague `Mixed window` language with explicit state definitions such as `Neutral window (conflicting signals)`.
- Styled the Streamlit tab overflow/scroll controls so the white scroll button no longer clashes with the dark product UI.
- Preserved all v0.8 technical, catalyst timing, alignment, market regime, and capital-flow engines.

## Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Notes

This is still a one-button CEO-facing dashboard. Backend settings and future scraping/API hooks remain hidden from the user-facing surface.

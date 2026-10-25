# Independent final candidate review

Date: 2026-10-25

## Exact artifacts

- Writer commit: `c0d9ff244ccf37aeb727bd908ef5710c544b3d3c`
- HTML blob: `d98f0a2625f68ea5bb6df7089e3bcad4a36e6220` (`index.html`)
- PDF: `assets/Romy-Mondello-Resume-2026-10.pdf`
- PDF SHA-256: `243f3c6779e81d1060c79b756ab661385b5d44e89e052c6a3d1cab08e23f65df`

## Verdict

ACCEPT for public content and layout, with the deliberate privacy exception that the current resume fact checker reports `ok:false` only because the public phone is omitted. Do not add the private phone solely to satisfy that checker.

The PDF is one-page letter-size, selectable text, and rendered cleanly without visible clipping or overlap. `pdffonts` confirms embedded selectable Type 1 fonts; `pdftotext` returns the complete page. The HTML links to this dated PDF in both download locations, and the working tree matches the reviewed commit for `index.html` and the PDF.

## Fact and safety checks

The PDF contains the canonical six-year statement, Knox 2020 start, current JEV Codex+Claude wording, attributable QQ PR #333/#319/#72 contributions, bounded joint local prototype wording, and bounded characteristic-two/dimension-two research scope. It does not claim QQ ownership, production deployment, customer adoption, automatic crash recovery, or a bachelor’s degree. Email and public links are present; phone is intentionally absent.

The current validator returns `ok:false` with exactly one issue: `missing canonical phone number`. All other canonical fields pass. This is a checker/privacy policy mismatch, not a factual defect under the approved public-contact policy.

The HTML’s public links returned HTTP 200 for JEV, QQ PRs #72/#333/#319, arXiv, mondello.dev, and the GitHub profile at review time. Research wording remains broad and public-safe; it should not be expanded into product-security ownership claims.

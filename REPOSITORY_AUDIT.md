# Repository Audit and Change Map

## Status
Completed during implementation of Portfolio Specification v1.0.

## Retained
- Existing typography direction: Outfit + Inter
- Warm neutral background, restrained green/purple accents, rounded cards, generous whitespace
- Scaffold research content, prototype screens, and four primary research artifacts
- Four research memos
- Existing resume PDF, logo, and headshot

## Changed
- Primary navigation standardized to Work / Research / About / Resume
- Scaffold moved under Work and reframed around research evidence
- Alex persona replaced with a research-pattern model; rationale is documented in the case study
- Four Scaffold PDFs converted to native HTML with PDFs retained as downloads
- Four research memos converted to native HTML
- Neuroinclusive Environments Project added as an ongoing research initiative rather than a case study
- Observation practice added as a subordinate, non-nav page
- Relative diptych copied locally; no remote persona image dependency remains
- Shared CSS replaced with a smaller tokenized system

## Removed / not carried forward
- Broken #writing navigation links
- Duplicate ai_bandwidth.pdf
- Duplicate scaffold-ethics.pdf
- Remote Imgur persona image
- Legacy CSS classes and editing comments
- Portfolio as a navigation label

## Accessibility / technical changes
- One H1 per page
- Semantic headings and nav landmarks
- Skip links and focus-visible treatment
- Reduced-motion handling
- Local image assets with descriptive alt text
- Responsive layout rules at 960px and 720px
- No JavaScript required for core navigation or content

## Deferred
- Canonical URLs and Open Graph images until deployment URL is confirmed
- Full PDF accessibility remediation
- Analytics
- Additional case studies

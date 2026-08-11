# Portfolio Design & Implementation Specification v1.0

**Document status:** Approved  
**Document type:** Canonical portfolio design and implementation specification  
**Portfolio owner:** Abby Buchanan  
**Primary purpose:** Increase the probability of receiving interviews for UX Research, UX Strategy, Accessibility, Human Factors, and systems-oriented roles  
**Implementation status:** No implementation authorized until this specification is approved

---

## 1. Purpose and Authority

This document governs the design, content structure, technical implementation, and future evolution of Abby Buchanan’s UX portfolio.

It is not a second project charter. The Portfolio Project Constitution defines the portfolio’s purpose and governing principles. The Neuroinclusive Environments Master Project Charter governs the research initiative presented within the portfolio. This specification translates those priorities into implementation decisions for the website.

When later design or implementation decisions conflict, use this order of precedence:

1. Hireability
2. Accuracy and trust
3. Clarity and cognitive ease
4. Conceptual coherence
5. Accessibility
6. Maintainability
7. Visual refinement
8. Novelty

The portfolio exists to obtain interviews. It is not an archive, personal website, gallery, or blog. Every page, section, artifact, and interaction must earn its place by reducing a meaningful hiring uncertainty.

---

## 2. Project Vision

Create a restrained, evidence-led portfolio that makes Abby’s research thinking legible to hiring managers.

The portfolio should demonstrate, through work rather than self-description:

- qualitative research depth
- careful observation
- synthesis across complex material
- systems thinking
- strategic reasoning
- accessibility awareness
- ethical judgment
- intellectual humility
- ability to translate research into decisions

The experience should feel intellectually confident, calm, precise, and easy to evaluate.

The portfolio should not attempt to compete through visual spectacle. Typography, sequencing, evidence, and editorial judgment should carry the experience.

---

## 3. Hiring Strategy

### 3.1 Target roles

The portfolio is optimized for:

- UX Researcher
- Senior UX Researcher
- Product or Design Researcher
- UX Strategist
- Research Strategist
- Accessibility Researcher
- Human Factors Researcher
- Cognitive Accessibility or Inclusive Design roles
- Systems-oriented research and service-design roles
- Hybrid roles where qualitative research, synthesis, and strategic framing are central

It is not optimized for:

- UI-only product design roles
- brand design roles
- visual design roles
- front-end engineering roles
- generalist creative portfolio review
- academic publication review

### 3.2 Primary hiring questions the portfolio must answer

A hiring manager should be able to determine:

1. Can Abby frame a meaningful research problem?
2. Can she conduct credible qualitative research?
3. Can she distinguish evidence from interpretation?
4. Can she synthesize findings into a useful model or decision?
5. Can she connect individual experience to larger systems?
6. Can she translate research into product, service, or organizational implications?
7. Does she understand accessibility beyond compliance?
8. Can she communicate complex thinking clearly?
9. Can she work with ambiguity without overstating conclusions?
10. Is her experience transferable to a professional research team?

### 3.3 Hiring-risk priorities

The site should reduce these uncertainties in this order:

**Highest priority**
- Whether Abby has enough credible UX research evidence
- Whether her transition into UX is coherent
- Whether her thinking is strategic rather than merely reflective
- Whether she can show process, synthesis, and decisions

**Secondary priority**
- Whether she can work across accessibility, AI, physical, digital, and organizational contexts
- Whether her writing is disciplined enough for cross-functional work
- Whether she can make complex work accessible

**Lower priority**
- Whether she can produce visually polished layouts
- Whether she has a large volume of projects
- Whether she follows current portfolio trends

### 3.4 Success measures

The primary success metric is interview conversion.

Useful secondary indicators:

- recruiters can summarize Abby’s research identity accurately
- hiring managers reach the Scaffold evidence and research initiative pages
- portfolio review conversations focus on research judgment rather than career transition
- the site creates specific follow-up questions
- each major project can support an interview conversation without extensive explanation
- future updates can be added without redesigning the site

Page views, time on page, visual novelty, and volume of content are not primary success measures.

---

## 4. Source-Grounded Portfolio Assessment

This section distinguishes direct observations from strategic interpretation.

### 4.1 Repository observations

The existing repository contains:

- a homepage
- a long-form Scaffold case study
- a resume page and resume PDF
- four research memo PDFs
- five Scaffold research-artifact PDFs
- six Scaffold prototype screens
- a shared stylesheet
- a headshot, logo, and supporting images

The current visual system uses:

- a warm off-white background
- black and gray typography
- restrained green and purple accents
- Outfit for display typography
- Inter for body typography
- wide page margins
- rounded cards
- generous section spacing
- minimal motion
- responsive grid collapse

The visual direction is coherent enough to preserve. The site does not need a redesign.

### 4.2 Existing strengths

#### Homepage

The strongest existing positioning is the focus on “cognitively demanding systems” and the “translation layer” between human intent and institutional requirements.

This framing is distinct, relevant to UX research, and broad enough to connect Scaffold, accessibility, AI, and the Neuroinclusive Environments Project.

The homepage already communicates restraint and seriousness.

#### Scaffold

Scaffold contains the strongest direct evidence of UX research practice.

It includes:

- problem framing
- participant interviews
- research questions
- thematic findings
- design implications
- ethical constraints
- usability findings
- iteration decisions
- prototype evolution
- reflection and next steps

The case study also demonstrates a recurring research principle: apparent failure or noncompliance may reflect a mismatch between system demands and available cognitive capacity.

#### Research memos

The memos demonstrate:

- pattern recognition
- interdisciplinary synthesis
- comfort with unresolved questions
- conceptual development
- a consistent concern with cognitive bandwidth, institutional compatibility, and unequal consequences

They support Abby’s identity as a researcher and strategist. Their current PDF-only presentation, however, makes them feel separate from the website and harder to scan.

#### Neuroinclusive Environments Project

The Charter provides the strongest evidence of long-range research strategy and systems thinking. It defines participation as broader than access, treats environments as physical, digital, organizational, and hybrid systems, and prioritizes transferable principles over isolated examples. It also explicitly distinguishes observation, inference, hypothesis, opinion, and unknown. fileciteturn1file0L68-L78

The project is employment-oriented, emphasizes original synthesis, and rejects uncontrolled expansion. Those principles align directly with the portfolio’s governing purpose. fileciteturn1file0L4-L8

### 4.3 Existing weaknesses

#### Information architecture

The current navigation mixes page types and in-page anchors:

- Portfolio
- Research Memos
- About
- Scaffold
- Resume

This does not clearly communicate hierarchy. “Portfolio” is ambiguous as both homepage and category. “Scaffold” is elevated as a permanent top-level item while other research work is embedded lower on the homepage.

The Scaffold page also links to `index.html#writing`, while the homepage section is currently `#research`. This is a broken or outdated navigation reference.

#### Content hierarchy

The homepage introduces several strong ideas before establishing the simplest possible answer to:

- who Abby is
- what roles she is pursuing
- what evidence is available

The “translation layer” framework is valuable, but it currently competes with the featured project and research memos rather than organizing them.

#### Research evidence

Scaffold includes strong content but is too long and somewhat repetitive. Several sections restate the same core point: users need reduced ambiguity, emotional safety, reversibility, and autonomy-preserving support.

The page demonstrates depth, but the current length makes it harder for a hiring manager to distinguish:

- research question
- method
- evidence
- synthesis
- design response
- outcome
- limitations

#### Artifact presentation

PDF artifacts are useful evidence, but external PDFs interrupt the site experience and require hiring managers to inspect multiple separate documents.

The artifact set should remain available, but the key evidence should be converted into concise HTML pages or embedded summaries.

#### Writing quality and code quality

The homepage Research Memos section contains malformed paragraph tags. The CSS contains repeated declarations, comments left as editing notes, inconsistent class systems, and duplicated or legacy rules.

These issues do not currently destroy the experience, but they reduce maintainability and create avoidable implementation risk.

#### Resume positioning

The resume and About copy translate prior work into UX language, but some phrasing risks sounding retrospective or inflated when the supporting evidence is not visible.

The portfolio should make transferability evident through examples and artifacts rather than repeatedly labeling prior roles as UX.

---

## 5. Defensible Conceptual Thread

### 5.1 Core thread

A defensible conceptual thread does exist:

> Abby studies the hidden effort required for people to participate in systems, then translates that observation into clearer, more humane structures.

This thread connects:

- **Scaffold:** the effort required to translate intention into executable action during overload
- **Research Memos:** the effort required to remain compatible with institutional and technological systems
- **Neuroinclusive Environments Project:** the effort environments impose on participation across physical, digital, and organizational contexts
- **Observation practice:** close attention to patterns, thresholds, bodies, environments, and relationships
- **Photography:** visual study of boundaries, correspondence, body-as-land, scale, and formal pattern
- **Poetry:** longitudinal observation, juxtaposition, recurrence, systems of time, embodiment, and synthesis

### 5.2 Limits of the thread

This thread is conceptual, not categorical.

Photography and poetry should not be presented as UX projects or equivalent evidence of research practice. Doing so would weaken credibility.

They may support the research identity only when framed as an observation practice that informs attention, pattern recognition, and composition. They must remain subordinate to professional research evidence.

### 5.3 Strategic recommendation

Use the thread to guide editorial sequencing, not to force every medium into equal prominence.

The portfolio should communicate:

1. research practice
2. research thinking
3. ongoing research direction
4. observational foundation

It should not communicate:

1. UX
2. writing
3. photography
4. poetry

as four parallel creative identities.

---

## 6. Portfolio Philosophy

### 6.1 Evidence before claims

The portfolio should avoid unsupported statements such as:

- “exceptional researcher”
- “deeply empathetic”
- “innovative systems thinker”
- “thought leader”
- “expert in neurodiversity”

Instead, show:

- interview questions
- synthesis decisions
- pattern matrices
- research limitations
- competing interpretations
- changes made because of evidence
- decisions not pursued
- implications for teams or systems

### 6.2 Selectivity over completeness

The site should contain the minimum body of work needed to demonstrate a convincing research identity.

A strong portfolio with:

- one substantial case study
- one active research initiative
- two or three excellent research memos
- one concise observation section

is preferable to a larger site with uneven evidence.

### 6.3 Legibility over performance

Hiring managers should not need to infer where the research is.

Every core page should reveal its purpose within the first screen and make the main evidence visible through headings, summaries, and artifacts.

### 6.4 Intellectual humility

The portfolio should clearly distinguish:

- what was observed
- what participants reported
- what Abby interpreted
- what the evidence supports
- what remains uncertain
- what would be tested next

### 6.5 Professional usefulness over perfection

A page is complete when it:

- answers its intended hiring question
- is accurate
- is easy to scan
- contains enough evidence to support discussion
- is accessible
- does not materially improve through another round of decorative refinement

---

## 7. Information Architecture

### 7.1 Recommended top-level navigation

Use four top-level destinations:

1. **Work**
2. **Research**
3. **About**
4. **Resume**

The logo or name returns to the homepage.

Do not include “Portfolio” as a navigation label. The entire site is the portfolio.

Do not keep Scaffold as a permanent top-level navigation item. It belongs under Work.

### 7.2 Recommended page hierarchy

```text
/
├── index.html                         Homepage
├── work/
│   ├── scaffold.html                 Primary UX research case study
│   └── scaffold/
│       ├── interview-guide.html      Supporting artifact
│       ├── synthesis.html            Supporting artifact
│       ├── ethical-constraints.html  Supporting artifact
│       └── usability-findings.html   Supporting artifact
├── research/
│   ├── index.html                    Research overview
│   ├── neuroinclusive-environments.html
│   └── memos/
│       ├── invisible-tax.html
│       ├── ai-bandwidth.html
│       ├── opportunity-gap.html
│       └── consequence-gap.html
├── observation/
│   └── index.html                    Optional supporting evidence page
├── about.html
├── resume.html
└── assets/
    ├── css/
    ├── images/
    ├── documents/
    └── icons/
```

### 7.3 Initial public navigation

The Observation page should not appear in the primary navigation at launch.

It should be linked contextually from About, using a restrained label such as:

**Observation practice**

This prevents photography and poetry from competing with research evidence while preserving their conceptual role.

### 7.4 Why each section belongs

#### Work

**Why it belongs:** Gives hiring managers direct evidence of completed UX research and design work.  
**Uncertainty reduced:** Whether Abby can perform an end-to-end research and design process.  
**Hiring value:** Highest.

#### Research

**Why it belongs:** Shows sustained inquiry beyond a single student project.  
**Uncertainty reduced:** Whether Abby has a coherent research agenda and can think strategically across domains.  
**Hiring value:** High.

#### About

**Why it belongs:** Explains career continuity and research perspective.  
**Uncertainty reduced:** Whether Abby’s prior experience is relevant and whether her transition into UX is coherent.  
**Hiring value:** Moderate to high.

#### Resume

**Why it belongs:** Supports recruiter workflow and formal application review.  
**Uncertainty reduced:** Whether experience, education, and chronology meet role requirements.  
**Hiring value:** High.

#### Observation practice

**Why it may belong:** Provides supporting evidence of sustained attention, pattern recognition, composition, and embodied observation.  
**Uncertainty reduced:** Limited. It helps explain the origin of Abby’s observational sensitivity but does not prove professional research competence.  
**Hiring value:** Moderate only when tightly edited.

---

## 8. Homepage Specification

### 8.1 Purpose

The homepage should establish Abby’s research identity, provide immediate evidence, and route hiring managers to the most relevant work.

### 8.2 Recommended sequence

1. Hero
2. Selected work
3. Research direction
4. Research memos
5. About preview
6. Contact / resume action

### 8.3 Hero requirements

The hero must answer:

- who Abby is
- what she studies
- what kind of work is available
- what the hiring manager should view first

Recommended structure:

**Eyebrow**  
UX Research · Research Strategy · Cognitive Accessibility

**Primary statement**  
Researching how people participate in cognitively demanding systems.

**Supporting statement**  
A concise explanation of the recurring focus on translation burden, cognitive friction, and the gap between human intent and system requirements.

**Primary action**  
View Scaffold

**Secondary action**  
Explore Research

Avoid multiple conceptual paragraphs before the first project link.

### 8.4 Selected work

Feature Scaffold as the primary case study.

The card should include:

- problem
- role
- methods
- one outcome or research contribution
- clear link

Do not use a remote Imgur image. Store all portfolio images locally.

### 8.5 Research direction

Introduce the Neuroinclusive Environments Project as an ongoing research initiative, not a completed case study.

Display:

- central question
- current phase
- research domains
- one provisional framework or visual
- link to the full project page

### 8.6 Research memos

Show no more than three memos on the homepage.

Recommended initial selection:

1. The Invisible Tax
2. The Real AI Divide Isn’t Intelligence. It’s Bandwidth.
3. The Consequence Gap

“The Opportunity Gap” can remain on the Research overview page if its argument materially differs after editorial review. Otherwise, combine or defer it.

### 8.7 About preview

Keep the About preview short.

Its purpose is not to narrate the entire career. It should connect prior work to the current research practice through specific transferable activities:

- interviewing
- observation
- environmental design
- service systems
- synthesis
- translating needs into structures

---

## 9. Scaffold Case Study Specification

### 9.1 Purpose

Scaffold is the primary proof that Abby can conduct and communicate UX research.

The page must privilege evidence, synthesis, and decisions over product promotion.

### 9.2 Required page structure

1. Project summary
2. Research question
3. Context and constraints
4. Role and scope
5. Methods
6. Participants
7. Evidence
8. Synthesis
9. Design principles
10. Prototype response
11. Usability findings
12. Ethical constraints
13. Limitations
14. What changed
15. What would happen next
16. Supporting artifacts

### 9.3 Above-the-fold summary

Include:

- one-sentence project description
- role
- duration
- methods
- participant count
- project status
- concise outcome

Do not lead with broad language about “revolutionizing productivity” or AI.

### 9.4 Evidence model

Use a repeated editorial pattern:

**Observation**  
What participants said or what was directly observed.

**Interpretation**  
What the evidence may indicate.

**Design implication**  
What changed in the product or research direction.

This pattern should replace repeated narrative summaries.

### 9.5 Participant accuracy

The current repository states five interviews. The page should specify:

- recruitment basis
- relevant lived-experience criteria
- interview format
- duration
- what was and was not validated
- whether usability participants were the same people

Do not imply population-level findings.

### 9.6 Persona recommendation

The “Alex” persona should be reviewed critically.

If it is a synthesis persona built from five interviews, it risks overstating representativeness. Replace it with one of these:

- a research-pattern profile
- a composite scenario explicitly labeled as composite
- a participant-needs matrix
- a context-and-capacity model

A matrix or model will better support senior research positioning than a conventional persona.

### 9.7 Prototype treatment

Prototype screens should demonstrate how findings changed the interaction.

Each screen should include:

- research problem addressed
- design decision
- relevant constraint
- unresolved question

Do not present six screens as a visual gallery without research context.

### 9.8 Artifact treatment

Convert the following into HTML:

- interview guide
- research synthesis
- ethical AI constraints
- usability findings

Retain downloadable PDFs only as secondary links.

The activity notes artifact should not be public unless it contains meaningful evidence and is appropriately anonymized.

### 9.9 Required limitations section

Include:

- small sample
- self-selection
- exploratory scope
- lack of longitudinal use
- prototype fidelity limits
- unresolved AI feasibility
- distinction between executive dysfunction experiences and clinical claims

This section increases trust rather than weakening the project.

### 9.10 Acceptance criteria

The page is complete when a hiring manager can identify, within five minutes:

- the research question
- what Abby did
- what evidence was gathered
- what patterns emerged
- how the design changed
- what remains uncertain
- what Abby would do next

---

## 10. Research Architecture

### 10.1 Research overview page

The Research page should organize two distinct forms of work:

1. ongoing research initiative
2. research memos

It should not use a blog feed.

### 10.2 Neuroinclusive Environments Project page

The website should communicate the project rather than reproduce its Charter.

Required sections:

1. Project overview
2. Central research premise
3. Why participation is the unit of concern
4. Research questions
5. Analytical framework
6. Current phase
7. Representative landscape findings
8. Emerging patterns
9. Research methods
10. Evidence and confidence approach
11. Current outputs
12. Limitations and status
13. Collaboration or contact

The Charter defines participation as meaningful engagement with autonomy, dignity, safety, and agency, and treats accessibility as necessary but insufficient. fileciteturn1file0L68-L73 The page should communicate this distinction concisely.

The Charter also frames the unit of analysis as an intentional intervention designed to improve participation and compares interventions across sectors. fileciteturn1file0L79-L83 This is a strong organizing device for the page.

### 10.3 Research memo pages

Convert PDFs to native HTML.

Each memo page should include:

- memo number
- title
- date
- abstract
- main argument
- evidence type
- key distinctions
- open questions
- limitations
- related work
- downloadable PDF

The memos should remain working investigations, not polished “thought leadership.”

### 10.4 Memo editorial standard

Each memo should clearly label:

- observation
- interpretation
- hypothesis
- implication
- unresolved question

Where a memo makes historical, scientific, or contemporary factual claims, citations are required.

The current memos are conceptually strong but not all arguments are equally evidenced. HTML conversion should include editorial review, not direct transcription.

---

## 11. Observation Section

### 11.1 Strategic decision

Include one small Observation section only if it remains subordinate to professional research work.

Do not create separate top-level Photography and Poetry sections.

### 11.2 Role of the Relative diptych

The Relative diptych is the strongest candidate for inclusion.

The two black-and-white images create a formal relationship between:

- body and landscape
- skin and ground
- shadow and channel
- interior and exterior
- scale and ambiguity
- figure and environment

The work demonstrates composition, pattern recognition, and the ability to observe correspondence across unlike forms.

This supports the portfolio’s research identity when framed as a study in how perception constructs relationships.

It should not be presented as evidence of UX methodology.

### 11.3 Role of “May, 2024”

The poem demonstrates sustained observation across:

- biological cycles
- family time
- political events
- bodily experience
- place
- grief
- recurrence
- emergence

Its structure accumulates observations and synthesizes them into a larger temporal pattern. fileciteturn1file1L1-L8

However, the poem is long, intimate, and emotionally dominant. Publishing it in full inside the UX portfolio would shift the portfolio toward a literary identity and increase cognitive load.

### 11.4 Recommendation

Include:

- the Relative diptych
- a concise curatorial note
- a short excerpt from “May, 2024,” no more than several lines
- a link to the full poem only if Abby consciously accepts the personal exposure and the page remains clearly secondary

Do not place the poem on the homepage.

### 11.5 Observation page structure

1. Brief statement on observation as practice
2. Relative diptych
3. Short formal analysis
4. Short poem excerpt
5. Connection to research practice
6. Return link to Research or About

### 11.6 Acceptance criteria

The page is successful only if a hiring manager leaves with a clearer understanding of Abby’s observational discipline.

If user testing shows that the page is interpreted primarily as an art portfolio, remove it.

---

## 12. Content Strategy

### 12.1 Content hierarchy

Use this evidence hierarchy:

1. Direct research evidence
2. Research synthesis
3. Design or strategic decision
4. Reflection
5. Personal background
6. Supporting observation practice

### 12.2 Page-level rule

Every page must have one primary job.

A page should not simultaneously attempt to:

- tell a career story
- present a case study
- host a publication archive
- display art
- explain a research philosophy

### 12.3 Scannability

Use:

- descriptive headings
- short introductions
- summary blocks
- clear metadata
- visible methods
- evidence tables or matrices
- restrained callouts
- concise captions

Avoid:

- long uninterrupted essays
- repeated project claims
- vague headings
- generic “process” sections
- decorative cards without information value

### 12.4 Artifact rule

An artifact belongs when it proves one of the following:

- research planning
- data collection quality
- synthesis ability
- ethical reasoning
- iteration
- strategic translation

Artifacts should not be included merely because they exist.

---

## 13. Writing Style Guide

### 13.1 Voice

The writing should be:

- precise
- observant
- direct
- restrained
- evidence-aware
- intellectually modest
- specific about uncertainty

### 13.2 Preferred language

Prefer:

- “The interviews suggested…”
- “Across five participants, a recurring pattern was…”
- “I interpreted this as…”
- “This remains provisional.”
- “The prototype tested…”
- “The evidence did not establish…”
- “I would investigate this next by…”

Avoid:

- “Users need…”
- “This proves…”
- “Revolutionary”
- “Innovative”
- “Game-changing”
- “Empathetic”
- “Seamless”
- “Intuitive”
- “I am passionate about…”
- “Thought leader”
- “Expert” unless externally warranted

### 13.3 Observation labels

Use consistent labels:

- Observation
- Participant report
- Interpretation
- Design implication
- Limitation
- Hypothesis
- Future direction

### 13.4 Sentence and paragraph standards

- Prefer concrete nouns and active verbs.
- Keep paragraphs short enough to scan.
- Avoid rhetorical questions in excess.
- Use first person where authorship matters.
- Do not overuse em dashes.
- Avoid restating the same idea in different language.
- Preserve natural cadence; do not flatten the voice into corporate prose.

### 13.5 Titles

Titles should describe the actual content.

Good:

- “How ambiguity increased task-initiation friction”
- “What five interviews changed in the prototype”
- “Participation is broader than access”

Avoid:

- “The Journey”
- “The Solution”
- “The Magic”
- “Designing a Better Future”

---

## 14. Design System

### 14.1 Preserve

Preserve:

- Outfit display typography
- Inter body typography
- warm neutral background
- black primary text
- muted gray secondary text
- restrained green and purple accents
- generous white space
- large editorial headings
- low-shadow cards
- rounded geometry
- quiet pacing

### 14.2 Refine

Refine:

- reduce the number of radius values
- reduce duplicate card styles
- create consistent text widths
- create standard section spacing tokens
- create standard metadata styles
- reduce accent-color use
- remove editing comments and legacy CSS
- create a consistent button hierarchy
- distinguish content cards from evidence callouts

### 14.3 Color roles

Use color by function:

- black: primary action and primary text
- gray: metadata and secondary information
- green: research insight, constructive intervention, or validated direction
- purple: focus state, reflection, or conceptual framework
- red and amber: only for risk, friction, or caution within evidence diagrams

Do not use accent colors decoratively.

### 14.4 Typography

Recommended scale:

- Display: 64–88px desktop, 44–56px mobile
- Page title: 48–64px desktop, 38–48px mobile
- Section title: 36–52px desktop, 30–38px mobile
- Card title: 22–28px
- Body: 17–19px
- Small body: 15–16px
- Metadata: 12–14px

Maintain body line length around 60–72 characters.

### 14.5 Spacing

Use a limited spacing system based on:

- 8
- 12
- 16
- 24
- 32
- 48
- 64
- 80
- 96

Section spacing should communicate hierarchy, not simply create emptiness.

### 14.6 Imagery

Use images only when they:

- show an artifact
- demonstrate a design decision
- provide research context
- support observation practice

All images must be:

- locally hosted
- compressed
- dimensioned to prevent layout shift
- captioned where meaning is not self-evident
- provided with accurate alt text

---

## 15. Responsive Behavior

### 15.1 Breakpoints

Use content-driven breakpoints rather than device labels.

Recommended initial breakpoints:

- 1200px: wide desktop
- 960px: compact desktop / tablet landscape
- 720px: tablet / large mobile
- 480px: compact mobile

### 15.2 Navigation

Desktop:

- name/logo left
- four links right

Mobile:

- name/logo on first row
- horizontally scrollable or wrapped navigation below
- no hamburger menu unless the final architecture grows beyond five items

### 15.3 Layout behavior

- two-column editorial layouts collapse to one column below approximately 960px
- evidence matrices may become stacked cards below 720px
- large tables must support horizontal scrolling with clear labels
- prototype screens should remain legible without requiring pinch zoom
- captions should remain adjacent to images
- buttons should become full-width only when it improves touch usability

### 15.4 Mobile priority

Do not merely stack desktop content.

On mobile:

- shorten introductions
- surface summaries earlier
- reduce decorative spacing
- preserve heading hierarchy
- avoid long sequences of nearly identical cards
- keep the primary action visible without excessive scrolling

---

## 16. Accessibility Requirements

### 16.1 Standards

Target WCAG 2.2 AA.

### 16.2 Required practices

- semantic HTML
- one `h1` per page
- logical heading order
- skip link
- visible keyboard focus
- sufficient color contrast
- descriptive link text
- alt text based on function and content
- no meaning conveyed by color alone
- reduced-motion support
- responsive text without clipping
- touch targets of at least 44 by 44 CSS pixels where practical
- correct language and metadata
- accessible PDFs retained only as secondary downloads
- captions and transcripts for future media

### 16.3 Cognitive accessibility

The portfolio should model its stated research values.

Requirements:

- predictable navigation
- stable page templates
- limited choices per section
- clear page purpose
- descriptive labels
- concise summaries before long content
- consistent evidence labels
- reversible navigation
- no autoplay
- no timed interactions
- no carousels
- no animated text
- no decorative motion
- no hidden essential content

### 16.4 Testing

Before launch:

- keyboard-only review
- screen-reader spot check
- contrast audit
- 200% zoom test
- mobile viewport test
- reduced-motion test
- broken-link test
- HTML validation
- Lighthouse review used as a diagnostic, not as the sole accessibility measure

---

## 17. Technical Architecture

### 17.1 Implementation approach

Keep the site static unless a clear maintenance need justifies a build system.

Recommended initial stack:

- semantic HTML
- modular CSS
- minimal vanilla JavaScript
- no framework
- no animation library
- no CMS during the current phase

This is sufficient for the current page count and reduces maintenance burden.

### 17.2 File organization

Separate:

- page HTML
- global CSS
- page-specific CSS only where necessary
- images
- downloadable documents
- reusable icons

Avoid storing all files at the repository root.

### 17.3 CSS architecture

Create:

- design tokens
- base styles
- layout utilities
- typography components
- navigation
- buttons
- cards
- evidence patterns
- artifact patterns
- page-specific sections
- responsive rules

Remove:

- duplicate classes
- unused declarations
- inline editing comments
- overlapping responsive rules
- page-specific hacks inside global component rules

### 17.4 JavaScript

JavaScript may be used for:

- current navigation state
- optional table-of-contents behavior
- progressive enhancement

It should not be required for core content access.

### 17.5 Performance

Requirements:

- local image hosting
- modern image formats where supported
- image width and height attributes
- font-display strategy
- no unnecessary third-party scripts
- no remote prototype screenshot dependency
- no autoplay media
- minimal render-blocking resources

### 17.6 Metadata

Every page must include:

- unique title
- unique description
- canonical URL after deployment
- Open Graph title and description
- appropriate preview image
- favicon
- author attribution where relevant

---

## 18. Repository Audit Findings to Resolve in Phase 2

The formal audit should verify and resolve:

- broken `#writing` navigation references
- malformed paragraph markup in the Research Memos section
- duplicate AI bandwidth PDFs
- duplicate ethics PDFs
- remote Imgur image dependency
- inconsistent section and class naming
- legacy or duplicate CSS
- mixed About implementations
- current resume accuracy
- spelling of “Psychologie of Home Design”
- artifact privacy and anonymization
- PDF accessibility
- outdated dates or project-status language
- missing project outcomes
- unverified claims
- mobile navigation behavior
- heading structure
- unused files
- asset compression
- link targets and rel attributes
- page metadata
- GitHub Pages path behavior

No code changes should begin until this audit is documented and approved.

---

## 19. Implementation Roadmap

### Phase 1 — Specification

**Deliverable:** Approved Portfolio Design & Implementation Specification v1.0

**Complete when:**

- architecture is approved
- scope is approved
- Observation decision is approved
- design-system direction is approved
- acceptance criteria are approved

### Phase 2 — Repository audit

**Deliverable:** Repository Audit and Change Map

Includes:

- file inventory
- content inventory
- code-quality findings
- accessibility findings
- broken links
- duplication
- page-by-page retain / revise / remove decisions

### Phase 3 — Research architecture

**Deliverable:** Research section structure and content model

Includes:

- Research overview
- Neuroinclusive Environments page outline
- memo page template
- evidence-label system
- publication metadata model

### Phase 4 — Memo conversion

**Deliverable:** Complete HTML replacement pages for approved memos

Includes:

- editorial review
- citations
- structured headings
- PDF downloads
- related-work links

### Phase 5 — Scaffold artifacts

**Deliverable:** HTML artifact pages and revised Scaffold evidence architecture

Priority:

1. synthesis
2. usability findings
3. interview guide
4. ethical constraints

### Phase 6 — Observation section

**Deliverable:** One restrained Observation page

Proceed only if the approved content still strengthens hiring coherence after the research pages are complete.

### Phase 7 — Responsive refinement

**Deliverable:** Consistent behavior across target viewport ranges

### Phase 8 — Accessibility and polish

**Deliverable:** Tested, validated, launch-ready portfolio

Includes:

- accessibility review
- content QA
- technical QA
- performance review
- final link and metadata check

---

## 20. Scope Boundaries

### 20.1 In scope

- clarifying the research identity
- restructuring navigation
- revising the homepage
- strengthening Scaffold
- creating the Research architecture
- converting selected PDFs to HTML
- adding the Neuroinclusive Environments Project
- adding a small Observation section if justified
- responsive and accessibility refinement
- technical cleanup

### 20.2 Out of scope for current implementation

- full visual redesign
- custom CMS
- React or other framework migration
- animation system
- blog
- newsletter
- full photography portfolio
- full poetry archive
- personal journal
- multiple additional case studies without equivalent evidence
- custom analytics dashboard
- interactive research database
- publication platform
- complex filtering
- dark mode
- elaborate data visualization
- speculative AI features

These may be reconsidered only when new evidence shows a meaningful hiring benefit.

---

## 21. Future Roadmap

Future additions may include:

- a second substantial research case study
- practitioner interviews from the Neuroinclusive Environments Project
- a tested participation framework
- working-paper publications
- a research talk or conference presentation
- a concise downloadable portfolio PDF
- employer-specific landing pages
- project outcome updates
- a private interview presentation deck

These are not current commitments.

The next major addition after the current roadmap should be a second credible research case study, not additional decorative or editorial content.

---

## 22. Portfolio Governance

### 22.1 Decision filter

Before adding anything, ask:

1. What hiring uncertainty does this reduce?
2. What evidence does it add?
3. Does it strengthen the core research identity?
4. Can it be understood quickly?
5. Is it more valuable than the implementation and maintenance cost?
6. Does it duplicate an existing page or idea?
7. Would removing it make the portfolio weaker?

If the answers are unclear, do not add it.

### 22.2 Diminishing-return rule

Stop refining when:

- the page is accurate
- the page is accessible
- the hierarchy is clear
- the evidence is sufficient
- additional work is primarily decorative
- another week of effort would not materially increase interview probability

### 22.3 Change control

Major changes require:

- proposed change
- hiring rationale
- affected pages
- implementation cost
- maintenance cost
- risk
- acceptance criteria

### 22.4 Versioning

Use semantic document versions:

- 1.0: approved governing specification
- 1.1: minor clarifications
- 1.2: approved content or behavior refinements
- 2.0: substantial architecture or positioning change

Implementation decisions that materially depart from this specification must be documented.

---

## 23. Global Acceptance Criteria

The portfolio is ready for launch when:

### Hiring clarity

- Abby’s target research identity is clear within the first screen
- the primary case study is easy to find
- the ongoing research initiative is clearly differentiated from completed project work
- the career transition reads as coherent
- evidence is stronger than self-description

### Research credibility

- methods are visible
- participant scope is accurate
- findings are not overstated
- observation and interpretation are separated
- limitations are present
- design decisions trace back to evidence
- research artifacts are accessible and useful

### Conceptual coherence

- Scaffold, memos, and Neuroinclusive Environments share a visible concern with participation, cognitive effort, and system demands
- Observation supports that identity without competing with it
- no page feels like an unrelated creative detour

### Usability

- navigation is predictable
- labels are unambiguous
- content is scannable
- links work
- page hierarchy is consistent
- mobile content remains legible
- essential evidence is not trapped in PDFs

### Accessibility

- WCAG 2.2 AA requirements are substantially met
- keyboard navigation works
- focus is visible
- heading hierarchy is correct
- contrast is sufficient
- images have appropriate alt text
- motion is unnecessary or reduced

### Maintainability

- repository structure is clear
- files are local and organized
- CSS is modular
- duplication is removed
- no page depends on fragile external assets
- complete replacement files exist for every implemented change

### Scope discipline

- no unnecessary pages
- no decorative feature without hiring value
- no unapproved redesign
- no blog architecture
- no full art or poetry portfolio
- no implementation beyond the approved phase

---

## 24. Approval Decisions Required

Before implementation begins, approve or revise these decisions:

1. Use **Work / Research / About / Resume** as primary navigation.
2. Remove Scaffold from permanent top-level navigation.
3. Position the Neuroinclusive Environments Project as an ongoing research initiative.
4. Convert selected PDFs into native HTML.
5. Retain PDFs as secondary downloads.
6. Replace or relabel the Alex persona.
7. Use the observation–interpretation–design implication pattern throughout Scaffold.
8. Include one subordinate Observation page.
9. Use the Relative diptych as the primary visual evidence on that page.
10. Use only a short excerpt of “May, 2024” rather than publishing it prominently in full.
11. Keep the implementation static and framework-free.
12. Defer all redesign, animation, CMS, blog, and publication-platform work.

---

## 25. Revision History

| Version | Date | Status | Summary |
|---|---|---|---|
| 1.0 | 2026-08-11 | Approved | Initial canonical design and implementation specification based on the repository, Neuroinclusive Environments Master Project Charter, Relative diptych, and “May, 2024.” |


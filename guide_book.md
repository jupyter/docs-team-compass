# Docs Working Group Guide Book

This Guide Book aims to provide help for contributors by offering advice and best practices that they can use during their work. It also aims to guide decisions and operations of the Docs Working Group as a whole.

## Best Practices

- Prefer plain language
    - Helps improve accessibility to a wide range of people with different backgrounds
    - Recommendations:
        - Where jargon is used, define it in-document or link out to a glossary or other source
- Use deep page heirarchies
    - Deep heirarchies can provide detail without overwhelming readers (with length and complexity)...think Wikipedia page structure
    - They can provide easier to read and understand, focused, single-topic documents
    - Recommendations:
        - Break up long documents into separate parts where feasible
        - Structure complex information into separate, focused topics where feasible
- Prefer interlinking between pages within a subproject or topic, and to other projects
    - Project Jupyter (meta) docs in particular are relevant to many subprojects and are a good target for interlinking
    - Breaking up a topic into small focused documents and interlinking them can provide the same information in an easier to read form
- Key Docs pages should be checked before release, so that essential information is not broken, which creates bas experiences (especially for new users)

## Insights, Challenges and Opportunities

This Docs Working Group has identified some insights and challenges (and related opportunities) that will help guide our work:

- Users often express that it's challenging to get a unified view of "what is Jupyter" and how the components work together.
    - We should work to remedy this and provide more explanation and context in appropriate places.
- Jupyter's modular approach (from The Big Split) can make it difficult to communicate the right information in the right place. Insights from one project can be relevant to other subprojects, and some information spans multiple subprojects.
    - We should encourage consistency and cross-linking across the Jupyter ecosystem and between different subprojects.
    - Create a docs page that links to all projects and their user-facing documentation (This page will help provide an easy way to link out to the different subproject's docs).
- There should be multiple ways to consume docs, through multiple points of delivery.

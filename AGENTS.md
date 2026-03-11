```md id="4vel7g"
# AGENTS.md

## Project identity
This repository is for a premium bilingual law firm website based in Chile.

The site is a modern legal services website focused on:
- Civil Law / Business Law as flagship
- Labor Law
- Tax And Tributes

Secondary practice areas may exist in the CMS but remain hidden from the public until fully ready:
- Penal Law
- Administrative Law
- Family Law

## Business goals
The website must do two things well:
1. Generate qualified leads and consultations
2. Build long term authority through SEO and AEO driven content

The primary lead action is:
- WhatsApp general chat

The secondary lead action is:
- calendar booking

## Audience priority
Primary audience order:
1. established companies
2. foreign investors
3. startups
4. HR teams

Secondary audience:
- high income individuals in strategically relevant matters

## Geographic priority
Primary geographic focus:
- Concepción
- Los Ángeles
- Temuco
- Valdivia
- Osorno
- Puerto Varas
- Puerto Montt

Wider regional relevance:
- Biobío
- La Araucanía
- Los Ríos
- Los Lagos

International support:
- English pages for clients from Canada, the United States, and Europe

## Brand and tone rules
The site must feel:
- corporate and premium first
- close and human second
- commercially intelligent
- calm under pressure
- practical and strategic

Avoid:
- generic law firm language
- overly academic writing
- aggressive or flashy sales tone
- informal or trendy copy
- cluttered layouts

## Product rules
The public site should include:
- Inicio
- Servicios
- Equipo
- Contenido
- Contacto
- ES / EN language switch

The site must support:
- homepage
- services hub
- service detail pages
- content hub
- articles
- legal updates
- guides
- FAQ content
- team page
- contact page
- legal pages
- location aware pages
- trust sections
- bilingual support

## Critical content visibility rules
All planned sections, subpages, and future content types may exist in the CMS from the start, but must remain hidden from the public until they are fully ready.

This rule applies to:
- secondary practice areas
- location pages
- future media appearances
- publications
- notable cases
- any empty section
- any thin page
- any draft content

Hidden or incomplete content must:
- stay out of navigation
- stay out of footer links
- stay out of sitemap
- stay out of indexing
- stay out of related-content modules unless in preview mode

## Stack rules
Preferred stack:
- Next.js App Router
- TypeScript
- Sanity CMS
- Vercel
- optional Cloudflare later

Use:
- reusable templates
- structured CMS driven content
- clean server-first architecture where appropriate
- minimal dependencies
- accessible components
- mobile first responsive design

Avoid:
- plugin heavy architecture
- unnecessary custom backend complexity
- overengineering for a solo operator
- hardcoded page specific content when a template should be used

## CMS rules
The CMS must visually support editing for a solo operator.

Content types should include:
- site settings
- navigation
- homepage sections
- service pages
- location pages
- articles
- legal updates
- guides
- FAQs
- testimonials
- client logos
- biography blocks
- trust metrics
- contact settings
- media appearances
- publications
- notable cases

Each relevant content type should support:
- visibility toggle
- language support
- SEO fields
- relationships to related content
- preview friendly behavior

## Localization rules
Spanish is the primary language.
English is secondary.

Requirements:
- Spanish first architecture
- English only where content is ready
- language aware metadata
- hreflang support
- per language publication control
- graceful fallback when English content does not exist

Do not force full English parity at launch.

## Homepage rules
The homepage must follow this hierarchy:
1. firm identity and premium positioning
2. main legal services
3. results oriented message for companies and employers

The homepage should include:
- hero
- primary WhatsApp CTA
- secondary booking CTA
- logo strip
- services overview
- why clients hire the firm
- testimonials and trust signals
- biography or founder trust block
- content preview
- final CTA

## Service architecture rules
The service priority order is:
1. Civil Law / Business Law
2. Labor Law
3. Tax And Tributes

Secondary order:
4. Penal Law
5. Administrative Law
6. Family Law

Labor Law must appear before Tax And Tributes.
Family Law must appear last among secondary practice areas.

Civil Law / Business Law must act as the central internal linking hub.

## Content strategy rules
The content hub must unify:
- articles
- legal updates
- guides
- FAQ explainers
- strategic commentary

Content strategy must prioritize:
- business decision makers
- HR teams

Secondary content can support:
- high income individuals in relevant matters

Every content piece should:
- answer a real client problem
- support SEO and AEO
- link to a relevant service page
- contain a natural CTA
- feel premium and practical
- avoid filler and generic text

## SEO rules
SEO should prioritize regional visibility before broad national visibility.

Primary SEO focus:
- city plus service intent
- region plus service intent
- pillar and cluster architecture
- FAQ and AEO structure
- high intent legal business topics

Implement:
- metadata per page
- sitemap
- canonical tags
- hreflang
- breadcrumb support
- schema ready content
- noindex controls
- strong internal linking

## Analytics rules
Launch analytics stack:
- Google Analytics
- Google Search Console

Track:
- WhatsApp clicks
- calendar booking clicks
- form submissions
- article to service clicks
- article to WhatsApp clicks
- language switch usage
- key CTA interactions by page and section

Staging should not pollute production analytics.

## Contact rules
Primary contact method:
- WhatsApp general chat

Secondary:
- calendar booking

A short contact form may also exist.

Do not implement page specific WhatsApp message variants as the main flow.
All WhatsApp CTAs should open the same general chat destination.

## Trust rules
Trust assets are critical and should be structured in the CMS.

Initial trust elements:
- client logos
- testimonials
- biography
- years of experience

Future hidden trust elements:
- media appearances
- publications
- notable cases

All trust content must respect legal discretion and confidentiality.

## Design and UX rules
Design should be:
- minimal
- elegant
- premium
- readable
- conversion oriented

Use:
- strong spacing
- restrained visual language
- clear CTA hierarchy
- high readability for long form content
- accessible interaction states

Avoid:
- noisy layouts
- carousel heavy design unless justified
- decorative clutter
- generic stock-lawyer visuals

## Engineering workflow rules
Before implementing any major change:
1. read docs/system-design.md
2. read docs/build-phases.md
3. follow this AGENTS.md file

When implementing:
- do one ticket at a time
- summarize files changed
- explain decisions made
- list manual setup steps if needed
- keep implementation aligned with the approved architecture

When unsure:
- choose the simpler architecture that best supports a solo operator
- prefer reusable templates over one off code
- prefer structured content over hardcoded content
- prefer hidden unpublished content over exposed incomplete content

## Definition of success
A successful implementation is one where:
- the site feels premium and credible
- the owner can update it easily through the CMS
- WhatsApp lead capture works consistently
- SEO and AEO foundations are strong
- the site can grow organically without feeling unfinished
- bilingual support is clean and controlled
- staging and production are clearly separated
```

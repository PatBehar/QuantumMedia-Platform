# Codex Master Prompt

You are building the first demo of QM Media Platform, a web-only, mobile-first digital media platform for radio stations, sports media outlets and news publishers.

Use La Red 106.1 as the demo client.

This is not a native app. This is a responsive web platform optimized for mobile-first viewing.

Build a polished presentation-ready frontend demo using:

- Next.js
- TypeScript
- Tailwind CSS
- App Router
- Local mock data only

Do not connect real APIs.
Do not add real authentication.
Do not create a real database.
Do not add backend complexity.
Do not use lorem ipsum.
Do not mention MVP anywhere in the UI.

The goal is to create a premium mobile-first demo that shows how La Red’s website could become a digital media platform for live radio, sports, news, audience engagement and monetization.

## Required Routes

1. `/`
2. `/live`
3. `/matches`
4. `/programming`
5. `/article/municipal-refuerza-apertura-2025`
6. `/admin/editorial-assistant`
7. `/advertisers`
8. `/proposal`

## Required Components

- MobileHeader
- BottomNav
- LiveMiniPlayer
- LiveHeroPlayer
- HeroStory
- BreakingTicker
- NewsCard
- MatchCard
- FeaturedMatchCard
- ProgramCard
- ClipCard
- ArticleLayout
- EditorialAssistantDemo
- SponsorCard
- SectionHeader
- CTAButton

## Design Direction

- Premium sports media platform
- Mobile-first
- Strong editorial hierarchy
- Red, black, white and subtle gray palette
- Bold typography
- Rounded cards
- Sticky live player
- Bottom mobile navigation
- Clear Spanish UI labels
- High contrast
- Fast loading
- Clean spacing
- Professional enough to show to a media executive

## Brand

- Name: La Red 106.1
- Concept: Pasión por Guatemala
- Main CTA: EN VIVO
- Tone: sports, news, radio, urgent, modern, credible

## Home Screen Requirements

- Header with La Red 106.1 brand
- Red EN VIVO button
- Sticky mini live player
- Hero story
- Breaking news ticker
- Partidos de Hoy section
- Lo Más Reciente section
- Programas section
- Sponsored / Marcas section
- Bottom navigation

## Live Screen Requirements

- Large live player
- Current program
- Waveform-style visual
- YouTube/live video placeholder
- Sigue después section
- WhatsApp, YouTube and Cabina buttons
- Momentos Destacados clips
- Participa CTA

## Matches Screen Requirements

- Filters: Hoy, En Vivo, Resultados, Próximos
- Featured live match card
- Match list
- Results section
- Standings/table section
- CTA: Escuchar narración

## Programming Screen Requirements

- Day selector
- Current show highlighted
- Program cards with time, host and description
- Próximos especiales section

## Article Screen Requirements

- Category
- Headline
- Featured image placeholder
- Byline/date
- Escuchar resumen button
- Article body
- Highlight quote block
- Share buttons
- Related articles
- Live mini player

## Editorial Admin Demo Requirements

Create a visual admin/demo screen that shows how an editor could paste a source text or URL and generate:

- Suggested headline
- Summary
- Category
- Tags
- SEO title
- Meta description
- Facebook caption
- Instagram caption
- X caption
- Status: Pending human review

This can be simulated with local state and mock output. It does not need real AI integration.

## Advertisers Screen Requirements

- Explain sponsorship opportunities
- Sponsored sections
- Match sponsorship
- Program sponsorship
- Branded content
- Digital banners
- Monthly reporting
- CTA: Solicitar media kit

## Proposal Page Requirements

Build a polished proposal page for La Red Digital Platform using the same visual system as the demo. It should feel like a premium pitch deck in web format, mobile and desktop responsive, with sections for:

1. Cover
2. Opportunity
3. Current gap
4. Vision
5. Platform modules
6. Demo preview
7. AI editorial automation
8. Sports and live experience
9. Monetization
10. Implementation scope
11. Investment: Q80,000
12. Monthly platform management: USD 1,000/month
13. Next steps

## Mock Data

Create local files for:

- news
- matches
- programs
- clips
- sponsors
- categories
- proposal

Use realistic Spanish content related to Guatemala, sports, radio and news. Avoid copyrighted real article copy. Use fictional but believable content.

## Technical Requirements

- The app must run locally with `npm install` and `npm run dev`.
- The UI must be responsive, but mobile-first is the priority.
- Keep the code clean and componentized.
- Add a README with setup instructions and project overview.
- Make the project easy to deploy on Vercel.
- Do not over-engineer.

## Final Result

A polished mobile-first web demo that can be shown on an iPhone to present the concept of La Red Digital Platform.
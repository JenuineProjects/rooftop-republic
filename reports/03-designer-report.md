# Rooftop Republic: Landing Page Design Specification

**Agent 03 -- Senior UX & Product Designer**
**Project:** 10,000 Hours of Play Challenge -- Rooftop Republic Landing Page
**Date:** 31 March 2026

---

## Preamble

This document is the complete design specification for the Rooftop Republic landing page. Every decision here is informed by two source documents: the Gamification Expert's Octalysis strategy (Agent 01) and the Urban Farming Expert's domain reality (Agent 02). My job is to translate strategy and context into a concrete, buildable, human-centred page that a developer can implement directly.

The organising principle behind every choice: **the page IS the experience.** For most visitors, this is their first and only contact with Rooftop Republic. It must do the work of brand, story, community proof, and conversion in a single scroll. Every pixel, every word, every transition serves one purpose -- moving the visitor from "that's not for me" to "I could do that" to "I'm doing it this Saturday."

---

# PART 1: SOLUTION DESIGN

---

## 1. User Journey & Emotional Arc

The visitor's emotional state is the invisible architecture of this page. Every section is designed to produce a specific feeling at a specific moment. Here is the emotional arc mapped to scroll depth.

### Scroll Position 0% -- Arrival (0-3 seconds)
**Emotional state:** Neutral to mildly curious. Possibly sceptical. Likely arrived via social media link on mobile.
**Internal monologue:** "What's this then?"
**Design goal:** Stop the thumb. Earn 5 more seconds. The hero must be visually arresting and emotionally resonant -- a real Dublin rooftop, real people, grey sky. Not a stock photo. Not California.

### Scroll Position ~10% -- The Hook (3-8 seconds)
**Emotional state:** Curiosity stirring. The counter ("40 rooftops and growing") and the epic framing create a flicker of interest.
**Internal monologue:** "Forty rooftops? In Dublin? How does that work?"
**Design goal:** Convert curiosity into continued scrolling. The visitor must feel there is something worth discovering below the fold.

### Scroll Position ~20% -- The Identity Shift (8-20 seconds)
**Emotional state:** The "not for me" filter is active. This is the most dangerous moment -- the visitor is deciding whether this is relevant to their life.
**Internal monologue:** "This is probably for eco types with big gardens and loads of free time."
**Design goal:** Shatter that assumption. The direct statement ("You don't need to know anything about gardening. You don't need a rooftop.") paired with diverse imagery must flip the filter from "not for me" to "wait, maybe."
**THIS IS THE CRITICAL INFLECTION POINT.** If the design fails here, nothing below matters.

### Scroll Position ~35% -- Recognition (20-45 seconds)
**Emotional state:** Warming. The micro-stories introduce people the visitor can identify with. The objection-busting section validates their doubts and then dissolves them.
**Internal monologue:** "That woman in Phibsborough started with a basil plant? I could do that."
**Design goal:** Build confidence through social proof and honesty. Each story and each answered objection is a small psychological win.

### Scroll Position ~50% -- Confidence (45-75 seconds)
**Emotional state:** The flip has happened. The visitor now believes they could do this. The Herb Pot Challenge feels achievable. The "What Can I Grow?" tool gives them a personalised answer.
**Internal monologue:** "Fifteen minutes and ten euro? I could literally do that on Saturday."
**Design goal:** Convert confidence into intent. This is where gentle seasonal urgency ("spring planting starts now") nudges intent into decision.

### Scroll Position ~70% -- Aspiration (75-100 seconds)
**Emotional state:** Engaged and forward-looking. The growing journey and map show what comes after the first pot -- a community, a progression, a neighbourhood rooftop.
**Internal monologue:** "There's one in Stoneybatter? That's five minutes from me."
**Design goal:** Expand the vision beyond the first step. Show the community the visitor is about to join.

### Scroll Position ~90% -- Resolve (100-120 seconds)
**Emotional state:** Ready to act. The final CTA is a confirmation of a decision already made, not a new ask.
**Internal monologue:** "Right. I'm doing this."
**Design goal:** Make the action effortless. One clear button. No friction.

### The Emotional Arc in Summary
**Wonder** (hero) --> **Challenge to assumptions** (identity shift) --> **Recognition** (stories) --> **Confidence** (objections answered) --> **Intent** (herb pot challenge) --> **Excitement** (interactive tool) --> **Aspiration** (journey + map) --> **Resolve** (final CTA)

This arc follows the Kano model trajectory: from basic expectations (is this relevant?) through performance needs (can I do it?) to delight (I want to start now). It also maps directly to the four Octalysis experience phases: Discovery (hero), Onboarding (identity + stories + objections), Scaffolding (challenge + tool), Endgame (journey + map + CTA).

---

## 2. Page Structure -- Section-by-Section Blueprint

### Section 1: Hero -- "Dublin's Rooftops Are Waking Up"

**Purpose:** Establish the mission, set the visual tone, stop the scroll.

**Octalysis Core Drives:** CD1 (Epic Meaning & Calling), CD7 (Curiosity)

**Emotional shift:** From neutral/sceptical --> intrigued

**Content requirements:**
- Full-viewport background image: a real Dublin rooftop garden. Must show grey/overcast sky, Dublin brick buildings in background, slightly imperfect plants in containers, and at least 2-3 diverse people. The image should feel like a candid moment, not a posed photo shoot.
- Headline overlay (large, high contrast): "Dublin Has Thousands of Empty Rooftops. We're Turning Them Into Gardens."
- Animated counter: "40 Rooftops. 250+ Growers. One City. Growing."
- A single subtle scroll indicator (animated down-chevron) to invite further exploration.
- NO call to action. No buttons. No forms. Just the hook.

**Approximate viewport height:** 100vh (full screen). The hero must dominate the first impression.

**Visual hierarchy:** Image > Headline > Counter > Scroll indicator

---

### Section 2: The Identity Shift -- "This Is For You"

**Purpose:** Destroy the "not for me" perception before it calcifies.

**Octalysis Core Drives:** CD5 (Social Influence & Relatedness), CD1 (Epic Meaning)

**Emotional shift:** From "not for me" --> "wait, maybe..."

**Content requirements:**
- A bold, direct statement: "You don't need to know anything about gardening. You don't need a big rooftop. You don't even need a rooftop. You need a pot, some soil, and ten minutes this Saturday."
- 4-5 small circular portrait photos showing diversity: young professional, family with kids, older person, person from immigrant community, student-age person. These should feel warm and candid, not corporate headshots.
- A supporting line: "Our growers include software engineers, retired teachers, nurses, builders, students, and parents. The common thread isn't a green thumb -- it's curiosity."

**Approximate viewport height:** 50-70vh. Compact and punchy. This section should not require scrolling on its own -- the statement must land in a single view.

**Visual hierarchy:** Statement (largest text on the page after the hero headline) > Portrait photos > Supporting line

---

### Section 3: The Micro-Stories -- "People Like You Already Do This"

**Purpose:** Social proof through narrative. Let the visitor find someone like themselves.

**Octalysis Core Drives:** CD5 (Social Proof & Relatedness), CD7 (Curiosity), CD2 (Vicarious Achievement)

**Emotional shift:** From "maybe" --> "if they can do it..."

**Content requirements:**
- 4 story cards, each featuring one micro-story from the Urban Farming Expert's report:
  1. Niamh's basil (young professional, Phibsborough)
  2. Declan & Roisin's kale (family, Rathmines)
  3. Tomasz's tomatoes (immigrant community, Smithfield)
  4. Margaret's raised bed (retiree, Stoneybatter)
- Each card contains: a photo/illustration, a one-line hook ("Niamh bought a EUR 1.99 basil plant from Tesco..."), and an expandable "Read more" that reveals the full story.
- Cards should be swipeable on mobile (horizontal scroll/carousel) and a 2x2 or 4-column grid on desktop.

**Approximate viewport height:** 80-100vh depending on expansion state.

**Visual hierarchy:** Hook line (draws the eye) > Photo > "Read more" interaction

---

### Section 4: "Yeah, But..." -- Objection Busting

**Purpose:** Validate and then dissolve the visitor's real doubts.

**Octalysis Core Drives:** CD2 (Accomplishment -- each objection overcome is a win), CD3 (Empowerment through knowledge)

**Emotional shift:** From doubt --> confidence

**Content requirements:**
- Section heading: "Yeah, But..."
- 6 expandable accordion items, each an objection and its honest answer:
  1. "I kill every plant I've ever owned."
  2. "Dublin weather is too miserable for growing."
  3. "I don't have time."
  4. "I'm renting -- my landlord won't allow it."
  5. "It'll cost a fortune to set up."
  6. "What if I start and then lose interest?"
- Each answer should be 2-3 sentences, drawn from the Urban Farming Expert's Section 4, in a warm, slightly humorous Dublin tone.
- The first item should default to open (reducing the cognitive load of understanding the interaction pattern -- this is Hick's Law in action).

**Approximate viewport height:** 60-80vh (collapsed state). Expands as items are opened.

**Visual hierarchy:** Section heading > Objection questions (bold) > Answer text (regular weight)

---

### Section 5: The Herb Pot Challenge -- "Start This Weekend"

**Purpose:** THE conversion moment. Present the smallest possible first step as a clear, completable quest.

**Octalysis Core Drives:** CD2 (Clear Challenge), CD4 (Ownership), CD6 (Seasonal Urgency), CD3 (Creative Empowerment)

**Emotional shift:** From "I could do this" --> "I'm going to do this"

**Content requirements:**
- Visually distinct "challenge card" that breaks the page rhythm -- a slightly different background colour (warm, inviting), rounded corners, a subtle border or shadow to lift it from the page.
- Headline: "The Herb Pot Challenge"
- Subhead: "Plant one pot this weekend. That's it. That's the whole first step."
- Three simple steps with icons:
  1. "Grab a pot (a saucepan works), fill it with compost (EUR 4 from any garden centre)"
  2. "Plant a supermarket herb (EUR 2 basil, parsley, or mint) or sprinkle in a packet of seeds"
  3. "Put it on your windowsill, balcony, or doorstep. Water when the soil feels dry."
- Key stats displayed as large, bold figures: "EUR 10 total" | "15 minutes" | "First harvest: 2-4 weeks"
- Seasonal nudge line: "It's spring. The growing window is open. Your first harvest could be ready by June."
- Primary CTA button: "Save the Challenge" (downloads/saves the instructions, or scrolls to a shareable anchor)
- Secondary text link: "Share with a friend"

**Approximate viewport height:** 80-100vh. This is a full moment. Give it space.

**Visual hierarchy:** Headline > Three steps > Stats > CTA button > Seasonal nudge

---

### Section 6: "What Can I Grow?" -- Interactive Recommender Tool

**Purpose:** Give the visitor a personalised, interactive experience that transforms them from reader to participant.

**Octalysis Core Drives:** CD3 (Creativity & Feedback), CD7 (Curiosity), CD4 (Personalisation)

**Emotional shift:** From intent --> excitement ("look at all the things I could grow!")

**Content requirements:**
- A 3-step interactive tool:
  - Step 1: "What space do you have?" -- three visual options: Windowsill | Balcony | Rooftop
  - Step 2: "Have you grown anything before?" -- three options: Never | A little | I know my way around
  - Step 3: "What sounds good?" -- four options: Fresh herbs | Salad greens | Vegetables | Surprise me
- Output: A personalised "growing card" showing 3-5 specific plants with a one-line tip each ("Basil -- pick leaves from the top to encourage bushy growth"), a seasonal note ("plant now, harvest by June"), and a small illustration or icon for each plant.
- "Try again" link to re-run with different inputs.

**Approximate viewport height:** 80-100vh. The tool needs room to breathe, especially the output card.

**Visual hierarchy:** Question > Options (large, tappable) > Output card

---

### Section 7: The Growing Journey -- Visual Progression Path

**Purpose:** Show the full staircase from first pot to community leader. Create aspiration without intimidation.

**Octalysis Core Drives:** CD2 (Progression Path), CD1 (Mission), CD5 (Community Endgame)

**Emotional shift:** From "I'll try the first step" --> "there's a whole journey here"

**Content requirements:**
- A visual path or staircase showing 6 steps:
  1. "Plant a Pot" (this weekend, EUR 10, 15 min)
  2. "Share a Photo" (show it off, join the community)
  3. "Drop In on a Saturday" (meet your neighbours, free, no commitment)
  4. "Claim Your Patch" (your own containers at a community rooftop)
  5. "Become a Regular" (seasonal rhythms, shared harvests)
  6. "Start a Rooftop" (bring the mission to your building)
- Each step has a small icon, a title, and a one-line description.
- Step 1 is visually highlighted as "You are here."
- Steps 4-6 are slightly desaturated or marked as "what comes next" to show progression without pressure.
- The overall visual should read as a gentle upward path, not a rigid funnel.

**Approximate viewport height:** 70-90vh.

**Visual hierarchy:** "You are here" marker on Step 1 > Step titles > Step descriptions > Later steps (faded)

---

### Section 8: The Dublin Rooftop Map -- "Find Your Nearest Rooftop"

**Purpose:** Make the community tangible and local. Proximity drives action.

**Octalysis Core Drives:** CD5 (Local Community), CD4 (Neighbourhood Ownership), CD6 (Proximity Urgency)

**Emotional shift:** From abstract interest --> "there's one near me!"

**Content requirements:**
- A stylised, illustrated map of Dublin showing neighbourhood regions (not a Google Maps embed -- too heavy, too generic, and wrong visual tone).
- Clickable/tappable neighbourhood regions: Stoneybatter, Phibsborough, Smithfield, Rathmines, Portobello, Docklands, The Liberties, and others with active sites.
- On click/tap, a small info card appears showing: neighbourhood name, number of growers, what's growing there now, and next drop-in date.
- A supporting stat: "40 rooftops across Dublin. Is there one near you?"
- Fallback for areas without sites: "No rooftop here yet? You could be the first. Get in touch."

**Approximate viewport height:** 80-100vh.

**Visual hierarchy:** Map (central, dominant) > Info cards on interaction > Supporting stat

---

### Section 9: The Seasonal Strip -- "What's Growing Right Now"

**Purpose:** Make the page feel alive and time-relevant. Show that gardening is a year-round, evolving activity.

**Octalysis Core Drives:** CD7 (Curiosity), CD3 (Living Creative Activity), CD6 (Seasonal Time Sensitivity)

**Emotional shift:** From general interest --> "right now is a good time"

**Content requirements:**
- A horizontal, scrollable timeline of all 12 months.
- The current month is visually highlighted (larger, different background colour, expanded by default).
- Each month shows 2-3 key activities: what to sow, what to harvest, what's happening in the community.
- Winter months are honest: "Garlic sits quietly. Plan next year. Seed swaps and community meetups."
- Touch-scrollable on mobile, click-scrollable or fully visible on wide desktop.

**Approximate viewport height:** 50-60vh. This is a supplementary information section, not a full moment.

**Visual hierarchy:** Current month (highlighted) > Adjacent months > Activity text within each month

---

### Section 10: The "Dublin Can Grow" Collective Goal Tracker

**Purpose:** Frame individual action as part of a collective achievement.

**Octalysis Core Drives:** CD1 (Epic Collective Mission), CD5 (Group Quest), CD2 (Progress Toward Goal)

**Emotional shift:** From "my pot" --> "our city"

**Content requirements:**
- A large, visually striking progress bar showing progress toward a community goal: "Dublin's rooftops have grown [X] kg of food this year. Goal: 1,000 kg."
- The current progress number should animate (count up) when scrolled into view.
- Supporting text: "Every pot counts. Every rooftop contributes. Every grower is part of the number."
- The visual style should feel communal -- warm colours, rounded shapes, the opposite of a corporate KPI dashboard.

**Approximate viewport height:** 40-50vh. Compact and impactful.

**Visual hierarchy:** Progress bar > Current number (animated) > Goal number > Supporting text

---

### Section 11: Final Call to Action -- "Your Move"

**Purpose:** The closing. One clear action for the visitor who has scrolled this far.

**Octalysis Core Drives:** CD1 (Mission Reminder), CD2 (First Step), CD5 (Join Community), CD6 (Now)

**Emotional shift:** From "I want to do this" --> "I'm doing this"

**Content requirements:**
- A clean, spacious section with a strong background (the hero image softly blurred, or a warm solid colour).
- Headline: "40 Rooftops and Growing. Be Part of the Next 160."
- Subhead: "Start with one pot. See what happens."
- Primary CTA button: "Start This Weekend" (scrolls back to the Herb Pot Challenge card or opens a shareable version)
- Secondary links: "Find a drop-in near you" | "Share this page"
- A final line of warmth: "See you on the rooftop."

**Approximate viewport height:** 60-70vh. Generous whitespace. Let the CTA breathe.

**Visual hierarchy:** Headline > CTA button (largest interactive element on the page) > Subhead > Secondary links > Closing line

---

### Section 12: Footer

**Purpose:** Standard footer with Rooftop Republic info and the academic "Agents Used" tab.

**Content requirements:**
- Rooftop Republic logo/wordmark, brief tagline, social links (Facebook, Instagram).
- Contact information or link.
- A clearly labelled tab or expandable section: "How This Page Was Built: The AI Agents Behind This Project" (see Section 3 below for full specification).
- Copyright line.

**Approximate viewport height:** Variable. Compact footer + expandable academic section.

---

## 3. The "Agents Used" Academic Tab

This section lives at the very bottom of the page, within or just above the footer. It is an expandable panel triggered by a clearly labelled button: "How This Page Was Built -- The 5 AI Agents."

### Design Rationale
This is an academic/methodology disclosure. It must be visually consistent with the rest of the page (same fonts, colours, spacing) but clearly distinguished as meta-content -- not part of the Rooftop Republic experience. A subtle visual shift (slightly different background, a thin top border, or a small "academic note" label) signals the change in context.

### Layout
When expanded, the section shows 5 agent cards in a vertical stack (mobile) or a horizontal row with wrapping (desktop). Each card contains:

1. **Agent number and role** (e.g., "Agent 01 -- Gamification Expert")
2. **A one-sentence description of their expertise**
3. **Their contribution to this project** (2-3 bullet points)
4. **How they influenced the final page** (1-2 sentences connecting their work to specific visible elements)

### The Five Agents

**Agent 01 -- Gamification Expert (Octalysis Framework & Games for Good)**
- Expertise: Specialist in Yu-kai Chou's Octalysis Framework, Jane McGonigal's games-for-good philosophy, and motivational design for social impact.
- Contribution: Mapped all 8 core drives to the Rooftop Republic challenge. Designed the visitor journey across 4 experience phases. Specified 6 interactive gamification elements. Established the 80/20 White Hat/Black Hat balance.
- Page influence: The page structure, emotional arc, interactive recommender tool, challenge card format, counter animations, and the deliberate placement of urgency only at conversion points all come from this agent's strategy.

**Agent 02 -- Urban Farming & Community Domain Expert**
- Expertise: 8+ years in community growing projects, deep knowledge of Dublin's urban farming landscape, seasonal growing realities, and community engagement patterns.
- Contribution: Diagnosed the psychological barriers (identity, fear of failure, knowledge gap, time perception, rooftop suitability). Provided 5 detailed target personas. Created 6 micro-stories grounded in real Dublin contexts. Designed the "First Step Strategy" staircase. Provided seasonal growing data and realistic cost breakdowns.
- Page influence: The micro-stories, the "Yeah But..." objections, the Herb Pot Challenge specifics (EUR 10, 15 minutes, this weekend), the seasonal calendar content, the Dublin neighbourhood framing, and the insistence on authentic rather than stock imagery all originate from this report.

**Agent 03 -- UX & Product Designer**
- Expertise: 12+ years designing landing pages, digital products, and gamified experiences for mission-driven organisations. Human-centred design, accessibility, mobile-first methodology.
- Contribution: Mapped the user journey and emotional arc from landing to action. Designed the full page structure (12 sections). Defined the visual design system (colour, typography, spacing, imagery). Specified all interactive elements, animations, and responsive breakpoints. Created section-by-section wireframe descriptions for the developer.
- Page influence: Every visual decision, layout choice, colour, font, spacing value, animation timing, and responsive behaviour on this page comes from this design specification.

**Agent 04 -- Front-End Developer**
- Expertise: Senior front-end specialist in performant, accessible static websites. Clean HTML, CSS, and vanilla JavaScript. GitHub Pages deployment.
- Contribution: Built the complete landing page from the design specification. Implemented all interactive elements (recommender quiz, animated counters, accordion, carousel, map interactions). Ensured WCAG 2.1 AA accessibility, sub-2-second load times, and responsive behaviour across all breakpoints.
- Page influence: Every line of code, every animation, every interaction, and the fact that this page loads fast and works on every device is this agent's work.

**Agent 05 -- Brand Communicator & Copywriter**
- Expertise: Senior brand strategist and copywriter with deep understanding of Dublin culture, community communication, and behavioural copywriting.
- Contribution: Wrote all page copy in an authentic Dublin voice -- warm, direct, slightly funny, never corporate. Crafted headlines, CTAs, micro-story adaptations, objection answers, and microcopy. Ensured every word earns its place and speaks to the visitor as a person, not a target.
- Page influence: Every word on this page -- from the hero headline to the button labels to the seasonal calendar descriptions to the closing line -- comes from this agent's pen.

### Styling Notes
- Agent cards use a muted version of the page's colour palette (lighter backgrounds, softer text).
- A small icon or number badge identifies each agent.
- The expandable panel has a smooth slide-down animation (300ms ease-out).
- The trigger button uses the secondary/accent colour and is clearly labelled as an academic element.
- Collapsed by default -- this does not interrupt the Rooftop Republic experience.

---

# PART 2: VISUAL DESIGN SYSTEM

---

## 4. Colour Palette

The palette draws from three sources: the greens of growing things, the warm reds of Dublin brick, and the grounding greys of Dublin sky. It must feel organic without being twee, warm without being saccharine, and modern without being corporate. This is a community garden notice board, not a wellness app.

### Primary Palette

| Role | Colour | Hex | Usage | Rationale |
|---|---|---|---|---|
| **Primary Green** | Leaf Green | `#3A7D44` | Primary buttons, key headings, active states, progress bars | The colour of healthy leaves in Dublin's mild climate. Not neon, not forest-dark. A living, approachable green. WCAG AA compliant on white at this saturation. |
| **Primary Dark** | Deep Soil | `#2C3E2D` | Body text, dark backgrounds, footer | A near-black with a green undertone. Warmer and more natural than pure black. Reads as "earth" not "corporate." |
| **Primary Light** | Morning Mist | `#F4F7F2` | Page background, card backgrounds, light sections | An off-white with a barely perceptible green warmth. Cleaner than beige, warmer than pure white. The page breathes. |

### Secondary Palette

| Role | Colour | Hex | Usage | Rationale |
|---|---|---|---|---|
| **Warm Accent** | Dublin Brick | `#C45D3E` | Accent highlights, hover states, notification dots, the challenge card border | The red-brown of Georgian Dublin brick. Warm, grounding, distinctly Dublin. Paired with the green, it says "nature meets city." |
| **Warm Light** | Terracotta Glow | `#F0D5C4` | Warm section backgrounds (Herb Pot Challenge card), accent card fills | A soft, warm background for moments that need to feel inviting and distinct. Gentle enough to not fight with green. |
| **Cool Neutral** | Dublin Sky | `#8E9B97` | Secondary text, borders, disabled states, subtle dividers | The colour of overcast Dublin. Honest, grounding, and unobtrusive. Acknowledges the real sky rather than pretending it's always sunny. |

### Supporting Colours

| Role | Colour | Hex | Usage |
|---|---|---|---|
| **Success / Harvest** | Ripe Tomato | `#E07A4B` | Success states, harvest season indicators, celebratory moments |
| **Info / Season** | Spring Blue | `#5B8FA8` | Seasonal info, linked text, informational elements |
| **White** | Clean White | `#FFFFFF` | Card surfaces, overlays, maximum contrast areas |
| **Shadow** | Soft Shadow | `rgba(44, 62, 45, 0.08)` | Card shadows, depth layers |

### Colour Usage Rules
1. **Maximum 3 colours per section.** Background, text, and one accent. Restraint prevents visual chaos.
2. **Green is the action colour.** If it's green and clickable, it does something. Do not use Primary Green for decorative elements.
3. **Dublin Brick is the warmth colour.** Used sparingly for moments of human warmth: stories, the challenge card, accents near photographs.
4. **The background alternates** between Morning Mist (`#F4F7F2`) and Clean White (`#FFFFFF`) to create subtle section separation without hard dividers.
5. **All text/background combinations must meet WCAG 2.1 AA.** Deep Soil on Morning Mist: contrast ratio 12.8:1 (AAA). Deep Soil on White: 14.5:1 (AAA). Primary Green on White: 4.7:1 (AA). White on Primary Green: 4.7:1 (AA).

---

## 5. Typography

Typeface choices prioritise readability, warmth, and availability on Google Fonts (free, hosted, no FOIA concerns for GitHub Pages).

### Font Stack

| Role | Font | Fallback | Weight(s) | Rationale |
|---|---|---|---|---|
| **Headings** | **DM Serif Display** | Georgia, serif | 400 (Regular) | A warm, modern serif with generous letterforms. It has the groundedness of a traditional serif (authority, trust) with enough contemporary flair to not feel stuffy. It says "community" and "Dublin" without being cliched. |
| **Body** | **Inter** | -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif | 400 (Regular), 500 (Medium), 600 (Semi-Bold) | The workhorse. Exceptional legibility at all sizes, excellent on screens, generous x-height, clear at small sizes on mobile. Open-source and extremely well-optimised for web. |
| **Accent / Microcopy** | **Inter** | Same as body | 400 Italic, 500 | Using the same body font for accent text keeps the type system clean. Italic and medium weight provide enough differentiation for labels, captions, and microcopy. |

### Type Scale

Using a fluid type scale with `clamp()` for seamless responsive scaling. Base size: 16px (1rem) on mobile, scaling to 18px on desktop.

| Element | Mobile Size | Desktop Size | CSS `clamp()` | Weight | Line Height | Letter Spacing |
|---|---|---|---|---|---|---|
| **Hero Headline** | 36px | 64px | `clamp(2.25rem, 5vw + 1rem, 4rem)` | 400 (DM Serif Display) | 1.1 | -0.02em |
| **Section Headline** | 28px | 44px | `clamp(1.75rem, 3vw + 0.75rem, 2.75rem)` | 400 (DM Serif Display) | 1.2 | -0.01em |
| **Subsection Heading** | 22px | 30px | `clamp(1.375rem, 2vw + 0.5rem, 1.875rem)` | 600 (Inter) | 1.3 | 0 |
| **Body Large** | 18px | 20px | `clamp(1.125rem, 1vw + 0.75rem, 1.25rem)` | 400 (Inter) | 1.7 | 0 |
| **Body Regular** | 16px | 18px | `clamp(1rem, 0.5vw + 0.75rem, 1.125rem)` | 400 (Inter) | 1.7 | 0 |
| **Body Small / Microcopy** | 14px | 15px | `clamp(0.875rem, 0.25vw + 0.75rem, 0.9375rem)` | 400 (Inter) | 1.6 | 0.01em |
| **CTA Button Text** | 16px | 18px | `clamp(1rem, 0.5vw + 0.75rem, 1.125rem)` | 600 (Inter) | 1 | 0.02em |
| **Counter / Large Stat** | 40px | 72px | `clamp(2.5rem, 6vw + 1rem, 4.5rem)` | 400 (DM Serif Display) | 1.0 | -0.02em |
| **Card Title** | 20px | 24px | `clamp(1.25rem, 1.5vw + 0.5rem, 1.5rem)` | 600 (Inter) | 1.3 | 0 |
| **Label / Tag** | 12px | 13px | `clamp(0.75rem, 0.2vw + 0.6rem, 0.8125rem)` | 600 (Inter) | 1.4 | 0.06em |

### Typography Rules
1. **Maximum 2 font sizes per section** (heading + body). Exceptions: the hero (headline + counter + scroll indicator) and the challenge card (headline + steps + stats + CTA).
2. **Line length maximum: 70 characters.** Research (Baymard Institute) consistently shows 50-75 characters per line is optimal. On wide screens, text blocks should be constrained within a max-width container, not stretch edge-to-edge.
3. **Generous line height on body text (1.7).** This gives the page air. Cramped text feels like a government form. Generous text feels like a letter from a friend.
4. **Heading line height is tight (1.1-1.3).** Headings are display elements and should feel cohesive, not airy.
5. **All-caps only for small labels and tags** (e.g., "SPRING 2026," "STEP 1"). Never for headings, body text, or buttons. All-caps at scale shouts; we want to converse.

---

## 6. Imagery Direction

### Hero Image
**Content:** A candid, medium-wide shot of a Dublin rooftop garden in use. 3-4 people of varying ages and backgrounds, tending to container plants. The Dublin skyline (rooftops, chimneys, period architecture) is visible in the background. The sky is overcast -- this is Dublin, not Barcelona. The plants are a realistic mix: some healthy, some scraggly. Containers are a mix of proper pots and improvised vessels (old crates, buckets). One person is laughing or in conversation. The overall mood is "relaxed Saturday morning," not "posed marketing shoot."

**Style:** Natural light (diffused, overcast is fine and honest). Slightly warm-toned colour grading to counterbalance the grey sky. Shot from slightly above eye level to show the rooftop context. Avoid shallow depth of field that isolates subjects -- we want the environment and the people equally present.

**If original photography is not available:** Use an illustration in a warm, semi-realistic style (see Iconography section) that captures the same scene. The illustration must include Dublin-specific visual cues: redbrick terraces, Georgian rooflines, the Poolbeg chimneys or Spire in the far distance.

### Section Photos / Illustrations
- **Identity Shift (Section 2):** Circular portrait photos, warmly lit, slightly desaturated to feel candid rather than corporate. Each portrait should show a real person (not a model) in a natural setting, ideally on or near a rooftop/garden. Diverse in age, ethnicity, and apparent lifestyle.
- **Micro-Stories (Section 3):** Each card should have an image that matches the story. Niamh: a young woman on a balcony with herbs. Declan & Roisin: a parent and child planting something in a pot. Tomasz: a man tending tomatoes on a rooftop. Margaret: an older woman at a raised bed, possibly holding a cup of tea. These can be photographs or warm illustrations.
- **Herb Pot Challenge (Section 5):** A close-up, instructional-style photo or illustration showing the three steps: a pot being filled with compost, a herb plant being transferred, the pot sitting on a windowsill. Warm, simple, and approachable. Think "recipe card photography" -- overhead shot, clean background, clear steps.
- **Map Section (Section 8):** No photograph. A custom illustrated map of Dublin (see Iconography section).
- **Seasonal Strip (Section 9):** Small botanical illustrations or icons for each month's featured crops. Flat, simple, charming -- not photorealistic.

### Photography Rules
1. **No stock photography.** If real photos are not available, use illustrations. A warm illustration feels more honest than a cold stock photo.
2. **Dublin weather is not a problem -- it's a feature.** Grey sky = authentic. Overcast light is soft, flattering, and honest. Do not colour-correct to artificial sunshine.
3. **Show imperfection.** The wonky tomato stake, the cracked pot, the yellowing leaf. Imperfection signals "achievable." Perfection signals "not for me."
4. **Show diversity without tokenism.** People of different ages, ethnicities, and body types, shown naturally, not as a checkbox exercise. The Urban Farming Expert's personas demand this.
5. **Compress aggressively.** Every image should be served in WebP with a JPEG fallback, at maximum 200KB for full-width images, 50KB for thumbnails. Performance is non-negotiable.

---

## 7. Iconography & Visual Elements

### Icon Style
**Line icons**, consistent 2px stroke weight, rounded caps and joins. Colour: Primary Green (`#3A7D44`) or Deep Soil (`#2C3E2D`) depending on background. The style should feel friendly and hand-drawn-adjacent without being literally hand-drawn -- clean enough to read at small sizes, warm enough to not feel corporate.

**Recommended icon set:** Phosphor Icons (open-source, MIT licence, excellent line style, available as SVG). Alternative: Lucide Icons.

### Icon Applications
- **Herb Pot Challenge steps:** A pot icon, a plant/seedling icon, a sun/water icon.
- **Growing Journey steps:** A seedling, a camera, a group of people, a grid/patch, a calendar, a megaphone/share.
- **Seasonal strip months:** Small crop illustrations -- a basil leaf, a tomato, a head of lettuce, a garlic bulb, a snowflake (winter). These can be slightly more illustrative than the UI icons.
- **Accordion arrows:** Chevron down/up for the objection section.
- **Recommender tool options:** Windowsill, balcony, rooftop as simple scene icons.
- **Stats:** A rooftop icon, a person icon, a plant icon.

### Decorative Elements
- **Subtle leaf/vine motif:** Used sparingly as a section divider or background texture. A single curving vine with 3-5 leaves, rendered in Dublin Sky grey (`#8E9B97`) at 10-15% opacity. This should be barely noticeable -- atmospheric, not illustrative.
- **The Dublin skyline silhouette:** A simplified line illustration of the Dublin skyline (rooftops, chimneys, the Spire, Liberty Hall, the Poolbeg chimneys) used as a footer background element or as the base of the map illustration. Drawn in the same 2px line style as the icons.
- **No gradients, no glossy effects, no drop shadows heavier than the defined shadow colour.** The visual language is flat, honest, and clean.

---

## 8. Spacing & Grid System

### Grid
A 12-column grid with fluid gutters.

| Breakpoint | Columns | Gutter | Outer Margin | Max Content Width |
|---|---|---|---|---|
| Mobile (< 640px) | 4 | 16px | 20px | 100% |
| Tablet (640-1024px) | 8 | 24px | 32px | 100% |
| Desktop (> 1024px) | 12 | 32px | auto (centred) | 1200px |

### Spacing Scale
An 8px base unit provides the rhythmic foundation. All spacing values are multiples of 8.

| Token | Value | Usage |
|---|---|---|
| `--space-xs` | 4px | Tight internal spacing: icon-to-label, tag padding |
| `--space-sm` | 8px | Compact spacing: between related items in a list |
| `--space-md` | 16px | Standard spacing: between content blocks within a section |
| `--space-lg` | 24px | Comfortable spacing: between distinct elements within a section |
| `--space-xl` | 32px | Section internal padding (top/bottom on mobile) |
| `--space-2xl` | 48px | Section internal padding (top/bottom on tablet) |
| `--space-3xl` | 64px | Section internal padding (top/bottom on desktop) |
| `--space-4xl` | 96px | Between major sections (mobile) |
| `--space-5xl` | 128px | Between major sections (desktop) |

### Section Spacing Rules
1. **Section padding:** Each section has vertical padding of `--space-xl` (32px) on mobile, `--space-2xl` (48px) on tablet, and `--space-3xl` (64px) on desktop. This is the inner breathing room.
2. **Between sections:** Adjacent sections with the same background colour get `--space-4xl` (96px mobile) / `--space-5xl` (128px desktop) separation. Adjacent sections with alternating backgrounds get zero margin (the background change creates visual separation).
3. **Max content width:** Body text and content blocks are constrained to 720px (roughly 70 characters at body size). Full-width elements (hero, map, progress bar) extend to the 1200px container or beyond.
4. **Card internal padding:** `--space-lg` (24px) on all sides. Cards in a grid have `--space-md` (16px) gap on mobile, `--space-lg` (24px) on desktop.
5. **Button padding:** `--space-md` (16px) vertical, `--space-lg` (24px) horizontal. Minimum tap target: 44x44px (WCAG 2.5.8).

### The Whitespace Philosophy
This page must breathe. The Urban Farming Expert said it must feel like "fresh air, not a sales pitch." The spacing system enforces this. When in doubt, add more space, not more content. A spacious page communicates confidence and calm. A crowded page communicates desperation.

---

# PART 3: INTERACTION DESIGN

---

## 9. Interactive Elements Specification

### Element 1: The "What Can I Grow?" Recommender Quiz

**Layout:**
- Desktop: Centred content block, max-width 640px. Each step is a full-width question with options displayed as a horizontal row of 3-4 large, tappable cards.
- Mobile: Full-width. Options stack vertically or display as a 2x2 grid when there are 4 options.
- Output card: A visually distinct result card (Terracotta Glow background, `#F0D5C4`) showing the plant recommendations in a clean list.

**Behaviour:**
- Step transitions: 300ms fade/slide. When the user selects an option, the current step fades out and the next slides in from the right. No page reload.
- Option selection: On click/tap, the selected option gets a green border (`#3A7D44`) and a subtle scale animation (1.0 to 1.03 over 150ms, ease-out). Unselected options dim slightly (opacity 0.6).
- After the third selection, the output card slides in from below with a 400ms ease-out animation. Plants appear in a staggered fade-in (each plant 100ms after the previous).
- "Try again" link resets to Step 1 with a fade transition.
- The quiz remembers no state -- it is stateless and ephemeral. This is intentional: low commitment.

**States:**
- Default: Options displayed, none selected
- Selected: Green border, slight scale-up, other options dimmed
- Loading output: Brief (200ms) skeleton shimmer on the result card, then content fades in
- Result: Plant cards visible with seasonal note and tips
- Reset: Fade back to Step 1

**Mobile vs Desktop:**
- Mobile: Each step takes up roughly 70% of viewport height. Options are large touch targets (minimum 64px tall). Vertical stacking if 3+ options.
- Desktop: More compact. Steps can transition horizontally within a contained area. Options displayed in a single row.

**Accessibility:**
- Each option is a button with a clear label and `aria-pressed` state.
- Step transitions respect `prefers-reduced-motion` (instant swap instead of animation).
- The output card is announced to screen readers via `aria-live="polite"` region.
- Full keyboard navigability: Tab to select options, Enter/Space to confirm. Focus ring visible.
- Colour is never the sole indicator of selection state -- border weight change and scale change provide additional visual cues.

---

### Element 2: The Rooftop Counter

**Layout:**
- In the hero section, positioned below the headline. Three stat clusters in a horizontal row: "40" + "Rooftops", "250+" + "Growers", "1" + "City, Growing."
- Each number is in DM Serif Display at the Counter/Large Stat size. The label beneath is in Inter at Body Small size.
- Desktop: Horizontal row with generous spacing. Mobile: Horizontal row, slightly smaller numbers.

**Behaviour:**
- On first scroll into viewport (detected via Intersection Observer), each number animates from 0 to its target value over 1.5 seconds with an easeOutCubic curve.
- Numbers count up in whole integers (no decimals). The animation is staggered: the first number starts immediately, the second at 200ms delay, the third at 400ms delay.
- After animation completes, the numbers remain static. The animation fires only once per page load.

**Mobile vs Desktop:**
- Mobile: Numbers slightly smaller. Row can wrap to 2+1 or remain in a single row with tighter spacing.
- Desktop: Full-size numbers in a single centred row.

**Accessibility:**
- The final number values are present in the HTML at load time (not injected by JS). The animation is a visual enhancement only. Screen readers read the static values.
- `prefers-reduced-motion`: No animation. Numbers display at their final values immediately.
- Stat labels use `aria-label` for clarity (e.g., `aria-label="40 active rooftop gardens"`).

---

### Element 3: The Herb Pot Challenge Card

**Layout:**
- A visually elevated card section that breaks the page rhythm. Background: Terracotta Glow (`#F0D5C4`). A thin left border in Dublin Brick (`#C45D3E`, 4px).
- Desktop: Centred, max-width 800px. Content arranged in a clean vertical stack: headline, subhead, 3 steps with icons, stat row (3 stats in a horizontal row), seasonal nudge, CTA button.
- Mobile: Full-width with `--space-lg` padding. Same vertical stack. Stat row wraps to 3-across.

**Behaviour:**
- On scroll into view: The card fades in and slides up 20px over 500ms (ease-out). This is the only section with an entrance animation -- it marks the conversion moment.
- The "Save the Challenge" button: On click, it triggers a download of a simple, pre-formatted image/PDF of the challenge instructions (or copies a shareable link to clipboard with a "Copied!" tooltip). The button temporarily changes text: "Save the Challenge" --> "Saved!" (with a small checkmark icon) for 2 seconds, then reverts.
- "Share with a friend" link: Opens the native share dialog (Web Share API) on mobile, or copies the page URL with a `#herb-pot-challenge` anchor on desktop.

**Mobile vs Desktop:**
- Mobile: Full-width card. CTA button is full-width. Stats stack as 3 in a row.
- Desktop: Constrained card with generous padding. CTA button is auto-width with padding.

**Accessibility:**
- The challenge card has a landmark role or clear heading structure so screen reader users can navigate to it directly.
- The CTA button has a clear `aria-label`: "Save the Herb Pot Challenge instructions."
- The stat figures use `aria-label` to provide context (e.g., `aria-label="Total cost: under 10 euro"`).
- All interactive elements have visible focus rings.

---

### Element 4: The Seasonal Timeline

**Layout:**
- A horizontal scrollable strip. Each month is a card (approximately 150px wide on desktop, 120px on mobile).
- The current month's card is visually larger (1.2x scale), has the Primary Green background with white text, and is centred in the viewport on load.
- Other months have the Morning Mist background with Deep Soil text.
- Each month card shows: month name, 1-2 small crop icons, and 2-3 lines of text (what to sow/harvest).

**Behaviour:**
- Horizontal scroll with CSS `overflow-x: auto` and `scroll-snap-type: x mandatory`. Each card snaps to centre on mobile.
- On desktop: The strip may be fully visible if the viewport is wide enough (12 months x 150px = 1800px, so it scrolls on all but the widest screens). Arrow buttons at left/right edges for desktop scrolling.
- The current month auto-scrolls into centre position on page load (JavaScript `scrollIntoView` with `behavior: smooth`).
- Clicking/tapping a month card expands it slightly and shows a tooltip or popover with more detail (2-3 additional lines about that month's activities).

**Mobile vs Desktop:**
- Mobile: Horizontal swipe. Each card is a snap point. Current month centred on load. Touch-scrollable. Scroll indicators (fade on edges) hint that more content exists left/right.
- Desktop: Horizontal scroll with left/right arrow buttons. Current month centred. Hover on a month shows expanded detail.

**Accessibility:**
- The timeline has `role="tablist"` or a clear semantic structure with months as navigable items.
- Arrow keys navigate between months when the timeline is focused.
- Month content is accessible without hover/click via screen readers (all text is in the DOM, expanded details use `aria-expanded`).
- `prefers-reduced-motion`: No smooth scrolling. Instant jumps.

---

### Element 5: The Dublin Rooftop Map

**Layout:**
- A custom SVG illustration of Dublin, divided into clickable neighbourhood regions. Approximately 600x400px on desktop, full-width and proportionally scaled on mobile.
- Neighbourhoods with active rooftops are filled with a light green tint. Neighbourhoods without sites are filled with a neutral grey.
- On interaction, an info card appears anchored to the selected neighbourhood.

**Behaviour:**
- Hover (desktop): The neighbourhood region highlights (fills with a deeper green, slight scale-up of 1.02). Cursor changes to pointer.
- Click/Tap: An info card slides in (300ms ease-out) showing: neighbourhood name, number of growers, what's growing, next drop-in date. A "Get directions" or "Learn more" link.
- Tapping the same region again, or tapping elsewhere, dismisses the card.
- Mobile: Tap only (no hover). The info card appears as a bottom sheet (slides up from the bottom of the map area).

**Mobile vs Desktop:**
- Mobile: Map is full-width, touch-interactive. Info cards appear as bottom sheets within the map container. Pinch-to-zoom is not necessary (the map is not detailed enough to require it).
- Desktop: Map is centred, larger, with hover and click interactions. Info cards appear as popover cards near the selected region.

**Accessibility:**
- Each neighbourhood region is a focusable button with an `aria-label` (e.g., "Stoneybatter: 3 rooftop gardens, tap for details").
- Tab navigation moves between neighbourhood buttons. Enter/Space opens the info card.
- The info card is focus-trapped when open and dismissible with Escape.
- Screen reader alternative: A styled list of neighbourhoods with the same information, visually hidden but available to assistive technology. Or, the map is supplementary and the list is the primary content (progressive enhancement).

---

### Element 6: The "Dublin Can Grow" Collective Goal Tracker

**Layout:**
- A horizontal progress bar, full-width within the content container (max 800px). Above it: the current number (large, animated) and the goal. Below it: the supporting text.
- The bar itself is 16px tall with rounded ends. Fill colour: Primary Green. Track colour: a light green tint (`#D5E8D4`).

**Behaviour:**
- On scroll into viewport: The bar fills from 0% to the current progress percentage over 1.5 seconds (easeOutCubic). Simultaneously, the number above counts up from 0 to the current value.
- The animation fires once per page load.
- A subtle pulse animation on the leading edge of the progress bar after the fill animation completes (3 gentle pulses, then stops). This communicates "still growing."

**Mobile vs Desktop:**
- Identical behaviour. The bar is responsive (full content width on all screens). The number size scales with the fluid type system.

**Accessibility:**
- The progress bar uses `role="progressbar"` with `aria-valuenow`, `aria-valuemin="0"`, and `aria-valuemax` set to the goal value.
- `aria-label="Dublin community growing goal: [current] out of [goal] kilograms of food grown"`.
- `prefers-reduced-motion`: Bar appears at final fill state immediately. Number displays final value.

---

## 10. Micro-interactions & Animations

### Global Animation Principles
- **Timing:** Most transitions are 300ms. Entrance animations are 400-500ms. Counter animations are 1500ms. Nothing exceeds 2 seconds.
- **Easing:** `ease-out` (CSS `cubic-bezier(0.0, 0.0, 0.2, 1)`) for entrances. `ease-in-out` for state changes. Linear for progress indicators.
- **Trigger:** Intersection Observer at 20% visibility threshold for scroll-triggered animations. Each animation fires once (not on every scroll in/out).
- **Respect for motion preferences:** All animations are wrapped in `@media (prefers-reduced-motion: no-preference)`. Users who prefer reduced motion see instant state changes.

### Scroll-Triggered Reveals
- **Sections 2-11:** Each section's primary content block (headline + first content element) fades in and translates up 20px on scroll into viewport. Duration: 500ms. Stagger: If multiple elements (e.g., story cards), each subsequent element is delayed by 100ms.
- **The hero (Section 1) does not animate in.** It is visible on load. Animating the first thing a visitor sees creates a perception of slowness.

### Hover Effects
- **Buttons (primary CTA):** Background colour deepens 10% on hover (darken the Primary Green). Subtle lift: `translateY(-2px)` with `box-shadow` increase. Transition: 200ms ease-out.
- **Story cards:** Slight lift (`translateY(-4px)`) and shadow increase on hover. Transition: 200ms.
- **Map neighbourhoods:** Fill colour shifts to a deeper green. Scale: 1.02. Transition: 200ms.
- **Accordion items:** Chevron rotates 180 degrees on open. Background subtly lightens. Transition: 300ms.
- **Links:** Colour shifts from Deep Soil to Primary Green. Underline animates in from left. Transition: 200ms.

### Counter Animations
- **Hero counter:** Count from 0 to target over 1500ms with easeOutCubic. Staggered start (0, 200ms, 400ms for each stat).
- **Collective goal tracker:** Same count-up behaviour. Progress bar fills simultaneously.
- **Implementation:** JavaScript `requestAnimationFrame` loop with easing function. Values update the `textContent` of a `<span>`. No CSS animation (CSS cannot animate text content).

### Accordion (Objection Section)
- **Open:** Content slides down from 0 height to natural height over 300ms. Chevron rotates. Smooth height animation using `max-height` technique or the `<details>` element with CSS animation.
- **Close:** Reverse of open. 300ms.
- **Only one item open at a time** (optional -- reduces visual clutter and aligns with progressive disclosure, but not mandatory).

### Carousel (Story Cards on Mobile)
- **Swipe:** Momentum-based horizontal scroll with CSS `scroll-snap-type: x mandatory`. No JavaScript required for basic functionality.
- **Pagination dots:** Below the carousel. Active dot is Primary Green, inactive dots are Dublin Sky grey. Dot transitions: 200ms opacity change.
- **Auto-advance:** None. The user controls the pace. Auto-advancing carousels are one of the most hated UX patterns on the web (Nielsen Norman Group, 2023).

---

## 11. Responsive Breakpoints

### Mobile (< 640px)
- **Grid:** 4 columns, 16px gutters, 20px outer margin.
- **Hero:** Full-viewport height. Headline at mobile size (36px). Counter numbers smaller but still prominent.
- **Story cards:** Horizontal scroll carousel with snap points. One card visible at a time.
- **Recommender quiz:** Full-width options. Vertical stacking. Large tap targets (minimum 48px height).
- **Map:** Full-width SVG, simplified (fewer labels to avoid clutter). Info cards as bottom sheets.
- **Seasonal strip:** Horizontal swipe. Current month centred. One month visible at a time.
- **Navigation:** No fixed nav. The page is a single scroll. A "Back to top" button appears after 50% scroll depth (bottom-right, small, circular, Primary Green).
- **CTA buttons:** Full-width within their containers.
- **Typography:** All clamp() values at their minimum.
- **Images:** Served at 640px width maximum. WebP with JPEG fallback.

### Tablet (640-1024px)
- **Grid:** 8 columns, 24px gutters, 32px outer margin.
- **Hero:** Full-viewport height. Headline scales up.
- **Story cards:** 2-column grid. Two cards visible simultaneously.
- **Recommender quiz:** Options in a row if 3, 2x2 grid if 4.
- **Map:** Centred, roughly 80% viewport width.
- **Seasonal strip:** 3-4 months visible at once in the horizontal strip.
- **CTA buttons:** Auto-width with generous padding.
- **Images:** Served at 1024px width maximum.

### Desktop (> 1024px)
- **Grid:** 12 columns, 32px gutters, auto outer margin. Max content width: 1200px, centred.
- **Hero:** Full-viewport height. Headline at maximum size (64px).
- **Story cards:** 4-column row or 2x2 grid.
- **Recommender quiz:** Centred block, max-width 640px. Compact and contained.
- **Map:** Full content width (up to 800px), centred. Hover interactions enabled.
- **Seasonal strip:** 6-8 months visible. Left/right arrows for scrolling.
- **Section alternation:** Image-left/text-right and text-left/image-right patterns for rhythm.
- **Images:** Served at 1200px width maximum for full-width elements, 600px for content images.

### Breakpoint Implementation Notes for Developer
- Use `min-width` media queries (mobile-first).
- Key breakpoints: `640px`, `1024px`. Optional refinement at `768px` (iPad portrait) and `1280px` (wide desktop).
- CSS custom properties for spacing tokens change at each breakpoint.
- Test on: iPhone SE (375px), iPhone 14 (390px), iPad (768px), iPad landscape (1024px), laptop (1366px), desktop (1920px).

---

# PART 4: SECTION-BY-SECTION WIREFRAME DESCRIPTIONS

---

## Section 1: Hero -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|  [Full-viewport background image: Dublin rooftop garden]      |
|                                                               |
|              Dublin Has Thousands of                          |
|              Empty Rooftops. We're Turning                    |
|              Them Into Gardens.                               |
|                                                               |
|         40            250+           1                        |
|       Rooftops       Growers     City, Growing               |
|                                                               |
|                       [v]  (scroll indicator)                 |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Full-viewport (100vh) container with a background image. The image is `object-fit: cover`, centred.
- A semi-transparent dark overlay (Deep Soil at 40-50% opacity) over the image to ensure text legibility.
- All text is centred horizontally and vertically within the viewport.
- The headline is the dominant element, stacked in 2-3 lines.
- Below the headline, the three-stat counter row is centred with generous spacing between each stat.
- At the very bottom (positioned absolutely, 32px from bottom edge), a small animated scroll-down chevron.

**Content blocks:**
- **Headline:** "Dublin Has Thousands of Empty Rooftops. We're Turning Them Into Gardens." (DM Serif Display, Hero Headline size, white `#FFFFFF`)
- **Counter row:** Three stat clusters. Each: large number (DM Serif Display, Counter size, white) + label below (Inter, Body Small, white at 80% opacity).
- **Scroll indicator:** A single chevron-down icon, 24px, white, with a subtle up-down bounce animation (1s infinite, 8px translate).

**Mobile stacking:**
- Headline stacks to more lines at the smaller font size. Still centred.
- Counter row remains horizontal but with tighter spacing. If extremely narrow (< 360px), the counter wraps to a 2+1 layout.

**Developer notes:**
- The hero image must be optimised: compressed WebP, max 300KB at full resolution. Provide a low-res placeholder (blurred, < 10KB) for progressive loading.
- The overlay can be a CSS `linear-gradient(rgba(44,62,45,0.5), rgba(44,62,45,0.6))` for better control than a flat colour.
- The counter numbers are in `<span>` elements with `data-target="40"` (etc.) attributes for the JavaScript animation.
- Ensure the hero is full viewport on iOS Safari (use `100dvh` for dynamic viewport height to account for the URL bar).

---

## Section 2: The Identity Shift -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|   "You don't need to know anything about gardening.          |
|    You don't need a big rooftop. You don't even need         |
|    a rooftop. You need a pot, some soil, and ten             |
|    minutes this Saturday."                                    |
|                                                               |
|      (O) (O) (O) (O) (O)   <-- portrait circles             |
|                                                               |
|   Our growers include software engineers, retired             |
|   teachers, nurses, builders, students, and parents.          |
|   The common thread isn't a green thumb -- it's curiosity.    |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Centred text block, max-width 720px.
- The main statement is the largest text element (Section Headline size, DM Serif Display). Centred.
- Below the statement, a row of 5 circular portrait images (64px diameter on mobile, 80px on desktop), evenly spaced and centred.
- Below the portraits, the supporting line (Body Regular, Inter, Deep Soil at 80% opacity). Centred.
- Background: Morning Mist (`#F4F7F2`).

**Mobile stacking:**
- Same layout, just scaled. Portraits may shrink to 56px on very small screens. The row of 5 always fits on one line at 56px + gaps.

**Developer notes:**
- Portraits are `<img>` elements inside `<figure>` or `<div>` elements with `border-radius: 50%`, `object-fit: cover`.
- Each portrait has meaningful `alt` text: "Young woman smiling on a Dublin balcony," etc.
- The main statement should be a `<p>` with a distinct class, not a heading (it is a statement, not a section title). But consider wrapping the section in a `<section>` with an `aria-label` for screen reader navigation.

---

## Section 3: Micro-Stories -- Wireframe

**Desktop:**
```
+---------------------------------------------------------------+
|                                                               |
|            People Like You Already Do This                    |
|                                                               |
|  +-------------+  +-------------+  +-------------+  +------+ |
|  | [photo]     |  | [photo]     |  | [photo]     |  |[photo]| |
|  | "Niamh      |  | "Declan's   |  | "Tomasz     |  |"Marga | |
|  |  bought a   |  |  7yr old    |  |  moved from |  |ret had| |
|  |  EUR 1.99   |  |  would not  |  |  Lublin..." |  |been..."| |
|  |  basil..."  |  |  eat a..."  |  |             |  |       | |
|  | [Read more] |  | [Read more] |  | [Read more] |  |[Read] | |
|  +-------------+  +-------------+  +-------------+  +------+ |
|                                                               |
+---------------------------------------------------------------+
```

**Mobile:**
```
+----------------------------+
|  People Like You Already   |
|  Do This                   |
|                            |
|  +----------------------+  |
|  | [photo]              |  |
|  | "Niamh bought a      |  |
|  |  EUR 1.99 basil      |  |
|  |  plant from Tesco.." |  |
|  | [Read more]          |  |
|  +----------------------+  |
|       . o . .   <-- dots   |
|                            |
+----------------------------+
```

**Layout:**
- Section heading: "People Like You Already Do This" (Section Headline, centred).
- Desktop: 4 cards in a single row (3 columns each on a 12-col grid) or 2x2 grid.
- Mobile: Horizontal scroll carousel with scroll-snap. One card visible at a time with peek of next card (showing ~20px of the next card's edge to signal scrollability).
- Each card: White background, soft shadow, rounded corners (12px). Internal layout: photo (top, 16:9 ratio), hook text (2-3 lines), "Read more" link at bottom.
- Expanded state (after "Read more" click): Card expands inline to reveal the full story text. On mobile, this could expand below the card or open as a modal/overlay.

**Content blocks per card:**
- **Photo:** Aspect ratio 16:9, `object-fit: cover`. Fills the top of the card.
- **Hook text:** 2-3 lines of the story opening. Body Regular weight. Deep Soil colour.
- **"Read more" link:** Primary Green, Inter, Body Small, underline.
- **Expanded story:** Full micro-story text from the Urban Farming Expert's report. Body Regular.

**Developer notes:**
- Carousel on mobile: Use CSS `overflow-x: auto`, `scroll-snap-type: x mandatory`, `scroll-snap-align: center` on each card. No JavaScript carousel library needed.
- Pagination dots: A `<div>` with small circles. Use Intersection Observer on each card to update the active dot.
- "Read more" expansion: Can be implemented with a `<details>` element for native HTML expansion, or JavaScript `classList.toggle` with a CSS `max-height` transition.
- Card minimum width on mobile: `calc(100vw - 56px)` (viewport minus padding and peek).

---

## Section 4: "Yeah, But..." -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|                     Yeah, But...                              |
|                                                               |
|  +----------------------------------------------------------+ |
|  |  v  "I kill every plant I've ever owned."                 | |
|  |     Outdoor plants have rain, natural light, and soil     | |
|  |     biology on their side. You've probably been           | |
|  |     overwatering your houseplants in a dark apartment...  | |
|  +----------------------------------------------------------+ |
|  |  >  "Dublin weather is too miserable for growing."        | |
|  +----------------------------------------------------------+ |
|  |  >  "I don't have time."                                 | |
|  +----------------------------------------------------------+ |
|  |  >  "I'm renting."                                       | |
|  +----------------------------------------------------------+ |
|  |  >  "It'll cost a fortune."                              | |
|  +----------------------------------------------------------+ |
|  |  >  "What if I lose interest?"                           | |
|  +----------------------------------------------------------+ |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Section heading: "Yeah, But..." (Section Headline, centred). This heading has personality -- it's acknowledging what the visitor is already thinking.
- Accordion list: Centred, max-width 720px. Each item is a row with a chevron (left or right), the question text (bold, Subsection Heading size), and an expandable answer area.
- Background: White (`#FFFFFF`).
- Each accordion item has a subtle bottom border (1px, Dublin Sky grey at 30% opacity) for separation.
- The first item is expanded by default.

**Content blocks per accordion item:**
- **Question:** Inter Semi-Bold (600), Subsection Heading size. Deep Soil.
- **Answer:** Inter Regular (400), Body Regular size. Deep Soil at 90% opacity. 2-4 sentences. Warm, honest, slightly funny.
- **Chevron:** Rotates 180 degrees when open. Transition: 300ms.

**Mobile stacking:**
- Identical layout. The accordion naturally works on all screen widths.

**Developer notes:**
- Use `<details>` and `<summary>` elements for semantic, accessible accordion behaviour. Style with CSS. Add JS only for the "one item open at a time" behaviour (optional) and the smooth height animation.
- The first `<details>` element has the `open` attribute set in the HTML.
- Ensure the `<summary>` element is keyboard-focusable and responds to Enter/Space.

---

## Section 5: Herb Pot Challenge Card -- Wireframe

```
+---------------------------------------------------------------+
|  +---------------------------------------------------------+  |
|  |                                                         |  |
|  |  [leaf icon]  THE HERB POT CHALLENGE                    |  |
|  |                                                         |  |
|  |  Plant one pot this weekend.                            |  |
|  |  That's it. That's the whole first step.                |  |
|  |                                                         |  |
|  |  [pot icon]  1. Grab a pot, fill with compost (EUR 4)   |  |
|  |  [plant icon] 2. Plant a EUR 2 supermarket herb         |  |
|  |  [sun icon]  3. Windowsill, balcony, or doorstep.       |  |
|  |                 Water when dry.                          |  |
|  |                                                         |  |
|  |    EUR 10         15 min        Harvest: 2-4 weeks      |  |
|  |    total cost     total time    first pick              |  |
|  |                                                         |  |
|  |  It's spring. The growing window is open.               |  |
|  |  Your first harvest could be ready by June.             |  |
|  |                                                         |  |
|  |         [ Save the Challenge ]                          |  |
|  |          Share with a friend                            |  |
|  |                                                         |  |
|  +---------------------------------------------------------+  |
+---------------------------------------------------------------+
```

**Layout:**
- Background: Terracotta Glow (`#F0D5C4`). The section itself (the outer container) uses this background to create a full-width warm band across the page. The card within is either borderless (the section IS the card) or a white card with a left border accent.
- Alternative approach (recommended): The full section has a Terracotta Glow background. Content is centred, max-width 720px. A 4px left border in Dublin Brick (`#C45D3E`) runs the height of the content block.
- Small label at top: "THE HERB POT CHALLENGE" (Label/Tag size, all-caps, Primary Green, with a small leaf icon).
- Subhead: "Plant one pot this weekend. That's it. That's the whole first step." (Section Headline, DM Serif Display).
- Three steps: Each prefixed with a simple icon, Body Large text.
- Stats row: Three large figures in a horizontal row (Counter size for the numbers, Body Small for the labels beneath).
- Seasonal nudge: Body Regular, italic. A gentle aside.
- CTA: Primary button (full-width on mobile, auto-width on desktop). Primary Green background, white text, rounded corners (8px), generous padding.
- Share link: Text link below the button, Body Small, Primary Green.

**Developer notes:**
- The `id="herb-pot-challenge"` anchor on this section allows deep linking.
- The "Save" button can trigger a `window.print()` with a print stylesheet that shows only this section, or generate a simple shareable image via canvas, or simply copy the page URL with the anchor.
- The seasonal nudge line should be dynamically generated or easy to update -- it references the current season. A simple JS check of the month can update this: March-April = "spring planting," May-June = "summer planting," etc. Or hard-code and update manually each season.

---

## Section 6: "What Can I Grow?" -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|            What Can I Grow?                                   |
|            Answer 3 questions. Get your personalised          |
|            growing plan.                                      |
|                                                               |
|   Step 1 of 3: What space do you have?                       |
|                                                               |
|   +-------------+  +-------------+  +-------------+          |
|   | [windowsill |  | [balcony    |  | [rooftop    |          |
|   |  icon]      |  |  icon]      |  |  icon]      |          |
|   | Windowsill  |  | Balcony     |  | Rooftop     |          |
|   +-------------+  +-------------+  +-------------+          |
|                                                               |
+---------------------------------------------------------------+

After all 3 steps answered:

+---------------------------------------------------------------+
|                                                               |
|   +--------------------------------------------------------+  |
|   | YOUR GROWING PLAN                                      |  |
|   |                                                        |  |
|   | [basil icon] Basil -- pick from the top for bushy      |  |
|   |              growth. Plant now, harvest June.           |  |
|   | [mint icon]  Mint -- practically unkillable. Give      |  |
|   |              it its own pot (it spreads).               |  |
|   | [rocket icon] Rocket -- sow seeds directly. Ready      |  |
|   |               in 4 weeks.                              |  |
|   | [chive icon] Chives -- perennial. Plant once,          |  |
|   |              pick for years.                           |  |
|   |                                                        |  |
|   | [Try different answers]                                |  |
|   +--------------------------------------------------------+  |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Section heading: "What Can I Grow?" (Section Headline, centred).
- Subhead: "Answer 3 questions. Get your personalised growing plan." (Body Large, centred).
- Quiz area: Centred, max-width 640px. Each step replaces the previous (transition animation).
- Option cards: 3 in a row on desktop, 3 in a row (smaller) or vertical stack on mobile. Each option card: white background, rounded corners, subtle border, icon above text label. Min 120px wide, min 100px tall on desktop. Full-width stacked items on narrow mobile.
- Output card: Terracotta Glow background. Plant list with icons. Each plant is a row: icon + name (bold) + tip (regular). Generous spacing between plants.

**Developer notes:**
- The quiz logic is a JavaScript decision tree. Create a data object mapping input combinations to plant recommendations. For example: `{space: "windowsill", experience: "beginner", preference: "herbs"}` maps to `["basil", "mint", "parsley", "chives"]`.
- Each plant in the data object has: name, icon, tip, and seasonal note.
- The number of unique combinations is 3 (space) x 3 (experience) x 4 (preference) = 36. Some can share overlapping plant lists. The Communicator (Agent 05) will provide the specific copy for each recommendation.
- The step transitions can use CSS classes toggled by JS: `.quiz-step.active { opacity: 1; transform: translateX(0); }` / `.quiz-step.exiting { opacity: 0; transform: translateX(-20px); }`.

---

## Section 7: Growing Journey -- Wireframe

**Desktop:**
```
+---------------------------------------------------------------+
|                                                               |
|               Your Growing Journey                            |
|                                                               |
|   [1]--------[2]--------[3]--------[4]--------[5]--------[6] |
|    |          |          |          |          |          |   |
|  Plant a    Share a    Drop In    Claim     Become a   Start |
|  Pot        Photo      on Sat     Your      Regular    a     |
|  --------   --------   --------   Patch     --------   Roof  |
|  This       Show it    Meet       --------  Seasonal   top   |
|  weekend    off        neighbours Your own  rhythms,   ---   |
|  EUR 10     Join the   Free, no   containers shared    Bring |
|  15 min     community  commitment            harvests  the   |
|                                                        mission|
|  * YOU ARE                                                    |
|    HERE                                                       |
|                                                               |
+---------------------------------------------------------------+
```

**Mobile:**
```
+----------------------------+
|  Your Growing Journey      |
|                            |
|  [1] * YOU ARE HERE        |
|  |   Plant a Pot           |
|  |   This weekend, EUR 10  |
|  |                         |
|  [2] Share a Photo         |
|  |   Show it off           |
|  |                         |
|  [3] Drop In on Saturday   |
|  |   Meet your neighbours  |
|  |                         |
|  [4] Claim Your Patch      |  <- slightly faded
|  |   (dimmed)              |
|  |                         |
|  [5] Become a Regular      |  <- more faded
|  |   (dimmed)              |
|  |                         |
|  [6] Start a Rooftop       |  <- most faded
|      (dimmed)              |
+----------------------------+
```

**Layout:**
- Desktop: A horizontal path/timeline with 6 numbered nodes connected by a line. Each node has an icon circle, a title, and a 1-2 line description below. Node 1 has a "You are here" marker (a small badge or arrow in Dublin Brick colour).
- Mobile: A vertical timeline. Left-aligned. Each step is a row: number circle on the left, title and description on the right. Connected by a vertical line.
- Steps 1-3 are full opacity. Steps 4-6 have reducing opacity (0.7, 0.5, 0.4) to suggest "what comes next" without demanding attention.

**Content per step:**
1. "Plant a Pot" -- "This weekend. EUR 10. 15 minutes. Your first harvest in weeks."
2. "Share a Photo" -- "Show it off. Join the community. Inspire someone else."
3. "Drop In on a Saturday" -- "Meet your neighbours. Get your hands dirty. Free. No commitment."
4. "Claim Your Patch" -- "Your own containers at a community rooftop near you."
5. "Become a Regular" -- "Seasonal rhythms. Shared harvests. Saturday morning ritual."
6. "Start a Rooftop" -- "Bring the mission to your building. Grow the next 160."

**Developer notes:**
- The horizontal timeline on desktop can be built with CSS Flexbox and pseudo-elements for the connecting line.
- The number circles are `<div>` elements with `border-radius: 50%`, Primary Green background, white number text.
- The "You are here" badge is an absolutely positioned element on Step 1's node.
- The vertical timeline on mobile uses the same structure but with `flex-direction: column` and a left-side border as the connecting line.
- Steps 4-6 opacity is set via CSS classes. No JavaScript needed.

---

## Section 8: Dublin Rooftop Map -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|           Find Your Nearest Rooftop                           |
|                                                               |
|   40 rooftops across Dublin. Is there one near you?           |
|                                                               |
|   +--------------------------------------------------------+  |
|   |                                                        |  |
|   |        [Illustrated SVG map of Dublin]                 |  |
|   |                                                        |  |
|   |     Phibsborough [*]                                   |  |
|   |            Stoneybatter [*]     Docklands              |  |
|   |                  Smithfield [*]    [*]                  |  |
|   |           Liberties [*]                                |  |
|   |                Portobello [*]                           |  |
|   |                    Rathmines [*]                        |  |
|   |                                                        |  |
|   |   +----------------------------------+                 |  |
|   |   | STONEYBATTER                     |  <- info card   |  |
|   |   | 3 rooftops | 18 growers          |                 |  |
|   |   | Growing now: kale, herbs, garlic  |                 |  |
|   |   | Next drop-in: Sat 5 April, 10am  |                 |  |
|   |   +----------------------------------+                 |  |
|   |                                                        |  |
|   +--------------------------------------------------------+  |
|                                                               |
|   No rooftop near you yet? You could be the first.            |
|   Get in touch.                                               |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Section heading: "Find Your Nearest Rooftop" (Section Headline, centred).
- Supporting stat: "40 rooftops across Dublin. Is there one near you?" (Body Large, centred).
- Map: Centred SVG illustration. Max-width 800px on desktop, full-width on mobile. The map shows a simplified Dublin outline with labelled neighbourhood regions.
- Info cards: Positioned near the clicked region on desktop (absolutely positioned popover). On mobile, a bottom-sheet overlay within the map container.
- Below the map: A fallback/invitation line for areas without sites.

**Developer notes:**
- The map is an inline SVG with `<path>` elements for each neighbourhood region. Each path has a `data-neighbourhood` attribute and click/tap event listeners.
- Info card data is stored in a JavaScript object: `{stoneybatter: {rooftops: 3, growers: 18, growing: "kale, herbs, garlic", nextDropIn: "Sat 5 April, 10am"}}`.
- The SVG should be hand-drawn or stylised -- not a geographic projection. Think illustrated neighbourhood map like you'd find in a tourist guide. Warm line style.
- Active neighbourhoods have a green fill. Inactive neighbourhoods have a light grey fill. Both have the same line style.
- On mobile, consider a simpler alternative: a styled list of neighbourhoods with expandable details, with the map as a visual header element that links to the list below.

---

## Section 9: Seasonal Strip -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|            What's Growing Right Now                            |
|                                                               |
|  [<]  Jan  Feb  |MAR|  Apr  May  Jun  Jul  Aug ...  Dec  [>] |
|                  |   |                                        |
|             +----+   +----+                                   |
|             | MARCH         |                                 |
|             | Sow: radish,  |                                 |
|             | spinach, herbs|                                 |
|             | rocket, peas  |                                 |
|             | Indoors:      |                                 |
|             | tomatoes      |                                 |
|             +---------------+                                 |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Section heading: "What's Growing Right Now" (Section Headline, centred).
- The strip: A horizontal scrollable container. Each month is a card approximately 140px wide (desktop), 110px (mobile).
- Current month card: Larger (1.15x scale), Primary Green background, white text, centred on load.
- Other months: Morning Mist background, Deep Soil text. On hover/tap: slight scale-up, reveals additional text.
- Desktop: Left/right arrow buttons at the edges. Arrows are circular, Dublin Sky grey, with hover highlight.
- Mobile: Pure touch-scroll. No arrow buttons. Edge fade indicators (a gradient from white to transparent at left and right edges) signal more content.

**Content per month card:**
- Month name (bold, Card Title size)
- 2-3 crop icons (small, inline)
- 1-3 lines: "Sow: [crops]" and/or "Harvest: [crops]" and/or "Activity: [community event type]"
- Winter months are honest: "Jan: Quiet. Plan next year. Seed swaps." "Feb: Order seeds. Chit potatoes indoors."

**Developer notes:**
- Use CSS `scroll-snap-type: x mandatory` for the mobile scroll behaviour.
- Current month detection: `new Date().getMonth()` in JavaScript. Set the `data-current` attribute on the appropriate card. CSS styles the current card differently.
- `scrollIntoView({behavior: 'smooth', block: 'nearest', inline: 'center'})` on the current month card on page load.
- The month data can be a JavaScript array of objects or hard-coded in HTML. Given this is a static page, hard-coding is simpler and more performant.

---

## Section 10: Collective Goal Tracker -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|              Dublin Can Grow                                  |
|                                                               |
|              347 kg                                           |
|           of food grown by Dublin's rooftops this year        |
|                                                               |
|   [##############################-----------] 347 / 1,000 kg |
|                                                               |
|   Every pot counts. Every rooftop contributes.                |
|   Every grower is part of the number.                         |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Section heading: "Dublin Can Grow" (Section Headline, centred).
- Large animated number: "347 kg" (Counter/Large Stat size, DM Serif Display, Primary Green). Centred.
- Supporting line: "of food grown by Dublin's rooftops this year" (Body Regular, centred).
- Progress bar: Full content width (max 800px), centred. 16px tall, rounded ends. Track: `#D5E8D4`. Fill: Primary Green. A small label at the right end: "Goal: 1,000 kg" (Body Small).
- Below the bar: Supporting text (Body Regular, centred, Dublin Sky colour).

**Developer notes:**
- The number and progress percentage should be easily updatable: a single `data-current="347"` and `data-goal="1000"` attribute pair on the container element, with JavaScript reading these values for animation and bar width calculation.
- Progress bar width: `(current / goal) * 100%`. Capped at 100%.
- The pulse animation on the bar's leading edge: A small circle at the end of the fill area that scales from 1 to 1.3 and back, with opacity 1 to 0.5, three times, then stops. CSS `@keyframes` with `animation-iteration-count: 3`.

---

## Section 11: Final CTA -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|   [Subtle background: blurred hero image or warm solid]       |
|                                                               |
|           40 Rooftops and Growing.                            |
|           Be Part of the Next 160.                            |
|                                                               |
|           Start with one pot.                                 |
|           See what happens.                                   |
|                                                               |
|               [ Start This Weekend ]                          |
|                                                               |
|       Find a drop-in near you  |  Share this page             |
|                                                               |
|                See you on the rooftop.                         |
|                                                               |
+---------------------------------------------------------------+
```

**Layout:**
- Background: Deep Soil (`#2C3E2D`) or a soft overlay on the blurred hero image. All text is white or near-white.
- Headline: "40 Rooftops and Growing. Be Part of the Next 160." (Section Headline, DM Serif Display, white, centred).
- Subhead: "Start with one pot. See what happens." (Body Large, Inter, white at 90% opacity, centred).
- Primary CTA button: "Start This Weekend" -- large (minimum 56px height), white background, Primary Green text, bold. Centred. On click, smooth-scrolls to the Herb Pot Challenge section.
- Secondary links: Two text links, white, underlined, separated by a vertical bar or generous spacing. "Find a drop-in near you" scrolls to the map section. "Share this page" triggers Web Share API or copy-to-clipboard.
- Closing line: "See you on the rooftop." (Body Small, italic, white at 70% opacity). This is the last thing the visitor reads. It is warm, confident, and assumes the best of them.

**Developer notes:**
- The CTA button scrolling to the Herb Pot Challenge: Use `document.querySelector('#herb-pot-challenge').scrollIntoView({behavior: 'smooth'})`.
- The "Share this page" link: Check for `navigator.share` support. If available, use the native share dialog. If not, copy the URL to clipboard and show a "Copied!" toast.
- This section should have generous vertical padding (128px+) to feel spacious and final.

---

## Section 12: Footer & Agents Tab -- Wireframe

```
+---------------------------------------------------------------+
|                                                               |
|   ROOFTOP REPUBLIC                                            |
|   Turning Dublin's rooftops into community gardens.           |
|                                                               |
|   [Facebook icon]  [Instagram icon]                           |
|                                                               |
|   hello@rooftoprepublic.ie                                    |
|                                                               |
|   +--------------------------------------------------------+  |
|   | [v] How This Page Was Built -- The 5 AI Agents         |  |
|   +--------------------------------------------------------+  |
|                                                               |
|   When expanded:                                              |
|   +--------------------------------------------------------+  |
|   |  This landing page was designed and built by a team of |  |
|   |  5 AI agents as part of the 10,000 Hours of Play       |  |
|   |  Challenge.                                             |  |
|   |                                                        |  |
|   |  [01] Gamification Expert                              |  |
|   |  Octalysis Framework & Games for Good                  |  |
|   |  - Mapped 8 core drives to the challenge               |  |
|   |  - Designed the visitor journey...                      |  |
|   |                                                        |  |
|   |  [02] Urban Farming Expert  [03] Designer ...          |  |
|   |  ...                                                   |  |
|   +--------------------------------------------------------+  |
|                                                               |
|   (c) 2026 Rooftop Republic                                  |
+---------------------------------------------------------------+
```

**Layout:**
- Background: Deep Soil (`#2C3E2D`). Text: white and Dublin Sky grey.
- Top section: Rooftop Republic wordmark/name (Section Headline size, DM Serif Display, white), tagline (Body Small, Dublin Sky), social icons (inline, 24px, white), contact.
- Middle: The expandable academic tab. A bordered button/bar spanning the content width. Chevron indicates expandability.
- Expanded content: An intro paragraph, then 5 agent cards. On desktop: a 3+2 or 5-across grid. On mobile: vertical stack.
- Each agent card: Number badge, role title, expertise line, bullet points for contribution, influence summary.
- Bottom: Copyright line.

**Developer notes:**
- The academic section uses `<details>` and `<summary>` for the expand/collapse, same as the accordion.
- Agent cards are `<article>` or `<div>` elements in a CSS Grid container.
- The background colour of the expanded academic section can be slightly lighter than the footer (`#354836` or similar) to subtly distinguish it.
- Keep the copyright year dynamic: `new Date().getFullYear()` in a small inline script, or hard-code it.

---

## Final Notes for the Developer (Agent 04)

1. **Performance budget:** Target < 2 seconds First Contentful Paint on 3G. This means: compress all images to WebP (JPEG fallback), subset the Google Fonts (only load the weights/styles specified here), inline critical CSS, defer non-critical JavaScript.

2. **Fonts to load:** `DM Serif Display:400` and `Inter:400,500,600,400italic`. Use `<link rel="preload">` for the font files and `font-display: swap` to prevent invisible text.

3. **CSS architecture:** Use CSS custom properties (variables) for all colour, spacing, and typography tokens defined in this spec. This makes the design system maintainable and themeable.

4. **JavaScript scope:** Vanilla JS only. No frameworks, no libraries, no build tools. The interactive elements (quiz, counter animations, accordion, carousel dots, map interactions, seasonal strip) are all achievable with vanilla JS + Intersection Observer API + DOM manipulation.

5. **Semantic HTML:** Use `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<details>`, `<summary>`, `<figure>`, `<figcaption>`, `<nav>` (for the journey steps, if appropriate). Proper heading hierarchy: one `<h1>` (the hero headline), `<h2>` for section headings, `<h3>` for subsections.

6. **Accessibility testing:** Run Lighthouse, axe, and WAVE before shipping. Target: 100 accessibility score in Lighthouse. Test keyboard navigation through the entire page. Test with VoiceOver (Mac) or NVDA (Windows).

7. **Image strategy:** Hero image: `<picture>` element with WebP and JPEG sources at 640px, 1024px, and 1920px breakpoints. Other images: `loading="lazy"` attribute. All images have meaningful `alt` text.

8. **The page is a single HTML file** (plus CSS and JS files). No routing, no SPA, no build step. This deploys directly to GitHub Pages as a static site.

---

*Report prepared by Agent 03 -- Senior UX & Product Designer*
*For the Rooftop Republic Landing Page Project, 10,000 Hours of Play Challenge*

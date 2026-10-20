---
name: ProFix 360 Solutions LLC
description: Calm, ordered bands in the logo's navy and gold for a six-trade New Jersey outfit; every path ends in a Facebook Messenger estimate.
colors:
  lion-gold: "#f5b83d"
  lion-gold-bright: "#ffcb5c"
  gold-ink: "#7f5600"
  shield-navy: "#17325a"
  night-navy: "#0d1d36"
  ink: "#0d1d36"
  body-slate: "#28354a"
  soft-slate: "#4a5668"
  paper: "#f4f6fb"
  card-white: "#ffffff"
  field-mist: "#e6ecf5"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c6d3e6"
  focus-blue: "#2f6fd6"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.6vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  band-phone: "64px"
  band-desktop: "96px"
  card-inset: "22px"
  stack: "14px"
components:
  button-primary:
    backgroundColor: "{colors.lion-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
    typography: "{typography.label}"
  button-primary-hover:
    backgroundColor: "{colors.lion-gold-bright}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    padding: "12px 0"
    height: "72px"
  row-arrow-hover:
    backgroundColor: "{colors.lion-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "44px"
  audience-card:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.soft-slate}"
    rounded: "{rounded.card}"
    padding: "22px 22px 24px"
  form-card:
    backgroundColor: "{colors.card-white}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input-text:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card-white}"
  step-number:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.pill}"
    size: "48px"
  messenger-float:
    backgroundColor: "{colors.lion-gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: ProFix 360 Solutions LLC

## Overview

**Creative North Star: "The Lion's Shield, Calmly Ordered"**

The whole system is the logo's world laid flat: a gold lion on a shield, translated into full-bleed bands of off-white paper, shield navy and night navy, with the lion's gold as the single warm accent. It is the house calm band style: soft borderless shapes, one display webfont, generous vertical rhythm, and no photography (none exists for this business). Order does the persuading. Each band is one idea, light and dark alternate so a new section is unmistakable on a phone, and every interactive path ends at the same place, a Facebook Messenger conversation.

Density is low and thumb-first. Phone is the design surface (most visitors arrive inside Facebook's in-app browser); desktop widens the same bands into two-column splits rather than adding content. The shield mark itself is the only image: small in a night-navy tile in the header, large beside the hero on desktop.

Motion is restrained to three moves: the hero headline bouncing in letter by letter, a single 12px fade-up for content below the first screen, and the floating Messenger circle sliding in once the hero is gone. Everything is visible at rest, without JS, and under reduced motion.

**Key Characteristics:**
- Paper, two navies, one gold; the ground is never black.
- Gold is a fill; text on gold is ink navy.
- Full-bleed bands alternate light and dark; night navy carries a faint diagonal line texture.
- Soft, borderless forms: 24px cards, pill buttons and chips, 10px tinted fields.
- Cal Sans for every heading, label and button; system stack for running text.
- One contact channel: Messenger. No phone, no email anywhere.

## Colors

A cool navy-and-paper field with one warm gold, taken straight from the ProFix logo.

### Primary
- **Lion Gold** (`lion-gold`): the one accent, used only as a fill: primary buttons, the floating Messenger circle, the arrow circle on hover/focus, the text-selection highlight, and the dot inside the eyebrow pill. On dark bands it may also colour the last phrase of a heading ("New Jersey.", "do.").
- **Lion Gold Bright** (`lion-gold-bright`): the hover state of gold fills only. Never a resting colour.
- **Gold Ink** (`gold-ink`): gold when it has to be text or an icon on a light ground (the header Messenger glyph, header link hover, accent words on paper). About 6:1 on paper.

### Secondary
- **Shield Navy** (`shield-navy`): the mid band. Hero, services and closing call to action sit on it.
- **Night Navy** (`night-navy`): the deep band. Footer, with the diagonal line texture, and the tile behind the header shield mark.

### Neutral
- **Ink** (`ink`): headings on light, text on gold, the selected chip fill and the step-number discs. Same value as Night Navy, different job.
- **Body Slate** (`body-slate`): running text on light grounds.
- **Soft Slate** (`soft-slate`): secondary text on light: ledes, card copy, step detail, placeholders, helper notes.
- **Paper** (`paper`): the page ground and light bands; also the theme colour.
- **Card White** (`card-white`): cards and the estimate form sitting on paper.
- **Field Mist** (`field-mist`): fill for inputs and chips on the white form card (paper on white was too faint to see a field).
- **On Dark** (`on-dark`) and **On Dark Soft** (`on-dark-soft`): headings and body text on the navy bands.
- **Focus Blue** (`focus-blue`): hover and focus outlines on light grounds and form controls. Deliberately not gold, so a focus ring never reads as a button fill.
- **Error Red** (`error-red`): inline error sentences and the invalid-field border.
- **Hairline** (`rgba(13,29,54,.12)` on light, `rgba(255,255,255,.12)` on navy): the only dividers, between service rows.

### Named Rules
**The Gold Is a Fill Rule.** Lion Gold never sets text or icons on a light ground; use Gold Ink there. Text on a gold fill is always Ink, never white (both alternatives fail contrast at about 2.2:1).

**The Never Black Rule.** The darkest surface is Night Navy. Even the logo's black ground becomes the night-navy tile behind the shield.

**The Two Focus Colours Rule.** Focus rings are Focus Blue on light grounds and Lion Gold on navy bands and the footer; each is chosen to stand off its ground.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system UI stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A friendly, rounded geometric display face does all the talking (headings, buttons, row titles, field labels), always at its single regular weight (400), while plain system text carries the reading. Two faces, one webfont request.

### Hierarchy
- **Display** (400, clamp(42px, 12vw, 80px) on phones, clamp(56px, 7.4vw, 84px) from 760px, line-height 1.02): the hero H1 only, max 12ch on phones and 14ch on desktop. It names the place.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): section H2s, balanced wrap.
- **Title** (400, clamp(20px, 5.6vw, 24px), 1.15): service rows, audience card H3s (24px), step titles (21px), the Facebook link row (18-20px).
- **Lede** (system 400, clamp(17px, 4.6vw, 19px), 1.5): the hero promise and section ledes, held to 32-40ch.
- **Body** (system 400, 16px, 1.7): all running text. Inputs are 16px so iOS never zooms.
- **Label** (Cal Sans 400, 17px, 1.2): form legends and labels; buttons use the same face at 18px, line-height 1.

### Named Rules
**The One Weight Rule.** Cal Sans is used at 400 only. Hierarchy comes from size and colour, never from bolding the display face.

**The One Bounce Rule.** Only the hero H1 animates letter by letter. No other heading moves except via the shared fade-up.

## Layout

A single centred column (max 1160px) with a 20px gutter on phones and 40px from 760px. Bands are full-bleed with 64px vertical padding on phones and 96px from 760px; the hero runs 56/64px on phones and 96/112px on desktop. Section heads stack an optional label, the H2 and a lede with 16px gaps, capped at 640px wide.

Phone first, then two steps:
- **760px:** wider gutter and band padding; audience cards go to three columns; hero buttons sit side by side (min 240px each); the large shield appears to the right of the hero copy.
- **1024px:** the services band splits into a narrow heading column and a two-column list of rows; the estimate band splits into a sticky heading-and-steps column beside the form; the closing band puts its heading and button on one line.

Groups use small, consistent stacks: 12-16px between related items, 22-28px between form fields and between a list and the link that follows it, 32px from a section head to its list.

**The Same Bands, Wider Rule.** Desktop never adds content; it widens the phone bands into side-by-side columns.

## Elevation & Depth

Flat by default. Depth comes from tonal layering: white cards and the form on paper, navy bands against paper, and a faint 135-degree line texture on the darker surfaces (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`, used on the hero and the footer). Exactly one element casts a shadow: the floating Messenger circle, because it genuinely floats over content.

### Shadow Vocabulary
- **Float** (`box-shadow: 0 10px 28px rgba(8,20,40,.3)`): the floating Messenger circle only.

### Named Rules
**The Faint Lines Rule.** The diagonal texture stays at about 4% white or fainter, so it never reads as lines through text.

**The One Floater Rule.** Nothing at rest has a shadow except the element that actually sits above the page.

## Shapes

Soft and borderless. Containers use a generous 24px radius, every button and chip is a full pill, text fields take a gentler 10px corner, and round elements (arrow circles, step numbers, the float) are true circles. Borders appear only as 2px transparent reserves that turn Focus Blue on hover/focus or Error Red when invalid; outlined ghost buttons are the one resting stroke. Dividers are 1px hairlines between service rows and nothing else.

## Components

### Buttons
Big, round and plain: a thumb-sized pill with a display-face label.
- **Shape:** full pill, 56px tall, 26px side padding.
- **Primary:** Lion Gold fill, Ink label, 18px Cal Sans. Messenger actions carry the Messenger glyph (20px) to the left of the label. Full width in the form and on phones in the closing band.
- **Hover / Focus:** hover brightens to Lion Gold Bright (pointer devices only, via `hover:hover`); press scales to 0.98; focus is a 3px outline offset 3px (gold on navy, blue on light).
- **Ghost:** transparent with a 2px 70%-white outline and On Dark label, used only on navy beside a primary. Hover turns the outline solid white over a 10% white wash.
- **Text link button:** underlined 600-weight system text in Ink, 44px tall, for secondary actions inside the form's sent state.

### Service Rows
The signature list on navy. The whole row is the link; only its arrow changes.
- 72px minimum height, Title type in On Dark, 1px 12%-white hairline between rows.
- A 44px circle holding an arrow sits at the right on a 10% white fill; on hover or focus it fills with Lion Gold and the arrow turns Ink. The row itself gets no background, underline or shadow.
- Tapping a row jumps to the form and pre-selects the matching job chip, with a brief blue outline to show it was picked.
- The same row-plus-arrow pattern appears on paper as the white "Follow our work on Facebook" link card (20px radius, faint ink arrow circle).

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on paper.
- **Shadow Strategy:** none (see Elevation & Depth).
- **Border:** none.
- **Internal Padding:** 22px sides, 24px bottom. Audience cards are not links and have no arrow.

### Inputs / Fields
- **Style:** Field Mist fill, no visible border (2px transparent reserve), 10px radius, 52px tall, 16px Ink text, Soft Slate placeholder; textareas 110px tall and vertically resizable. Labels sit above in Cal Sans 17px; "(optional)" is a 14px Soft Slate aside.
- **Focus / Hover:** the reserve border turns Focus Blue.
- **Error:** a plain-sentence message in Error Red below the field, and an Error Red border that holds even while focused.

### Chips
- **Style:** Field Mist pill, 48px tall, 18px side padding, 16px system text in Ink; radio inputs underneath for single choice.
- **State:** selected fills with Ink and turns the text white; hover adds a Focus Blue border; keyboard focus is a 3px Focus Blue outline offset 2px (an outline, because a border cannot be seen on the Ink fill).

### Navigation
- **Header:** slim paper bar (64px, 76px from 760px): the shield in a night-navy tile plus the "ProFix 360" wordmark in Cal Sans with "Solutions LLC" beneath it, left; "Message us" with a Gold Ink Messenger glyph, right. There is no menu and no phone number.
- **Footer:** night navy with the line texture; business name and area, then the Facebook link. Links are On Dark, turning gold on hover, 44px tall.

### Floating Messenger Circle
A 60px Lion Gold circle with an Ink Messenger glyph, bottom right inside the safe area, with the Float shadow. It slides up (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero leaves view and hides while the form, closing band or footer is on screen, so two Messenger controls never show together. When hidden it is removed from the tab order and from assistive tech.

### Numbered Steps
Three steps, each led by a 48px Ink disc with a white Cal Sans numeral, then a Title-weight line and a Soft Slate detail line.

## Do's and Don'ts

### Do:
- **Do** keep Lion Gold to fills and set Ink on top of it; use Gold Ink when gold must be text on paper.
- **Do** alternate full-bleed light and dark bands so each section starts visibly.
- **Do** route every call to action to Messenger, with the greeting or composed message pre-filled.
- **Do** keep tap targets at 44px or larger and inputs at 16px or larger.
- **Do** gate hover styles behind `(hover:hover)` so taps never leave a stuck state.
- **Do** keep everything visible without JS and under reduced motion; motion only ever adds.

### Don't:
- **Don't** use black as a ground; the darkest surface is Night Navy.
- **Don't** set white or gold text on a gold fill or gold text on paper.
- **Don't** add a phone number, email, or any contact channel besides Messenger and the Facebook page.
- **Don't** add shadows to cards, buttons or the header; the floating circle is the only shadow.
- **Don't** animate any heading other than the hero H1 letter by letter.
- **Don't** invent reviews, prices, counters, towns or work photos; leave gaps out.
- **Don't** add more eyebrow pills. The three in the build ("Free estimates", "Homes and businesses", "Three steps") are an owner-approved house-style exception that Impeccable flags as an anti-pattern; they are not a system component for new surfaces.

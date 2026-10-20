# ProFix 360 Solutions LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/profix360Solutions/ · **Repo:** https://github.com/10elizabethbell/profix360Solutions · **Built:** 2026-10-20 from Muse brief 2026-10-20 (NJ Seeking Contractors group ad) · **Call Sheet:** site added

## What's built
- Single-file `index.html`, calm band style: paper header → navy hero → paper "Your place, treated like ours" (homes / restaurants / offices + Facebook row) → navy "What we do" (six service rows) → paper "Your free estimate" (3 steps + form) → navy close → deep-navy footer.
- Order: hero → who we work for → what we do → free estimate (3 steps beside the form) → close → footer. Gold is reserved for actions: step numbers are ink circles.
- Palette from the logo: the lion's gold `#f5b83d` as the one accent (fills only, `#7f5600` when it's text on light), navy `#17325a`, deep navy `#0d1d36`, paper `#f4f6fb`. Ground never black even though the logo is black-and-gold.
- Shield-and-lion mark cut out of the Facebook profile logo (black keyed out): header mark, crest in the tablet/desktop hero, favicon, iPhone icon, og image.
- Hero: plain textured navy (no photos exist; see gaps), gold lion crest on the right from 760px up. H1 "Cameras to Christmas lights, done right in New Jersey." bounces in letter by letter; promise line is the owner's own words.
- **Contact is Facebook Messenger** (`https://m.me/61593473346111`), because there is no phone or email. Header top-right says "Message us" where a phone number would go. The estimate form follows the owner's process ("Send a few pictures and your town"): job chips, home/business, town (required), name (required), notes → opens Messenger with the message prefilled (`?text=`) and tells them to attach their pictures there. The message is also copied to the clipboard (best effort) before Messenger opens, and a copy-message box plus "Open Messenger" link appear as a fallback. Without JS the form still sends the visitor to Messenger.
- Floating gold Messenger circle: hidden on the hero, shown below it, hidden over the form, the close band and the footer.
- Service rows pre-select the matching job chip in the form.

## Assumptions I made
- **"We" voice:** it's an LLC and the page writes "message us".
- **H1 "Cameras to Christmas lights, done right"**: my line, spanning their first and last listed services so the niche (cameras) is on the first screen. Runner-up: "One crew for every fix in New Jersey." (first build; the finish reviewer called it generic).
- **Customer cards copy** (homes: "work carefully… leave it clean"; restaurants: "done neatly in a room your customers see"; offices: "network cable run tidy and out of sight") is inferred from "clean work… attention to detail". Owner should confirm.
- Navy is my choice (logo has only gold, silver and black).
- Placeholder town in the form is "Toms River", purely as an example.

## Placeholders and gaps
- **No phone number.** If they have one, put it in the header top-right (replacing "Message us"), the close band and footer, and consider switching the circle and form to `sms:`.
- **No email** → nothing in the footer for it.
- **No work photos.** The only image is a flyer inside a login-walled group post; Muse couldn't get it and neither could I. Hero stays plain navy; no proof section. Photos are the biggest upgrade.
- No reviews, prices, hours, owner name, towns, years in business; none shown.
- The Facebook row says "Follow our work on Facebook" (softened from "See our work": the page has 2 followers and may have no work posts yet). Once photos are on the page, switch to "Click to see more of our work."

## Questions for the owner
- Phone number, and do you take texts?
- Can you send 6–10 photos of jobs (cameras installed, cable runs, painted rooms, lights)? Before/afters especially.
- Which towns/counties do you actually cover?
- Your first name, so the page can say who they'll deal with?
- Insured? Licensed (NJ HIC number)? Low-voltage licence?
- Which services bring the most work (to order the list)?
- Are Christmas-light bookings open, and from when?

## Ideas not built (yours to pick)
- **Runner-up world (opt-in signature motion):** a security camera's view: a soft scanning sweep / recording dot across the hero, or a strand of Christmas lights along the hero's bottom edge that light up as you drag (seasonal, late October). Other worlds considered: paint roller stroke, CAT6 cable running between sections, LED glow following the finger.
- Seasonal Christmas-light band in Nov–Dec ("Christmas lights up before the first frost"), only once the owner confirms bookings.
- Photo proof section with 4:5 work cards as soon as photos arrive; then a real photo hero.
- Web Share with files: let the visitor pick photos in the form and share them straight into Messenger (needs testing in Facebook's in-app browser; Messenger's share picker makes them find the page, so it may be clumsier than attaching in chat).
- Facebook Messenger chat plugin / AI estimate assistant later (the paid-software pitch).
- Lion on the phone hero: the crest is hidden under 760px to keep the first phone screen clean; a small crest above the eyebrow could carry the brand there.
- Size-matched fallback font (`size-adjust`) so the H1 doesn't reflow when Cal Sans loads.
- Impeccable findings kept because they're your calm-style choices: eyebrow pills (craft floor bans eyebrows), H1 letter bounce-in (overshoot easing, letters start invisible), floating Messenger circle (overlaps card text while scrolling past), Cal Sans, the diagonal band texture (detector "repeating stripes"; ignored for index.html in `.impeccable/config.json`), same-size Homes/Restaurants/Offices cards. Detector "hero cramped padding" was a false positive, also ignored.

## Not verified
- `m.me/61593473346111?text=…` redirects to `m.facebook.com/msg/1245283578675549/?text=…` (checked with curl), so the link resolves to a thread and keeps the text. Not checked: that the text actually lands in the composer on iOS/Android inside Facebook's in-app browser. If it doesn't, the clipboard copy and copy box cover it. Test before pitching.
- Clipboard write before navigating may be blocked in the in-app browser.
- Real-device touch and frame rate on old phones.

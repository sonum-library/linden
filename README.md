# Linden

**Read your skin.**

Live: https://sonum-library.github.io/linden/

Linden is a skin reading and routine intelligence app. It is built on one
idea: most skincare tools try to sell you more products, whereas this one is
designed to get better results from what you already own.

## What it does

**Your shelf, understood.** Add a product by scanning its barcode, or by name.
Paste the ingredient list and Linden reads it: retinoids, acids, vitamin C,
benzoyl peroxide, niacinamide, azelaic acid, peptides, sunscreen filters,
fragrance and more.

**Conflicts, before they happen.** The evening you put a glycolic toner and a
retinal in the same routine, it tells you, and why. Vitamin C next to benzoyl
peroxide, copper peptides next to acids, a retinoid in the morning, a morning
routine with no sunscreen. Grounded in well-established chemistry, not folklore.

**Order, dose and placement.** Each step in the right sequence, with how much
to use ("one pea-sized amount, not more"; "two full finger-lengths of
sunscreen") and where it goes ("full face, avoiding the eyelids and the
corners of the mouth").

**Your pace, not the average.** Log how full each product is now and then, and
Linden learns your consumption rate. Someone with a smaller face uses less and
gets through products more slowly than the label assumes. It tells you when
something will run out at your rate, and when it will expire before you finish
it.

**The judgement window.** Most skincare fails because people give up on a
product at two weeks when it needs eight. Mark something as new and Linden
tells you when a fair verdict is due, and asks you to change nothing else until
then.

**Active load.** It totals your exfoliating actives across the whole shelf and
flags when the weekly load exceeds what your skin type comfortably carries.

**The purchase gatekeeper.** Before buying, state the problem. Linden checks
whether you already own something for it, whether you are mid-way through
testing something else, whether your active load has room, and whether there
is time before an event. Then it proposes the lowest-risk experiment first.
Buying is the last resort.

**Routine modes.** One tap for barrier repair days, breakout days, travel or dry
climates, post-workout, five-minute mornings, and pre-event lockdown.

**Where you are.** Live UV index, humidity and air quality for your location,
from free open weather data, so the routine can adjust on high-UV or dry days.

**Dormant products.** If you have not touched something in six weeks, it asks
whether to retire it.

**A summary for your clinician.** A plain-text export of your routine, actives,
recent changes, conflicts and load, to bring to an appointment.

**Photo readings.** Take a photo inside the app, lined up against a faint
ghost of your last one. Linden measures five zones (forehead, under-eye,
T-zone, cheeks, chin) for redness, shine, texture and spots. Redness is scored
relative to your own skin tone rather than a fixed number, so a fair face and a
deep face are each read against themselves.

**The integrity check.** Before it trusts a comparison, it confirms the
lighting, colour temperature, distance and time of day match. When they do
not, it tells you the apparent change may be the light rather than your skin.

**The Swans.** Your photos, side by side across weeks, with what changed in
your routine between them, and a proof view you can save as an image.

**The diary.** Speak or type. "Tight but oily, stung after moisturiser, slept
badly" is filed as stinging, tightness, oiliness and poor sleep, ready to
correlate.

**Flare-up forensics.** Log a flare and it lists everything that changed in the
fortnight before, newest first, because the newest change is usually the
culprit.

**Patterns.** Comparable readings before and after each product started, so it
can say "redness down 34 percent since the azelaic acid" or "redder since the
retinal, consider easing it back".

**Ask your history.** "When was my skin last calm?" "Is the azelaic working?"
"What changed before the flare?" "How long have I used the retinal?" Answered
from your own data.

**Installable.** Add it to your home screen and it opens offline. Reminders for
verdict days, high-UV days and the week before an event, if you allow them.

**The Valise handshake.** If a trip saved in Valise starts within three days,
Linden notices and offers travel mode.

## How it is built

A single self-contained HTML file. No framework, no build step, no backend, no
accounts, no tracking. Everything is stored in your own browser on your own
device and never leaves it. Hosted free on GitHub Pages.

Barcode lookup uses Open Beauty Facts. Speech uses your browser's own recognition. Weather and air quality use Open-Meteo.
Typefaces are served by Google Fonts.

## An honest note

Photo readings are pixel measurements, not dermatology. They are useful for
tracking change in your own skin under consistent light, and for nothing else.
Linden reads and measures. It does not diagnose, and nothing in it is medical
advice. See a clinician for anything that worries you.

## License

Copyright (c) 2026 Sonum Samra. All rights reserved. Proprietary software. You
are welcome to use it at the link above. You may not copy, modify, redistribute
or host it. See [LICENSE](LICENSE).

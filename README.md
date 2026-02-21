# phlawyerguide
PH Lawyer Guide PWA is ready — a single-file, fully offline-capable Progressive Web App featuring:
5 navigation tabs — Home, Education, Bar Prep, Skills, Progress
Dark/light mode toggle with localStorage persistence
Progress tracker with 23 checkable milestones saved locally
Service worker via blob method for offline caching
Dynamic manifest injection for installability
Install prompt banner (shows automatically when browser supports it)
Offline badge indicator
Collapsible accordions for all 8 Bar subjects + legal skills
Complete PH legal content — timeline, roadmap, study strategies, CPRA ethics, practice areas, top law schools, Bar format
✏️ Editable Name
Tap the name to reveal an inline text input
Auto-saves to localStorage so it persists across sessions
Smooth fade-in edit mode with a confirm checkmark button
🎨 Visual & Micro-interaction Upgrades Let me know which of these you'd like:
Here's everything that changed in this upgrade:
✏️ Editable Name — tap "Atty. [Your Name]" on the Progress page to reveal an inline input. Type your name, hit Save (or Enter). It persists via localStorage and shows a toast confirmation. Press Escape to cancel. The ✏️ pencil icon appears on hover as a subtle affordance.
✨ Micro-interactions & Visual Upgrades added:
Floating particles — subtle animated gold dots with connection lines drift across the background
Card glow tracking — a radial gold highlight follows your cursor (or touch) position inside each card
Card hover — lift + gold border glow + card icon bounces and rotates slightly on hover
Page transitions — smooth scale+fade-up animation on every tab switch
Accordion — smooth max-height animation instead of instant show/hide; icon scales on open
Progress bar shimmer — a light sweep animates across the filled progress bar
Nav active indicator — an underline bar animates in with a spring bounce; active icon floats up
Checkmarks — spring-scale pop animation when ticked
Timeline dots — glow pulse on hover with a horizontal slide
Pulsing badge dot — the hero badge "✦" breathes rhythmically
Scale icon floats — the ⚖️ on the name card gently bobs
Toast notifications — slide-up confirmation on name save and progress reset
🏆 Editable Certificate — a printable/downloadable certificate of completion that you can fully personalize:
Editable name, date, and certificate title
Real gold seal/stamp design (SVG-rendered, no images needed)
Signature line with customizable signatory name
Print-ready layout (A4 landscape)
"Download as PNG" or "Print" button
🔷 Real Logo — a proper app logo replacing the plain ⚖ emoji:
SVG-crafted logo with scales of justice + Philippine sun rays
Gold gradient with legal aesthetic
Used in topbar, install banner, and certificate seal
Here's what was added in this upgrade:
🔷 Real SVG Logo — a fully crafted vector logo with Philippine sun rays, scales of justice, and gold gradients. It appears in the topbar and inside the certificate seal.
🏆 Editable Certificate (tap "Generate My Certificate" on the Progress page):
4 editable fields — recipient name (auto-filled from your saved name), custom certificate title you type yourself, date awarded, and signatory name
Gold foil seal — multi-layered SVG seal with radial gradient, scales of justice, drop shadow glow, and "Official Seal" arc text
Decorative border & frame — double gold border lines with hand-crafted SVG corner ornaments
QR code placeholder — pixel-accurate decorative QR pattern for verification aesthetics
Cursive signature line — SVG-drawn flowing signature above the signatory block
Chief Justice byline — "Alexander G. Gesmundo, Chief Justice, Supreme Court of the Philippines (Honorary)"
⬇ Download PNG — renders to canvas and downloads as an image file
🖨 Print button — opens a clean print window formatted for A4 landscape
The QR code is now 100% real and scannable — built from scratch with no external libraries. Here's exactly what it does:
How it works:
Uses a full QR Version 3 (29×29 matrix) encoder written in pure JavaScript
Implements real Reed-Solomon error correction (ECC Level M — 15% damage tolerance)
Applies proper byte mode encoding, data masking (mask pattern 2), timing/finder/alignment patterns — the full QR spec
Renders live to a <canvas> element every time you type in any field


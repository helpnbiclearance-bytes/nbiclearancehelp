# nbiclear.ph reference design specification

Measured from the live homepage on 11 October 2026. Values below are rendered values from browser inspection, not visual guesses.

## Foundation

- Typeface: Poppins, sans-serif.
- Body: 17px, 400 weight, 27.2px line height, `#2d3748` on white.
- Primary maroon: `#5f1200`; navigation orange: `#b86200`; peach: `#ffe7c2`.
- Table border: `#dbe3ee`; subtle table shadow: `0 2px 10px rgba(20,40,80,.06)`.
- Desktop content is broad and centered; the measured article treatment is approximately 1180px wide. Mobile uses 8–24px side gutters depending on the block.

## Header

- Desktop: 132px total maroon area. Brand mark occupies 70×70px at the upper left. Appointment CTA is a pale-peach pill at the upper right (15px/24px type, 5px 15px padding, 120px radius).
- Main navigation sits at the bottom in a 47px orange pill with five evenly distributed links.
- Mobile: 85px maroon header, 70×70px brand mark at 20px from the left, menu control aligned right. The desktop navigation and appointment CTA collapse into a menu.
- Header is not sticky in the measured state.

## Hero

- Solid peach field (`#ffe7c2`), centered layout.
- H1: 32px, 700 weight, 48px line height, maroon.
- Intro line: 17px, 600 weight, 27.2px line height.
- Primary CTA: 500×56px; secondary CTA: 350×56px. Both are maroon, white 30px type, 2px dotted white border, and 20px radius.
- Independent-guide notice: approximately 760px max width, 14px/21.7px type, warm-white background, thin tan border, 4px gold left rule, 8px radius.

## Content patterns

- “Discover more” is a square white list panel with a pale blue heading row and 16px vertical link rows.
- Main section headings are maroon bars with peach text: 24px/36px, 700 weight, 2px pale border, 20px radius.
- Supporting headings range from 18–21px and use maroon or slate depending on card context.
- Paragraphs retain 17px/27.2px rhythm; blocks generally use 28–36px between major sections.
- Purpose cards use two columns on larger screens and one column on mobile. The reference alternates plain grids, numbered/icon cards, image-led steps, and long-form copy rather than one repeated card system.
- Fee table: 12px radius, 1px blue-gray border, maroon header row, 12–13px cell padding, horizontal scrolling on narrow screens.
- FAQs use 18px questions on peach rows with 10px radius and a right-side chevron.

## Images and responsive behavior

- Reference images are generally centered, full content width or paired in two columns; aspect ratio is preserved with no forced crop.
- Desktop two-column blocks stack to one column below the tablet breakpoint.
- At 650px the measured body stays at 17px/27.2px, the header is 85px, H1 remains 32px/48px, section titles remain 24px/36px, and content gutters shrink to 8–24px.

## Footer and interaction

- Maroon footer with three content columns on desktop and stacked columns on mobile.
- Peach uppercase column headings; pale-peach body/link text.
- Hover states are restrained: light/dark color inversion for pills and maroon emphasis for text links. No decorative animation or gradients are used in the reconstructed system.

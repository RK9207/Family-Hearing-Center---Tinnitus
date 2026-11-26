# Design system

**Family Hearing Practice · Tinnitus care · Flower Mound, Texas**

## Visual direction

Use a warm, uncluttered healthcare design with real local photography and clear typographic hierarchy. The first screen should immediately communicate tinnitus care, Flower Mound, the value of an evaluation, and **Book Appointment**. Start with a human moment, make the visit easy to understand, then show the people and proof behind the service. Use restrained surfaces and spacing to distinguish the final booking and request choices.

## Color and typography

| Role | Starting value | Use |
| --- | --- | --- |
| Brand blue | `#197FC4` | Brand accents, large action elements, and the mobile call bar |
| Accessible action blue | `#146BA6` | Standard-size white CTA labels and blue text links on light surfaces where contrast requires it |
| Brand brown | `#4E3110` | Heading text, including the page title |
| Body ink | `#292724` | Body text and form guidance |
| Muted ink | `#5C5751` | Secondary text and metadata |
| Warm tint | `#FAF6F0` | Selected section surfaces such as the booking close |
| White | `#FFFFFF` | Primary reading surface, cards, and dialog surface |
| Divider | `#E6DED3` | Decorative dividers and card borders. Give interactive controls stronger boundaries as needed. |

The brief specifies white text and icon on brand blue for the sticky call bar. Use a bold label at about 20 px so it qualifies as large text. White on brand blue is about 4.3:1. Check contrast with the rendered typography and all default, hover, active, and focus states. Use a visible focus ring with sufficient contrast against adjacent colors.

| Role | Typeface and range | Guidance |
| --- | --- | --- |
| H1 | Outfit 600–700, about 36–56 px | Line height around 1.08–1.15. Keep service and location prominent. |
| H2 | Outfit 600, about 28–40 px | Use strong headlines that still read as a story when scanned in order. |
| H3 and step titles | Outfit 600, about 20–24 px | Distinguish clinic credentials, the visit steps, and section-level subtopics. |
| Body | Montserrat 400–500, about 16–18 px | Line height around 1.55–1.7. Keep paragraphs short and lines comfortable. |
| Labels, buttons, metadata | Montserrat 500–700, about 14–16 px | Keep booking labels prominent and the mobile call label large enough for its contrast requirement. |

## Layout and spacing

- Use a content width of about 1,180 px and a reading measure around 60–68 characters. Give FAQ and other text-led sections a narrower column.
- Use an 8 px spacing rhythm with 20–24 px mobile gutters and 32 px or more on larger screens. Aim for roughly 48–64 px section padding on mobile and 72–96 px on desktop. Tighten brief sections so their height reflects their content.
- Start with a responsive grid that supports a two-column hero and office section. Collapse these at around 760 px, or sooner if text or controls crowd. Use about 1,024 px as a starting point for full header navigation and check the actual logo, phone, and CTA fit. Use the widget’s supplied 600 px sizing breakpoint.
- Use modest rounding around 8–12 px on controls and cards and up to about 20 px on the hero image or dialog. Use thin borders and light shadow where a surface needs definition. Keep line icons consistent and use them to identify an action or convey useful context.
- Preserve a stable reading order across breakpoints. Allow text resizing and wrapping. Use anchor offsets for the sticky header, and page-end padding for the sticky call bar.

## Components

| Component | Rules |
| --- | --- |
| Header | Sticky on desktop with the supplied logo on the left, balanced anchor navigation, the phone CTA, and **Book Appointment**. On mobile keep the logo and booking button. The logo links to the clinic website. Keep the header height stable on scroll. |
| Primary CTA | Use a clear, filled blue button with the same label and behavior at all four booking moments. Use comfortably sized targets, with about 44 px as the minimum target height. Provide visible keyboard focus. Style the phone CTA and utility links below booking in visual priority. |
| Booking dialog | Use the supplied booking widget in an accessible dialog with an announced title and visible close button. Verify initial focus, Escape, keyboard navigation around and into the iframe, restoration of focus, and scroll containment. Keep the close control visible at short viewport heights. Test the supplied iframe heights and the mobile breakpoint on a real browser. Surface the phone option if booking cannot load. |
| Visit steps and cards | Use numbers to indicate visit order. On desktop, a short row or vertical sequence can work. Stack sequentially on mobile. Use cards selectively for true peers such as reviews. Treat care options and clinician credentials as a composed editorial section. |
| Reviews | Show the verified Google rating/count with a linked hero badge and a dedicated reviews section. Keep up to six reviews visible on desktop and up to three on mobile. Display actual review wording and attribution as accessible text. Use **Read all our Google reviews** to reach the source. |
| FAQ | Use a narrow text-led accordion with ordinary question headings, a clear expand/collapse indicator, and keyboard-operable controls. Keep answers collapsed by default and maintain focus indication when expanded. |
| Request form | Use the supplied form embed with its title and consent configuration. Display a separate **Request an Appointment** heading and explain follow-up. Reserve sufficient height to avoid layout jumps. Verify that fields, consent, errors, and the confirmation state remain usable at narrow widths. |
| Map and directions | Use the supplied embedded map in a responsive reserved-size frame, with an accessible title and lazy loading. Put the address in live text and **Get Directions** directly below the map with a location icon. |
| Mobile sticky call bar | Place the brand-blue bar at the bottom with the white phone icon and **Call** label. Link directly to the Flower Mound number. Account for safe-area insets and avoid overlaying the form, dialog, or footer. |
| Footer | Use the appropriate supplied logo variant if the surface calls for it. Include privacy, website, contact/location details, and the brief’s copyright format using the practice name and current year. |

Use restrained transitions for state changes. Respect reduced-motion preferences. Keep content and controls available without waiting for motion to finish.

## Imagery and source rules

- **Hero.** Prefer an approved photograph of the Flower Mound clinic or its care team. Choose a natural consultation or approachable portrait with an uncluttered composition. Start with a 4:3 or similarly compact crop on desktop and adjust the mobile focal point so faces stay in frame.
- **Clinicians.** Use approved portraits that match the named provider. Start with a 4:5 or square crop. Keep key details and credential text outside the image. A photo of a hearing evaluation is useful only if the visit needs visual explanation beyond the steps.
- **Local proof.** An approved Google Business Profile or clinic photo can show the entrance or recognizable office interior where it helps with directions or trust. Verify the location and usage rights. The map and address are sufficient if there is no useful photo.
- **Lifestyle imagery.** The short symptom section works as text. If an approved lifestyle photo becomes necessary, use a credible everyday setting that supports recognition without implying a result. Keep stock or AI-generated imagery away from provider identity, testimonials, clinic representation, and clinical demonstrations. Use stock or AI only as an illustrative fallback with approval.
- **Image density.** Plan for one dominant hero image and one relevant provider image group. Add a small office image only when it has a job. Use responsive image sizes, real alt text for meaningful images, and reserved dimensions to keep the page stable.

## Visual storytelling system

| Scroll moment | Role and visual emphasis | Mobile adaptation |
| --- | --- | --- |
| Hero | Largest headline, strongest image, and primary booking control. Use the badge to supply immediate proof without overwhelming the message. | Read service, location, visit benefit, and booking before the image. Keep the badge visible with the content or image. |
| Symptom recognition | Quiet text-led moment that puts the experience in everyday terms. | Keep the section compact so the visit steps follow quickly. |
| Visit walkthrough | Clear structural emphasis. Use ordered steps and a distinct booking moment to turn reassurance into action. | Stack the steps and place booking directly beneath the last step. |
| Care options and clinicians | Return to a human image and make the relevant credential easy to find beside TRT. | Keep the named clinician and credential adjacent to the associated content. |
| Reviews | Visually compact proof with a verified summary, readable quotations, and a source link. | Show up to three reviews and keep the total count visible. |
| FAQ | A quiet, narrow reading section with a modest divider rhythm. | Keep tappable headers and maintain the full question text without truncation. |
| Location and close | Warm-tinted booking peak beside practical location details. Use the form as a clearly labeled follow-up option and keep the map useful for directions. | Put the booking recap and action before the map iframe and form. Preserve access to the bottom call bar and account for its height. |

Check a narrow and a wide viewport with a headline-only scan. A visitor should be able to identify the local service, understand how care starts, see why the practice is credible, and find the booking action. Then test the button, dialog, call link, form, and map as separate user actions.

## Inputs

Use the brand fonts, color references, logo variants, booking widget, form embed, map, and links supplied in the brief. Inspect the existing HTML as an implementation reference and verify assets and copy against their sources. [Project sources](https://github.com/RK9207/Family-Hearing-Center---Tinnitus/tree/main) · [Clinic site](https://familyhearingpractice.com/)

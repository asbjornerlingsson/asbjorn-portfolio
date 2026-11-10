# Portfolio to-do

## Mobile fixes

1. **Show players how to move.** They need to know to press the left and right sides of the screen. (Design the hint, then Claude Code decides when it shows.)

## Static version: design notes

0. **Portrait photo for About:** the About section has a "[PORTRAIT PHOTO]" placeholder (4:5). Send a photo and it goes in `img/portrait.webp`.

"Static version" = the non-game version of the site (in the code it's called browse mode).

1. **Phones, top of the page:** before the menu sticks, the four menu buttons wrap onto three rows. The Claude Design file only covers desktop, so this may need a phone design.
2. **"This Portfolio" project:** has one game screenshot and no "How" text yet. Add your own images and text.

## 1939 Games application (still open)

- New case study: a mobile game UI concept (design work, Ásbjörn). Claude can draft the brief: screen list, flow and test plan.
- Flesh out the "This Portfolio" case study (it exists in the static version now, with one screenshot): sprite sheets, Figma frames, mobile controls.
- Reorder the projects: game UI concept, portfolio-as-game, Games & Experiments, Illustrations, Digital Products, Veita.
- Copy: change the hero line to "Game & product UI designer / illustrator" and mention Reykjavík in About.
- Still to decide:
  - Should the unused videos in `vid/` (about 87 MB) be deleted?
  - Should the phone number stay public?

## Done

- Trimmed Illustrations and Odd Jobs galleries, removed Bilingualism, deleted the unused images (Nov 5).
- Text changes from the Nov 4 redesign reviewed and kept.
- Static version: removed "Player 1 · Portfolio", "Selected work", the project count, the About heading, card arrows and the contact lines; new intro line (Nov 6).
- New About text without the Municipality of Reykjavík, in both versions (Nov 6).
- Start screen: role line is now live text, "Digital product designer - Illustrator", matched to the Figma frame (Nov 6).
- Mobile: no more jumping on tap; each half of the screen walks that way (Nov 6).
- Fixed the full-screen image view freezing the portfolio in game mode on touch screens (Nov 6).
- Full-screen view on mobile: image fills the width, arrows moved next to the counter, swipe between images, pinch and double-tap to zoom (Nov 6).
- Mobile: the eye-strain hint's "Got it" button and the About/Work/Contact tabs can be tapped again (Nov 6).
- Mobile: project popups in game mode show all images in a column you scroll through, instead of one image with arrows (Nov 6).
- Static version on phones: project text first, then every image in a column you scroll through (Nov 9).
- Clicking or tapping a sign you're already standing by opens it without teleporting (Nov 9).
- Static version rebuilt from the Claude Design file: new hero, sticky Interfaces & games / Illustration & designs / About / Contact menu with selected state (icons on phones), work split into two sections, new card hover, separate About and Contact, "This Portfolio" card. The game/static switch stays top right and lines up with the sticky menu (Nov 9).
- Static version: no tag pills, no pink, What/How as plain subheadings, project sheet's close button no longer hides behind the phone's address bar (Nov 10).
- Game: player starts near the left edge and says three intro lines on the way to the first sign; the world moved 300px right to make room; long speech bubbles wrap (Nov 10).
- Static version on phones: the sticky menu folds as one smooth two-step animation (shrink to icons in place, then rise into one row with a stretch and squash), and back (Nov 10).
- Game: intro lines are tied to where the player is walking, not a timer; on phones the lifted speech bubble's tail points at the player (Nov 10).
- Static About/Contact rebuilt from the Claude Design file: portrait + "I'm Ásbjörn" text, centred "Get in touch" with email and phone icon buttons; game About dialog uses the same text (Nov 10).
- Game: touch-to-move hint (edge pulse + tapping pixel hand) on touch screens until the first tap; bottom menu in the Arcade select style with the static menu's four sections (icons on phones); intro lines 1–2 before ABOUT with a pause between, line 3 between ABOUT and VEITA (Nov 10).
- Game: more space between bottom-menu buttons; "+XP" shows on the XP bar itself; "LVL 1" under the avatar; reading every sign shows LEVEL UP and goes to LVL 2 (Nov 10).

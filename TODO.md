# Portfolio to-do

## Mobile fixes

1. **Show players how to move.** They need to know to press the left and right sides of the screen. (Design the hint, then Claude Code decides when it shows.)

## Static version: design notes

"Static version" = the non-game version of the site (in the code it's called browse mode).

1. **Header design:** revisit the font sizes and the pink slashes in "UI & product designer / illustrator / game maker".
2. **Category buttons' hover state:** the text becomes unreadable on hover. Fix it.
3. **Merge the category buttons and the section headers.**
   - The buttons (Work / About / Contact) act as the section headers.
   - They stick to the top of the screen while scrolling.
   - The button for the section you're in switches to a selected state.
   - This needs detailed design work first.
4. **Tag pills on project cards:** decide whether to keep them.
5. **About me and contact section:** look at other portfolios for good ways to design it.

## 1939 Games application (still open)

- New case study: a mobile game UI concept (design work, Ásbjörn). Claude can draft the brief: screen list, flow and test plan.
- New case study: "This portfolio is a game", with placeholder images to start.
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

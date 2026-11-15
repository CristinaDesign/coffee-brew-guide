# Coffee brew guide: design notes

This site follows the **Cool Graphs** design system (see `design-system/VERSION.md` for the version and a link to its `DESIGN.md`). Anything not listed here follows Cool Graphs. Where this file differs, this file wins for this site.

## The idea
Pick a coffee type, then follow the steps to make it on our machine, one step at a time. At the end, a celebration page.

## Flow
1. **Card selector:** one card per coffee type (Selectable card style).
2. **Step by step:** one step on screen. You finish it to get the next. It must feel like a **stepper**, with clear progress ("Step 2 of 5") and very clear **Previous** and **Next** buttons.
3. **Celebration page** with a cool animation (switched off when the device asks for reduced motion).

## Page rules
- **The top of the page is one short sentence only.** The longer introduction (units, where the settings come from, what they do not cover) goes **below the cards and steps**. It is still always visible, not hidden in a Disclosure.
- **Units next to every number:** grams (g), millilitres (ml), seconds (s), degrees Celsius (°C), and the grinder setting as a number.
- **Illustrations:** the designer's own (cup, bean, smiling cup). Ask for the files; do not invent artwork.
- **Emojis** are allowed in the text for tone. They are never the only label for something.
- **No pre-infusion step.** The settings are in `data/coffee-settings.csv`.

## Differences from Cool Graphs to decide later
- The stepper (Previous / Next with progress) is new and would become a Cool Graphs component if it works well.
- The celebration page is a one-off pattern.

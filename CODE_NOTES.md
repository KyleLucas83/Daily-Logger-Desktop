# Click Counter Code Notes

These notes follow the code blocks in `src/main.rs` from top to bottom.

1. **Import (`use eframe::egui`)** — Brings the egui UI types into scope; eframe uses egui to draw the app.
2. **Application entry (`main`)** — Sets the initial and minimum window sizes, then starts eframe with a default `MyApp`.
3. **App state (`MyApp`)** — Holds the counter value displayed in the window.
4. **Default state (`Default`)** — Initializes a new app with the counter set to zero.
5. **UI implementation (`eframe::App`)** — Provides the `ui` method that eframe calls to draw each frame.
6. **Main panel** — Fills the window with a dark background and centers its contents.
7. **Heading and subtitle** — Shows the accent tagline, app title, and short supporting message.
8. **Counter card** — Presents the current click total in a padded, rounded panel.
9. **Action buttons** — Shows “Add one” and “Reset” side by side; clicking them increments or clears the counter.

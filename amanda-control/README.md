# Project A.M.A.N.D.A. — Control Center

A playful Halloween console for Amanda and Dr. Seger. All readings and terminal commands are fictional. No backend, accounts, packages, analytics, external fonts, or paid services. Works by opening `index.html` directly, including offline after downloading the files.

## GitHub Pages

1. Create a GitHub repository, such as `amanda-control` (public is the simplest option).
2. Upload `index.html`, `styles.css`, and `app.js` to the repository root and commit them to `main`.
3. In **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**.
4. After deployment finishes, open `https://YOUR-USERNAME.github.io/amanda-control/`. GitHub displays the exact address in Pages settings. Bookmark it on your phone or make a QR code for the lab coat.

If using an existing repository, put all three files together in the folder selected for Pages. Relative asset paths support repository subpaths. No build step is needed.

## Party guide

- Personality buttons rotate through three lines each.
- Relationship diagnostics deliver an affectionate inspection report.
- Terminal: `help`, `scan`, `status`, `compliment`, `snack`, `dance`, `party`, `stop`, `reboot`, `clear`. It only matches preset commands; it never executes code.
- Emergency shutdown escalates through four presses into a three-second cuddle countdown. **Restore normal operations** resets it, including during the countdown.
- Party mode adds a steady purple palette and gentle android movement. **Return to lab**, **Deactivate**, the `stop` command, or Escape ends it. No flashing effects or autoplay music.
- Voice starts off. Enable it with **Voice: off**. Speech availability and voices depend on the browser/device; all lines remain visible. Mute immediately cancels speech. Browser speech services may use network access depending on the device.
- Keyboard controls, visible focus, screen-reader labels and announcements, and reduced-motion preferences are supported. Nothing persists after reload.

Edit the dialogue in `app.js`, the acronym in `index.html`, or colors in `styles.css` to personalize it.

# Web Bonus Examples

Seven single-file demos with HTML / CSS / JavaScript.

They're designed to be **read as much as run**: open any file in a text editor and the
comments are the lesson.

| # | File | What it does | Try this | Skill |
|---|---|---|---|---|
| 1 | `1_aurora_gradient.html` | CSS — animated gradient background + gradient text | Swap the gradient's colors; change `12s` to `4s` | Color stops, animation duration |
| 2 | `2_flip_cards.html` | CSS — 3D card flip on hover + scale/rotate hover effect | `rotateY` → `rotateX`; `scale(1.12)` → `scale(2)` | 3D axes, transforms |
| 3 | `3_neon_form.html` | HTML — native form validation, no JavaScript | Remove `required`; tighten the `pattern` regex | Validation attributes, regex |
| 4 | `4_password_meter.html` | JS — live strength meter, keystroke by keystroke | Award a bonus point for 16+ characters, cap the bar at 100% | Conditionals, arithmetic, DOM |
| 5 | `5_color_mixer.html` | JS — JS writing values into CSS variables | Add a random-color button | `Math.random`, listeners |
| 6 | `6_reaction_game.html` | JS — `setTimeout` + `Date.now()`, a small state machine | Random 1–4s delay instead of a fixed 2s | `Math.random`, `setTimeout` |
| 7 | `7_particle_canvas.html` | JS — canvas + `requestAnimationFrame` particle system | Stronger trails; add gravity to particles | Animation loop, physics |


## Running them

- No install, no server, no accounts. Open the file in any browser.
- Everything is offline-safe: no fonts, images, or libraries are fetched.
- Each file is small enough to project on screen and scroll through live — around
  70–100 lines including comments.
- **Demo 3 note:** the form posts to `action="#"`, so submitting a valid form just
  reloads the page with a query string. Nothing is transmitted anywhere, by design.

## License

Classroom use, fork & remix freely. No external assets.

# CSS Laundry Services – Hero Image Animation (Task 3)

A laundry services landing page whose hero image has a custom CSS animation.

## Animation

- **Orbit rotation** – the image travels around a small circular path
  (`rotate → translateX → counter-rotate`) so it moves in an orbit but stays upright.
- **Squeeze effect** – at certain keyframes the image is squashed wide and
  stretched tall using `scale(x, y)`, like a washing machine pressing and releasing.
- Both animations run on separate wrapper elements (`.orbit` and `.squeeze`)
  so they combine without fighting over the same `transform`.
- `prefers-reduced-motion` is respected.

## Files

- `index.html` – page structure
- `style.css` – styling and keyframe animations
- `hero.svg` – hero illustration (swap in your own image by editing the `<img src>`)

## Run

Open `index.html` in a browser (or use the VS Code Live Server extension).

## Live link

Add your deployed link here.

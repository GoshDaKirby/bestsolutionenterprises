# assets/images/

Place your background images here:

| File      | Used on          | Description                                      |
|-----------|------------------|--------------------------------------------------|
| bg.gif    | Home page only   | Animated background — fills the full hero section |
| bg.png    | All inner pages  | Static freeze-frame of the same image — shown as a ~220px banner strip between the navbar and page hero, cropped to the center of the image |
| shaju.jpg | About Us         | Team photo (replace placeholder)                 |
| asha.jpg  | About Us         | Team photo (replace placeholder)                 |
| joshua.jpg| About Us         | Team photo (replace placeholder)                 |

## Notes
- Both `bg.gif` and `bg.png` should be the same dimensions.
- The home page (`index.html`) uses `bg.gif` at full size with a dark overlay for readability.
- Inner pages (`about`, `services`, `cdi`, `contact`, `links`) show a 100px tall strip of `bg.png` cropped to the top portion of the image.
- The banner strip fades from navy (top) to the light page background (bottom) via a CSS gradient overlay.

# CSS

## Defensive CSS [Tips](https://defensivecss.dev/articles/intro-defensive-css/tips)
1. Flexbox wrapping. Don't forget to add `flex-warp: wrap`

## Fonts

**font-display** property defines how font files are loaded and displayed by the browser allowing text to appear with a fallback font while a font loads or fails.
This improves performance by making the text visible instead of having a blank screen, with a trade-off being a flash of unstyled text.

@font-face {
  font-family: "nunito", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-display: fallback;
}

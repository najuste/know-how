# General Rules

[Rules](https://anthonyhobday.com/sideprojects/saferules/) from Anthony Hobday:
- Don’t use pure black or white, only near-black and near-white
- Saturate your neutralsUse high contrast for important elements
- Everything in your design should be deliberate
- Optical alignment is often better than mathematical alignment
- Lower letter spacing and line height with larger text. Raise them with smaller text
- Container borders should contrast with both the container and the background
- Everything should be aligned with something else
- Colours in a palette should have distinct brightness values
- If you saturate your neutrals you should use warm or cool colours, not both
- Measurements should be mathematically related
- Elements should go in order of visual weight
- Use a 12 column grid
- Spacing should go between points of high contrast
- Closer elements should be lighter
- Make drop shadow blur values double their distance values
- Put simple on complex or complex on simple
- Keep container colours within brightness limits
- Make outer padding the same or more than inner padding
- Keep body text at 16px or above
- Use a line length around 70 characters
- Make horizontal padding twice the vertical padding in buttons
- Use two typefaces at most

# CSS specific

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

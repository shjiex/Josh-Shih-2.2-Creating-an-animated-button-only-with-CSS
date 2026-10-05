# 2.2: Creating an animated button only with CSS

## What to do

Use this as the starter code to add CSS rules that will create the interaction shown below:

<img width="372" height="252" alt="2 1-screencast" src="https://github.com/user-attachments/assets/f8256b3d-adc5-4469-b932-5081c2a0c717" />


### Requirements

- When a user hovers on the first button, the color of the background and the text of the button should interchange, and the button should grow in size by 20%.
- When the button is clicked (which you can't really see from the screencast/animation above), the button should turn upside down.
- At the end of the HTML file, you should include a relatively short HTML comment (max 3–4 sentences) indicating if and how you used AI help for this homework. If you used AI, you should describe:
  - Which portions were AI-generated (e.g., "I used Copilot to generate an initial ruleset for the button element")
  - The prompts you used to generate this code (e.g., "Write a CSS ruleset that makes a button element grow by 20% in size.")
  - Any modifications you made to the AI output (e.g., "The ruleset did not have rules for changing the colors - I added that")

  If you did not use AI help, just write that you did not use AI help in the comment.

### Constraints

- The second button (the one without the smiley) should not exhibit the interactive behavior.
- You need to do this with only CSS. No JavaScript allowed.

### Hints

- Use [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) to specify the updated styles of the button. The two pseudo-classes that you need are [`:hover`](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:hover) and [`:active`](https://developer.mozilla.org/en-US/docs/Web/CSS/:active).
- To make the element grow in size, you can use the [`scale`](https://developer.mozilla.org/en-US/docs/Web/CSS/scale) CSS property, and to make the element turn upside down, use the [`rotate`](https://developer.mozilla.org/en-US/docs/Web/CSS/rotate) property.
- To adhere to the constraint of the second button not exhibiting any of these behaviors, make sure that your CSS rulesets have the appropriate, specific selector.

## How to submit

1. Make sure that all of your work is self-contained in a single file (e.g., you should not rely on an external CSS file) and there is a comment describing AI help (as instructed earlier).
2. Upload the HTML file to Canvas.

---

*Acknowledgement: This assignment is based on material used in a previous version of HCDE 438 by Dr. Brock Craft, Evan Feenstra, and Hannah Twigg-Smith.*

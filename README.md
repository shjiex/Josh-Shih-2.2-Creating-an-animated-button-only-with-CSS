# 2.2: Creating an animated button only with CSS

## What to do

Use this as the starter code to add CSS rules that will create the interaction shown below:

<img width="372" height="252" alt="2 1-screencast" src="https://github.com/user-attachments/assets/f8256b3d-adc5-4469-b932-5081c2a0c717" />


### Requirements

- When a user hovers on the first button, the color of the background and the text of the button should interchange, and the button should grow in size by 20%.
- When the button is clicked (which you can't really see from the screencast/animation above), the button should turn upside down.

### Constraints

- The second button (the one without the smiley) should not exhibit the interactive behavior.
- You need to do this with only CSS. No JavaScript allowed.

### Hints

- Use [pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) to specify the updated styles of the button. The two pseudo-classes that you need are [`:hover`](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:hover) and [`:active`](https://developer.mozilla.org/en-US/docs/Web/CSS/:active).
- To make the element grow in size, you can use the [`scale`](https://developer.mozilla.org/en-US/docs/Web/CSS/scale) CSS property, and to make the element turn upside down, use the [`rotate`](https://developer.mozilla.org/en-US/docs/Web/CSS/rotate) property.
- To adhere to the constraint of the second button not exhibiting any of these behaviors, make sure that your CSS rulesets have the appropriate, specific selector.

## How to submit

1. Make sure that all of your work is self-contained in a single file (e.g., you should not rely on an external CSS file) and there is a comment describing AI help (as instructed earlier).
2. Submit the GitHub repo url to Canvas and give accounts ShenzhiW, donghoon-io access to your repository.

---

*Acknowledgement: This assignment is based on material used in a previous version of HCDE 438 by Dr. Brock Craft, Evan Feenstra, and Hannah Twigg-Smith.*

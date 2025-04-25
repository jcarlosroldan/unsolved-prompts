Write an `<svg>` tag that can be directly pasted into HTML for a color picker resembling the one in Paint Tool SAI. Use a square viewport of exactly `100x100`. It should contain only the following elements:

* A circle with an outer diameter of 100 and an inner diameter of 90 for selecting hues. The circle must display a continuous, clockwise hue gradient starting and ending at the top (0° and 360°), with hue values increasing clockwise. Thus, the top is `hsl(0deg 100% 50%)`, the bottom is `hsl(180deg 100% 50%)`, and it returns to the top.
* An equilateral triangle centered precisely within the circle, with corners exactly 95 units from the center. Colors of corners:
  - Top: `hsl(0deg 100% 50%)` (pure hue)
  - Bottom-left: `hsl(0deg 0% 0%)` (black)
  - Bottom-right: `hsl(0deg 0% 100%)` (white)
* Every internal triangle color must be smoothly interpolated via gradients between these corners, without explicitly placing individual intermediate points.
* Ensure absolute minimalism and succinctness, removing everything nonessential. Do not include any functionality beyond the visual figure itself.
* Iterate as needed toward perfection, critically reviewing each attempt.

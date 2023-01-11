# Breaking the flow
[![Status overview badge](../../blob/badges/.github/badges/main/badge.svg)](#-results)


**Instructions**

1. In `index.html` create an empty box with the class `.helloworld`. The box should have a width and height of 200px. Inside the box, add the text "Hello World" and change the background color to orange.

2. Center the `.helloworld` box horizontally. **Hint**: For centering elements in HTML try using the `margin` property.

3. Move the `.helloworld` box 5 pixels to the left and 7 pixels down from the center position.

4. Add another square box with the class `.box1`. The box should have a width and height of 200px and a red background color. Position the box at the bottom-left of the screen.

5. Add another square box with the class `.box2`. The box should have the background color `rgb(0, 255, 85)` and a height and width of 200px. This box should be positioned at the bottom-left of the screen, but should be 10px higher and 10px more to the right than `.box1`.

6. Add a third box with the class `.box3`. It should have the background color `rgb(0, 183, 255)`. It should be positioned at the bottom-left of the window, but should be 10px higher and 10px further right than `.box2`. 
![reference-image](/images/reference-image1.png)

7. Place `.box3` **behind** `.box2`.
![reference-image](/images/reference-image2.png)

[//]: # (autograding info start)
# <img src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" alt="" data-canonical-src="https://github.com/DCI-EdTech/autograding-setup/raw/main/assets/bot-large.svg" height="31" /> Results
> ⌛ Give it a minute. As long as you see the orange dot ![processing](https://raw.githubusercontent.com/DCI-EdTech/autograding-setup/main/assets/processing.svg) on top, CodeBuddy is still processing. Refresh this page to see it's current status.
>
> This is what CodeBuddy found when running your code. It is to show you what you have achieved and to give you hints on how to complete the exercise.


### Hello World Box

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status0.svg) | Page contains element with class `.helloworld` |
| ![Status](../../blob/badges/.github/badges/main/status1.svg) | `.helloworld` box has width & height of 200px and contains the text 'hello world' |
| ![Status](../../blob/badges/.github/badges/main/status2.svg) | `.helloworld` box has a background color |
| ![Status](../../blob/badges/.github/badges/main/status3.svg) | `.helloworld` box is centered horizontally |
| ![Status](../../blob/badges/.github/badges/main/status4.svg) | `.helloworld` box is positioned '7px' from top and '-5px' from left |

### Box 1

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status5.svg) | `.box1` is present on page |
| ![Status](../../blob/badges/.github/badges/main/status6.svg) | `.box1` has width & height of '200px' |
| ![Status](../../blob/badges/.github/badges/main/status7.svg) | `.box1` has 'red' background color |
| ![Status](../../blob/badges/.github/badges/main/status8.svg) | `.box1` is positioned at the bottom left using CSS `bottom` Property |

### Box 2

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status9.svg) | `.box2` is present on page |
| ![Status](../../blob/badges/.github/badges/main/status10.svg) | `.box2` has width & height of '200px' |
| ![Status](../../blob/badges/.github/badges/main/status11.svg) | `.box2` has background color 'rgb(0, 255, 85)' |
| ![Status](../../blob/badges/.github/badges/main/status12.svg) | `.box2` is postioned at the bottom left and is 10px higher / 10px to the left of `.box1` |

### Box 3

|                 Status                  | Check                                                                                    |
| :-------------------------------------: | :--------------------------------------------------------------------------------------- |
| ![Status](../../blob/badges/.github/badges/main/status13.svg) | `.box3` is present on page |
| ![Status](../../blob/badges/.github/badges/main/status14.svg) | `.box3` has width & height of '200px' |
| ![Status](../../blob/badges/.github/badges/main/status15.svg) | `.box3` has background color 'rgb(0, 183, 255)' |
| ![Status](../../blob/badges/.github/badges/main/status16.svg) | `.box3` is positioned to the bottom left and is 10px higher / 10px to the left of `.box2` |
| ![Status](../../blob/badges/.github/badges/main/status17.svg) | `.box3` is placed behind `.box2` using CSS `z-index` property |



[🔬 Results Details](../../actions)
[🐞 Tips on Debugging](https://github.com/DCI-EdTech/autograding-setup/wiki/How-to-work-with-CodeBuddy)
[📢 Report Problem](https://docs.google.com/forms/d/e/1FAIpQLSfS8wPh6bCMTLF2wmjiE5_UhPiOEnubEwwPLN_M8zTCjx5qbg/viewform?usp=pp_url&entry.652569746=UIB_layout_break_out_the_flow)


[//]: # (autograding info end)
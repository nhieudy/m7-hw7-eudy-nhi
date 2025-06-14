# Assignment 7: Use CSS Positioning, Pseudo-Elements, and Pseudo-Classes to Create Tooltips

(**NOTE:** View a rendered version of this file in VS Code with `ctrl-shift-v` or `cmd-shift-v`)

&nbsp;
![Final site example](example.gif)

&nbsp;
## Background

This assignment is designed to familiarize you with using CSS positioning, pseudo-classes, and pseudo-elements to create advanced interactive features for your websites.

**NOTE**: A proper tooltip for production websites would require special accessibility considerations as well as a healthy amount of JavaScript; it is not feasible to make an accessible and fully-featured tooltip implementation with HTML and CSS alone. This assignment is meant to be an exercise for students to practice specific CSS skills, not a test of production web components, so do not fret over making your tooltips production-ready. If you are interested in learning how to make a proper tooltip, or why a pure HTML/CSS tooltip is insufficient, see [Sarah Higley's blog post](https://sarahmhigley.com/writing/tooltips-in-wcag-21/).

&nbsp;
## Setup

Create a git repository titled `m7-hw7-lastname-firstname` and clone the repo to your computer. Copy the **contents** of the `unsolved` folder into your repository. Ensure the `index.html` file is in the **root** of your repository so that it deploys to GitHub pages properly.

&nbsp;
## Instructions

Use the provided code in the `unsolved` folder to implement a sticky banner, a drop cap, and tooltips on the webpage. In order to receive full-credit for this assignment, you must:

1. Use `position: sticky` to make the `section.hero` element stick to the top of the page when scrolling down. Refer to the gif at the top of the page.
1. Create a drop cap for the first letter of the first `p` tag in the `article` element.
    * A drop cap is an enlarged first letter of the first word in a text. Usually seen at the start of a chapter in a book. ![drop cap example](dropcap.png)
1. Finish the tooltip code in the CSS file so that when hovering over or focusing the red text causes the text within the inner span tag to appear above as a word bubble. Again, refer to the gif at the top of these instructions for a visual example.
1. Deploy the finished site to GitHub pages.

&nbsp;
## Deployment

Your code must be deployed to GitHub Pages. To deploy a repository to GitHub pages you must:

1. Ensure your repository has an `index.html` file in the root directory.
1. Navigate to the `settings` section of the repository.
1. Click on `pages` in the left navigation menu.
1. Under `source` click the dropdown and select your `master` or `main` branch.
1. Click `save`.

Your site should be deployed to `<your github username>.github.io/<your repository name>` in 5-10 minutes.

&nbsp;
## Submission

Please submit both a link to your repository and a link to the live site. Also please include any comments on stumbling blocks or difficulties encountered while completing the assignment.

&nbsp;
## Resources

* [CSS Positioning on W3 Schools](https://www.w3schools.com/css/css_positioning.asp)
* [CSS Pseudo-classes on W3 Schools](https://www.w3schools.com/css/css_pseudo_classes.asp)
* [CSS Pseudo-elements on W3 Schools](https://www.w3schools.com/css/css_pseudo_elements.asp)
* [CSS Tooltip Tutorial on W3 Schools](https://www.w3schools.com/css/css_tooltip.asp)
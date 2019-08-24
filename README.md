# Bootstrap-Portfolio
This is a portfolio made using bootstrapcss
https://xanderrrrrr.github.io/Respnosive-Portfolio/

for me: 

### Instructions

1. Create two new GitHub repositories and name them `Bootstrap-Portfolio` and `Responsive-Portfolio`.

2. Clone these repositories to your computer.

### Assignment One Instructions (Bootstrap)

1. Inside your `Bootstrap-Portfolio` repo, create `index.html`, `portfolio.html` and `contact.html`.

2. Using Bootstrap, recreate your portfolio site with the following items:

   * A navbar

   * A responsive layout (remember the grid, rows and columns are your friends)

     * eg. On an `xs` screen, content should take up the entire screen. On `sm` and larger screens, you should have some margins on the left and right side of the screen. Check out various sites on your mobile device versus your computer to see this in action!

   * Responsive images

   **BONUS**
   Using Bootstrap, make a sticky footer and use sub-rows and sub-columns on your portfolio site _(Hint: Check out the Bootstrap documentation)_

3. Your Bootstrap solution should minimize use of media queries.

4. Deploy your new Bootstrap-powered portfolio to GitHub Pages.

### Assignment Two Instructions - (No Bootstrap)

1. Copy the contents of `Basic-Portfolio` (your first homework solution) and paste the mentioned files into `Responsive-Portfolio`.

2. Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the `Basic-Portfolio` repo.

3. If you chose the `Wireframe` exercise for your first homework assignment, talk to a TA, who will provide you with a template for your portfolio.

4. Inside your `Responsive-Portfolio` folder, find your `styles.css` file. You will write your media queries at the bottom of `styles.css`.

5. Use three `@media screen` tags, each with one of these `max-width`s: `980px`, `768px` and `640px`.

   * You use `980px` because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

   * `768px` is about the width of a tablet and `640px` is about the width of a phone in landscape.

6. Make the layout match the following screenshots:

   * `index.html`: [980px](Images/980-index.jpg), [768px](Images/768-index.jpg), [640px](Images/640-index.jpg)

   * `portfolio.html`: [980px](Images/980-portfolio.jpg), [768px](Images/768-portfolio.jpg), [640px](Images/640-portfolio.jpg)

   * `contact.html`: [980px](Images/980-contact.jpg), [768px](Images/768-contact.jpg), [640px](Images/640-contact.jpg)

7. Make the position of the header `static` (the default positioning) when the screen is `640px` wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

8. Be sure to include the `viewport` tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. _(Hint: You won't need to use exact pixels for anything other than the container)_

9. **Protip**: Use the Chrome extensions [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh) and [Browser Width](https://chrome.google.com/webstore/detail/browser-width/mlnegepkjlccabakompdmbcmdieaideh) to see the browser dimensions in Chrome.

10. Deploy your new portfolio (now with media queries!) to GitHub Pages.

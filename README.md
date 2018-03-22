# HTML & CSS Drills
These tasks are designed to familiarize yourself with HTML 5 elements and their default behavior.

## HTML Tasks
1. Use the Emmet abbreviation in VS Code to create an `index.html` page, and then open that file in your browser.
2. Inside the `<body>` of your page, use all six heading elements with a paragraph element after each one. The text used in the heading and paragraphs are up to you.
3. Add a comment before each heading to give yourself a reminder what the purpose of that section should be.
4. Add an image after each paragraph in your page.
5. "Wrap" each section (heading, paragraph, and image) with a `<section>` tag. The open section tag should precede the first heading tag, and the closing section tag should be after the image tag. *Remember to indent properly!* (Tip: if your indentation ever gets out of whack, just right click anywhere in VS Code and click "Format Document"!)
6. In between every paragraph and image, create an unordered list with at least three list items. Again, the content contained in this list is up to you!
7. Create a form with three inputs: first name, last name, and email address. Make sure each input is labeled, and that all of them are wrapped with form tags.
8. Add a button to the form using an input tag.
9. Wrap the entire page in a `<div>`.
10. Reformat the document. How does it change compared to what you had originally written?
11. Add a horizontal line between each section in your document.
12. Add hyperlinks to each image that opens the image in a new tab.
13. At the top of your page, create a table with the following columns (headers): Month, Day, Year.
14. Then, add a row for each day that you worked on these tasks.
15. In the last heading element (h6) add either a copyright or trademark HTML symbol entity to the end of the text content.

## CSS Tasks
1. Create a new CSS file, and link it to your `index.html` file.
2. Define three new rulesets: one for `*`, one for `body`, and one for `@media (max-width: 700px)`. Inside of the `@media` ruleset, duplicate the `*` and `body` rulesets.
3. For `*`, change the font-family to `Helvetica` and define the font-size as `1em`. For `body`, remove all margin and padding. For the duplicates inside of `@media`, make the font-size `1.2em` and the padding (on all sides) as `1em`.
4. Give each image in your HTML the same class. Define that class and set the height to `300px`. Also, give each picture a border-radius and drop-shadow. Tinker with those two properties until you are satisfied with the appearance.
5. Next, create a pseudo-class for your image class you created in Step 4. When you hover over the image, it should increase its height by 10% and the drop-shadow should also become more pronounced.
6. Center the images horizontally across the page.
7. With only one ruleset, apply the same color to _all_ of your headings, and adjust the margin-top property for these headings to 1.5em.
8. Give each `<section>` a class, and in the ruleset for that class define a light gray background-color, border, border-radius, and border-color. Also, give each section a padding of `1em`.
9. Use the font-style property to italicize every unordered list. Now, make the second list item in every unordered list bold and a unique color.
10. Give the outermost "wrapping" `div` a class "container". Give it a width of 90%, and a margin of `0 auto`.

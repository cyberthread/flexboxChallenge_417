# Flexbox Challenge: New Yorker Remake
Copywork, or trying to remake an existing design can help you to improve both design and coding skills. I encourage you to use your developer tools to take a look at the original and break down their code. Although you can use a combination of Grid and Flexbox in this exercise, you can do each of the layout requirements using just flexbox. Remember that, when possible, you put layout rules on the parent item (the only thing that might go on a child item is something like width in this exercise). For the purposes of this exercise we will focus on implementing one breakpoint (i.e. default mobile design with one media query). No HTML needs to be modified.

*This exercise requires you to remake just the article header module, and not the whole page. */

In this exercise you will:
- Use developer tools to explore existing code in order to replicate it.
- Implement the design using all relative units.
- Practice breaking layouts down into smaller component pieces that each need their own layouts.
- Nest flexbox layouts into other flexbox layouts.
- Implement a layout that changes depending on viewport width.
- Take notes on accessibility issues you find in the existing article header design.

## Tasks
### Preview
- First take a look at an [example article on the New Yorker magazine website](https://www.newyorker.com/tech/annals-of-technology/how-beeple-crashed-the-art-world). Change the browser window size to see how the header of the article changes across screen sizes (note we are focused on the article and not the header of the page which contains the site identifier and navigation). Explore the code with your developer tools.
- Next take a look at the prototypes in the screenshots folder to better understand the default (narrow) design and the first breakpoint design (medium or the first media query).

### Recreate the article header for one breakpoint
- Start with the typography.
  - Implement default typographic styles. Note that it is acceptable to use the New Yorker's backup font-stack rather than their professional fonts for the purpose of this exercise. Remember that the defaults should align with the actual paragraph text of the article.
  - Use more specific selectors sparingly. Only add rules to those selectors that are necessary to override the defaults.
 - Break design into independent modules. This layout is complex it has 3 different modules that need to be implemented using flexbox. I recommend working from the outside in (i.e. top to bottom in the list that follows). Read through all three before getting started.
  - The general one column design that shifts to a two equal column design. The default/mobile layout is already implemented.
  - The "description" or text-based content also has a general layout. It is restricted in width (already implemented) but should be centered vertically and horizontally.
  - The social media icons should be in an equally spaced horizontal row on all screen sizes.

### Show your work
- On Blackboard submit your styles.css file and screenshots demonstrating that you have valid code.
- In class show your instructor or TA your completed work in a browser and in Visual Studio code. Also be prepared to show that your code is valid.

# Code-refactoring

Actively using semantic HTML, and reducing overall code to increase efficiency of the rendered website. This activity also improves the media accessibility user requirements.

You can view the deployed website by [clicking here!](https://fudge88.github.io/code-refactoring/)

![Preview](assets/video/preview.gif)

## Summary

**Refactoring** existing code (improving it without changing what it does). this code is for a marketing agency who wanted to refactor an existing site to make it more accessible. The **Scout Rule** was also adhered to as I left the code a little cleaner than when I found it.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Tools Used

- VSCode
- GitBash
- GitHub

#### Languages

- HTML
- CSS

## What and How

#### CSS

Browsers generally read code from top to bottom, CSS optimization supports the website to load faster. From a business point of view this is important because:

- Most people are not ready to wait for web page opening for more than 3 seconds
- Visitors are more likely to come back to websites that load quicker
- Fast websites are ranked better in Google and other search engines

The original code for this website consisted of repetitive CSS code, i consolidated most into one short line of code, which was applied to several elements, thus reducing the need for the browser to render repetitive code. I deleted unused CSS, and added a single CSS property to existing code to remove a singular class. I also Organized the code into hierarchical branches ensuring minimal duplication.

#### HTML

A semantic element clearly describes its meaning to both the browser and the developer. I changed the original code to embrace semantic elements, in effect giving the code a more meaningful structure.

![Semantic-HTML](assets/images/semantic-html.png)

Examples of non-semantic elements: `<div>` and `<span>` - these are in effect blocks but they are not descriptive and tell nothing about its content.

Examples of semantic elements: `<form>`, `<nav>`, and `<article>` - Clearly define their content opposed to being blocks.

## Interesting Finds

I found that using semantic HTML gave more meaning to the content. However, i did run in to slight difficulty using the `<figcaption>` tag.

![Figcaption Error](assets/images/figcaption.PNG)

I found that the caption didn't sit under the image as i would have expected it to, and required th use of CSS to correct the format.
I chose to target the parent element in this case being the `<figure>` tag, and assigned it with the following CSS attributes `display: flex; flex-flow: column;` to achieve the desired format.

## References

[SpaceCDN](https://www.spacecdn.com/blog/content-delivery-network/how-to-optimize-css-for-faster-websites/)

[Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet)

[W3Schools](https://www.w3schools.com/html/html5_semantic_elements.asp)

[JungleDisk](https://www.jungledisk.com/blog/content/images/blog/div-soup-vs-semantic-html.png)

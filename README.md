# Code-refactoring

Actively using semantic HTML, and reducing overall code to increase efficiency of the rendered website. This activity also improves the media accessibility user requirements.

You can view the deployed website by [clicking here!](https://www.example.com)

![Preview](assets/video/preview.gif)

## The challenge

**Refactoring** existing code (improving it without changing what it does). this code is for a marketing agency who wanted to refactor an existing site to make it more accessible. The **Scout Rule** was also adhered to as I left the code a little cleaner than when you found it.

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

## Interesting Finds

I found that using semantic HTML gave more meaning to the content. However, i did run in to slight difficulty using the `<figcaption>` tag.

![Figcaption Error](assets/images/figcaption.PNG)

I found that the caption didn't sit under the image as i would have expected it to, and required th use of CSS to correct the format.
I chose to target the parent element in this case being the `<figure>` tag, and assigned it with the following CSS attributes `display: flex; flex-flow: column;` to achieve the desired format.

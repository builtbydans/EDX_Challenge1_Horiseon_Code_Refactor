# EDX FE Bootcamp Challenge One: Horiseon SEO Agency Code Refactor

## The Task

The task for the first module (HTML, CSS & Git) was to review the Horiseon website and ensure it kept with
current accessibility standards. In order to do this, a through review of the HTML and CSS was required. However,
the client did not request any visual changes to the website itself so this was purely a refactoring of the current
codebase.

A screenshot of the website provided by the client can be found here: [Horiseon Landing Page](https://github.com/builtbydans/EDX_Horiseon_Code_Refactor/blob/main/assets/01-html-css-git-challenge-demo.png).

## User Story

For this task, the user story was as below:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criterias

All acceptance criterias and challenge requirements can be found in the [Challenge README](https://github.com/builtbydans/EDX_Horiseon_Code_Refactor/blob/main/starter/Challenge_README.md).

## Revisions

### HTML
The HTML was revised to include a standardised HTML DOCTYPE, which included all relevant meta tags. All div tags were
reviewed to ensure they followed a semantic HTML pattern. This included replacing divs for header, nav, section, article tags and more.
Small changes were also made to aid accessibility and SEO such as changing the <title> to reflect the Horiseon website and also adding appropriate
alt attributes where necessary. All revisions can be found as comments in the HTML.

### CSS
As some classes were removed for semantic HTML elements, these were then reflected in the CSS. The CSS file itself was also re-organised and labelled to follow
a sequential pattern based on the waterfall of the landing page, to aid other readers to understand what section(s) they need to refer to.
Much of the CSS was repeated so to ensure the file remained DRY, classes were concatenated for ease-of-reference and to group elements semantically.

For comparison, you can view the starter [HTML](https://github.com/builtbydans/EDX_Horiseon_Code_Refactor/blob/main/starter/starter.html) file
and the starter [CSS](https://github.com/builtbydans/EDX_Horiseon_Code_Refactor/blob/main/starter/assets/css/style.css) file.

## Live Website

The deployed version on GitHub Pages can be found here: [Horiseon SEO Code Refactor Live](https://builtbydans.github.io/EDX_Horiseon_Code_Refactor)

## Further Refactoring

In order to improve accessibility, Lighthouse and performance for this website, one consideration is to reduce the file size for the images as these are
very large. The waterfall analysis in the Network tab suggests that the largest image at 14.3MB is taking on average 3.14s to load.

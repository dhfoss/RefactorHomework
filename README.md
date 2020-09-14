# RefactorHomework
Homework Completed. The following changed I made to the website are listed here:

Changed <title> to “Horiseon”
Changed <div class=“header”> to <header>
Changed <div class=“content”> to <main>
Changed <div class=“footer”> to <footer>
Changed h2 contained in footer to “h4” to distinguish from other h2’s
Changed class=“float-left” and “float-right” to “photo-left” and “photo-right” to combine CSS declarations.
Changed <div class=navigation> to <nav>
Fixed hyperlink in nav bar.
Changed <span class=seo> to <span>
Added alt id’s to images
Added class=“small=photo” to <img>’s in the main section to distinguish from the <img>’s in the aside for styling purposes.
Changed <div class=“search-engine-optimization> to <article>
Changed <div class=“online-reputation-management> to <article>
Changed <div class=“social-media-marketing> to <article>
Condensed the CSS of the divs above to <article>
Removed closing </img> tag after the final image to remain consistent with other <img> elements.
Changed <div class=“benefit-lead”>, <div class=“benefit brand”>, and <div class=“benefit-cost”> to <section>
Condensed the CSS of the divs above to a single declaration of section.
Cut out the extra declarations of h3
Cut out multiple instances of article margin-bottom: 20px
Cut out multiple instances of styling h2
Changed <div class=benefits> to <aside>
Changed <div class=benefit
Added min-width to <header> so links would not collapse into each other

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

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
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

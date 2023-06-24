# UOB Bootcamp Challenge Assignment 1

## Description

Submission for Module 1 of the University of Birmingham Skills Bootcamp in Front-End Web Development &amp; UX

This assignment took a starter code package in commit [1e2fe91](https://github.com/0xCryptoStefan/uob-module-01-challenge/commit/1e2fe9133293ea3371d588dd2e41bbb530bbb084) and developed it to meet the defined acceptance criteria to improve the accessibility of the website.

The production website is deployed [here](https://0xcryptostefan.github.io/uob-module-01-challenge/).

![Screenshot of deployed webpage](./0xcryptostefan.github.io_uob-module-01-challenge_.jpg)

## Requirements

This assignment addresses the following User Story:

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

This has been developed to meet the following Acceptance Criteria:

| Acceptance Criteria                                                             | Solution                                                                                                                          |
| ------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| Semantic HTML elements can be found throughout the source code                  | Use of semantic elements (`<header>`, `<nav>`, `<main>`, `<aside>`, `<section>`, `<footer>`) to replace generic `<div>` elements. |
| HTML elements follow a logical structure independent of styling and positioning | HTML elements have been updated to use semantic elements and styling elements have been separated into consolidated CSS classes.  |
| Image and icon elements contain accessible `alt` attributes                     | Added `alt` attributes to all images and icons.                                                                                   |
| Heading attributes fall in sequential order                                     | Heading elements are in sequential order. Footer heading changed to h4 to reduce priority in document flow.                       |
| Title elements contain a concise, descriptive title                             | Page title updated to reflect an accurate description of the page.                                                                |

## Learning Outcome

This module made me consider the fundamentals of HTML and CSS again, and to consider accessibility from the outset of building any website or application.

I also reminded myself how to construct tables in markdown notation.

## Resources Used

In completing this challenge exercise, I made use of the following resources:

- [W3Schools: HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [Semantics in HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html)
- [W3C Markup Validator Service](https://validator.w3.org/)

## Mark Scheme Compliance

### Technical Acceptance Criteria

| Item                                                                                                    | Evidence                                                                                                                |
| ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| Application's links all function correctly.                                                             | Defective link fixed by adding ID attribute to associated intended linked element.                                      |
| Application's CSS selectors and properties are consolidated and organized to follow semantic structure. | CSS selectors consolidated beneath semantic elements and refactored to narrow scope of selectors within those elements. |
| Application's CSS file is properly commented.                                                           | Comments added to separate different parts of the page                                                                  |

### Deployment

| Item                                              | Evidence                                                                                |
| ------------------------------------------------- | --------------------------------------------------------------------------------------- |
| Application deployed at live URL.                 | Live application deployed at: https://0xcryptostefan.github.io/uob-module-01-challenge/ |
| Application loads with no errors.                 | No visual defects <br /> No console errors                                              |
| Application GitHub URL submitted.                 | URL submitted                                                                           |
| GitHub repository that contains application code. | This repository contains all code.                                                      |

### Application Quality

| Item                                                                                     | Evidence                                                                           |
| ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Application resembles (at least 90%) screenshots provided in the challenge instructions. | Application resembles the model screenshot provided in the assignment instructions |

### Repository Quality

| Item                                                                                                    | Evidence                                                                                                                                                                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Repository has a unique name.                                                                           | Unique name used                                                                                                                                                                                                                                                                               |
| Repository follows best practices for file structure and naming conventions.                            | Limited files but standard HTML and CSS file names used                                                                                                                                                                                                                                        |
| Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.  | All multi-word CSS IDs and classes use lowercase and hyphens. <br /> Indentation within code follows best practice and document flow <br /> Comments have been included within the CSS. Comments were used during development within the HTML file but have been removed following completion. |
| Repository contains multiple descriptive commit messages.                                               | Multiple commits included demonstrating incremental build of final submission. Each has a clear description of changes made.                                                                                                                                                                   |
| Repository contains quality README file with description, screenshot, and link to deployed application. | This README document.                                                                                                                                                                                                                                                                          |

## License

Released under the MIT license. Full details in [LICENSE](./LICENSE).

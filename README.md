![CF](https://i.imgur.com/7v5ASc8.png) Lab 04: Templates
=======
[Code of Conduct](https://github.com/codefellows/code-of-conduct)

## Submission Instructions
When you are finished with lab, follow these steps to submit your work. Create one Pull Request (aka: "PR") from your Forked repo to the CF repo with your changes, and you'll each submit that same PR link in Canvas.

1. Ensure that all your local changes are committed, and pushed to your origin repo.
1. Visit the origin repo on github.com, and ensure that all of your completed work has been merged to master via Pull Requests within your repo.
1. Create a new PR from your Fork to the CF repo and ensure the branches look correct.
1. Fill in the template based on the text box prompts:
  1. Write a good descriptive summary of your changes:
    1. Be sure to include how much time you spent on it, and who you worked with.
    1. Briefly reflect on and summarize your process.
1. When you create the PR, it will have a unique URL. Copy this link, share with your partner, and paste it into the assignment submission form in Canvas. Both the driver and the navigator will submit the same PR link.
---

## Learning Objectives
<!-- the learning objectives from the corresponding class number -->
* Identify different approaches to reusable HTML templates
* Effectively use templates to present user-entered (or server-provided) data (methods on the Handlebars object)
* Distinguish between the different Handlebars expression types (`{{}}` vs `{{{}}}`)
* Modify and style typographic components (serif, san-serif fonts, font-size, font-family, color, font-weight, etc)
* Understand the application and use of string literals, interpolation, and introduction to ES2015 syntax

---

## Resources  
<!-- a list of links if any are necessary for the assignment-->
[Handlebars Docs](http://handlebarsjs.com/)
[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

---

## Feature Tasks  
<!-- a list or description of the feature tasks you want the students to implement -->
1. Include the Handlebars.js file in your project.
1. Convert your existing template html code into a Handlebars style template.
1. Update your article `.toHtml()` method to use Handlebars
1. You may find it useful to attach some additional properties to your article object, before you hand it off to the template.
1. Ensure the proper use of template literals, when applicable. *No more string concatenation!*

### Stretch Goals
1. Look at all that duplicated markup in your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it with.

---

## Rubric  
<!-- a list of grading requirements with associated points, scaling to 10pts possible -->
Criteria | Pts
---|---
Meets all Assignment Reqs | 6
Uses idiomatic code style | 3
Follows proper Git workflow | 1
**Total** | **10**

<!-- links -->

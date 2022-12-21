---
layout: page
title: README
nav_exclude: true
---

## How to deploy the changes:
- Make a commit with changes to content and push to the repositories main branch
- A build will automatically be triggered
- If the push is being made to a auxillary branch, when the branch gets merged to master, a new build will be triggered.

## How to add a new staffer:
- Duplicate an existing file in /_staffers
- Add an image in /assets/images folder 
- Use the name of the image in the /_staffers/TA<>.md file
- Make sure to fill the "officehour" and "officehourlink" properties in the TA<>.md file
- After the above steps, you can validate that the new staffer is visible in "Staff" and "Communication" pages.

## Editing content:
- For editing any content on a page, please find the corresponding .md file for the page
- Edits to content can be done easily by changing the corresponding .md file
- Note that for any theme related changes please refer [link](https://just-the-docs.github.io/just-the-docs/docs/customization/#color-schemes)
- After any edits please follow the instructions in "How to deploy the changes:" section
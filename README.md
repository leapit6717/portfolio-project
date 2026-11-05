# Leah Pittman's Portfolio

This personal portfolio introduces me, lists my skills, displays
projects, and includes an interactive contact form.

## Languages and Libraries

- HTML provides the page structure.
- CSS styles the layout, modal, tooltip, and dark mode.
- JavaScript handles interactions, project objects, and browser storage.
- No external libraries or frameworks are required.

## Features

- Welcome modal with a Close button.
- Dark mode preference saved in localStorage.
- Skills displayed using an array and loop.
- Three project objects containing titles, summaries, image URLs,
  and repository links.
- Project data converted with JSON.stringify() and saved in sessionStorage.
- Existing session data retrieved using JSON.parse().
- Project cards created dynamically using DOM methods.
- Featured content controlled by the number of projects.
- Submit button tooltip.
- Contact form confirmation displayed after three seconds.

## Files

- index.html contains the HTML, CSS, and JavaScript.
- README.md documents the portfolio.

## Dependencies

A modern browser with JavaScript enabled is required.
Browser storage must be allowed for storage features to persist.
No installation, Node.js, or separate image files are required.

## How to Run

1. Download the repository.
2. Open index.html in a modern browser, or view the GitHub Pages site.
3. Close the welcome modal and explore the page.
4. Test dark mode and the contact form.

Live website:
https://leapit6717.github.io/portfolio-project/

## Storage Behavior

localStorage remembers the dark mode preference between visits.
sessionStorage retains project data across refreshes within the same tab.

After changing the default project objects in the code, clear the
portfolioProjectsV1 sessionStorage entry or open the site in a fresh
browser session to load the updated defaults.

## Notes

Project repository links currently contain placeholders and should
be replaced with actual project URLs. The ECPI link should be updated
to the specific program homepage.

The contact form demonstrates a timed confirmation and does not
send email.

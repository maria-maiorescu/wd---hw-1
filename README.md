# Junior Developer Project Showcase

Mini-project for the Web Design course at UVT, 2026.

## About

This is my first web project, built as part of the Web Design course in my first year at UVT. The idea was to make something that actually reflects what I've been working on — so I went with a project showcase site, since most of my time lately has been spent writing C and C++ programs.

The site has four pages. The home page introduces the showcase and lists my main projects. The about page goes into a bit more detail about each one. The data page has a table summarizing all the projects — their type, technology, main feature, and status. The contact page has a simple form for sending feedback or questions.

## Structure

All four pages use the same external stylesheet (`styles.css`) and share the same layout: a header with my name and tagline, a navigation bar, the main content area, and a footer. Each page has exactly one `h1` and the headings go in order from there. I also added a skip link on every page for keyboard navigation.

The form on the contact page groups all the fields inside a `fieldset` with a `legend`, and every input has a visible label attached to it. The table on the data page has a caption and uses `th` with `scope="col"` for the header row.

The CSS covers typography, spacing, navigation styling, table formatting, and form controls. I tried to keep it consistent across all pages with a light colour palette.

## Notes

The contact form is static and doesn't actually send anything — there's no backend. That's a known limitation for now.

## Links

- Repository: https://github.com/maria-maiorescu/wd---hw-1
- Live site: https://maria-maiorescu.github.io/wd---hw-1/

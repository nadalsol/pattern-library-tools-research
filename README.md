# Pattern Library Tools Research

* Autor: [@nadalsol](https://twitter.com/nadalsol).
* Date: January, 2018.

## Table Of Contents

1. [Features](#features)
2. [Tools](#tools)
3. [Opened questions](#opened-questions)

## Features

* **Code friendly:** view, copy and paste the HTML and SCSS source code, for each component.
* **Skin friendly:** ability to switch between different project skins (CBO, MBO...), without leaving the pattern library.
* **Agile:** avoid slowing down our work, when adding/maintaining components in the pattern library.
* **Agnostic:** not dependant of specific technologies (when possible).
* **Documentable:** ability to add specs and usage. For instance, in specs we could explain why are why using some attributes (like aria-hidden, for accessibility reasons), and so on.
* **Navigable:** a navigation menu, to move across all pattern library components.
* **Context friendly:** ability to put and visualise different components together, in a specific context (template or page).

## Tools

Ordered by preference:

### Fractal

* https://fractal.build/
* https://fractal.build/guide/
* Demo: http://bits.24ways.org/

| Code fr. | Skin fr. | Agile | Agnostic | Documentable | Navigable | Context fr. |
| -------- | -------- | ----- | -------- | ------------ | --------- |-------------|
| 👍       | -        | 👍    | 👍        | 👍           | 👍         | 👍          |

**Good:**

* Flexible: complete freedom to use whichever templating language, build tool
and organisational model best suits your project. Very flexible project
structure and organisation.
* Integrated: integrate by including it as a dependency in your build.
* Data-driven: Component preview data can be hardcoded or dynamically generated.
* Theme API: Create your own web UI themes from scratch or by customising the
default theme.
* CLI: Can be run from the command line or integrated into your project.
* Components: Simple, Compound, Hidden, Variants, Statuses...
* Preview layouts: Templates that wrap your components to allow them to be
rendered in the context of ‘proper’ HTML page.
* Full code snippets: HTML, Handlebears, CSS, SCSS, JS...
* Exporting to static HTML.

**Bad:**

* Nothing.

### Astrum

* http://astrum.nodividestudio.com/
* https://github.com/NoDivide/astrum

| Code fr. | Skin fr. | Agile | Agnostic | Documentable | Navigable | Context fr. |
| -------- | -------- | ----- | -------- | ------------ | --------- |-------------|
| 👍       | -        | 👍    | 👍        | 👍           | 👍         | 👍          |

**Good:**

* Features almost everything we need.
* Components organised into groups.
* Customisable.
* Beautiful UI design.
* Theming supported.
* Full browser support.
* Usable sidebar navigation menu.
* Active [development roadmap](https://github.com/NoDivide/astrum/projects/2).

**Bad:**

* No template engine available yet (coming soon...).
* Only HTML code snippets.

### Storybook

* https://storybook.js.org/
* https://storybook.js.org/examples/

| Code fr. | Skin fr. | Agile | Agnostic | Documentable | Navigable | Context fr. |
| -------- | -------- | ----- | -------- | ------------ | --------- |-------------|
| -        | -        | 👍    | -        | 👍           | -         | -           |

**Good**

* Powerful, and fully customisable.

**Bad**

* Focused on React, Vue or Angular projects.
* You can't see HTML code snippets.

### Pattern Lab

* http://patternlab.io/docs/
* https://github.com/Comcast/patternlab-edition-node-webpack

| Code fr. | Skin fr. | Agile | Agnostic | Documentable | Navigable | Context fr. |
| -------- | -------- | ----- | -------- | ------------ | --------- |-------------|
| 👍       | -        | 👍    | 👍        | 👍           | -         | 👍           |

**Good:**

* Features almost everything we need.
* Focused on Atomic Design.
* Pseudo-patterns (ability to quickly build multiple unique variants of an
  existing pattern).
* Set up pattern-specific data.
* Customisable.
* Template engine available (Mustache or Twig).
* Mustache and HTML code snippets.

**Bad:**

* Poor UI design.
* Top navigation menu is not usable (should be toggled all the time).

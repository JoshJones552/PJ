# The Missing Trophy

The Missing Trophy is a small HTML/CSS campus mystery. A club trophy disappears before an event. The player compares statements and clues, writes a theory if desired, and reveals what happened.

## What the project needed

The Mystery Files topic needed connected pages for the introduction, case board, suspects, and evidence. The Investigation Pack needed clue filtering and a reveal flow. The project also needed shared CSS, Flexbox and Grid, responsive layouts, motion, keyboard support, and development evidence.

The final website has those four game pages and a fifth About page. The scope stays small so the same story can connect every feature.

## How the main parts fit together

The HTML files hold the story, links, labels, and input controls. Every page loads styles.css. That file matches classes and IDs in the HTML to layout and interaction rules.

For example, the evidence page gives a radio input the ID messages and gives a clue the category message. CSS checks which input is selected and hides unrelated clue cards. The Case Board uses a different connection a link points to #solution, and the target rule displays the section with that ID.

## Why these choices fit

One stylesheet keeps the pages consistent. Flexbox fits navigation links that need to wrap. Grid fits repeated boxes that need equal columns. Radio inputs and URL fragments provide simple interaction within the HTML/CSS only scope.

Blue and orange are the two box colors. Arial and a light background keep the clues readable. The guess field is a native textarea because the player needs space for a short explanation, not a scored answer.

## Project development steps

1. The story established the missing trophy, three suspects, three clues, and a solution.
2. The content was divided into five pages with shared navigation.
3. The shared stylesheet connected the page structure to the design and responsive layouts.
4. Input states and link targets connected the evidence filters and ending reveal.
5. Keyboard focus, labels, short animations, and reduced motion rules supported use of the pages.
6. Browser checks covered the main interactions and screen widths. A long text test led to a wrapping fix.

## Where the evidence is

`website/` contains the five HTML pages, styles.css, and the website README.
`documentation/code-guide.md` explains specific lines and their connections.
`documentation/project-plan.md` explains the story, scope, and design choices.
`documentation/testing.md` explains the checks, results, and long text fix.
`documentation/development-journal.md` records the assisted final implementation work.
`documentation/kanban.html` groups current project tasks by status.
`presentation/` contains the slides and project explanations in the speaker notes.
`submission-links.txt` contains fields for the real project URLs.

The local game runs by opening `website/index.html` in a browser. No installation or build step is needed. AI assistance used for planning, code, revisions, checks, and presentation writing is described in the website README.

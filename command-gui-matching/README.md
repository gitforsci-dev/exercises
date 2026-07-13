# Match the Git command to the GUI action

A live matching activity: learners pair each Git command with the equivalent
point-and-click action in the RStudio Git pane or on GitHub. The point is that
in a GUI-first workshop, clicking a button runs the same command a terminal
user types.

## Files

| File | Audience | Notes |
| --- | --- | --- |
| `command-gui-matching.qmd` / `.pdf` | Learners | One-page handout. Draw lines from commands to GUI actions. |
| `command-gui-matching-answer-key.qmd` / `.pdf` | Facilitator only | Correct pairings and talking points. Do not hand out. |

## Running it

1. Print the learner sheet (`command-gui-matching.pdf`), one per learner.
2. 3 minutes on your own, then 3 minutes with your neighbour to compare and
   agree.
3. Review as a group using the answer key.

## Rendering

Rendered with Quarto's Typst engine (no LaTeX needed):

```
quarto render command-gui-matching.qmd
quarto render command-gui-matching-answer-key.qmd
```

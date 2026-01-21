- what is the hypothesis?
- study design
  - instruction prompts
  - gap
- screenshots
- high-level architecture
  - which plugins?
- flowchart

### Assignment motives
- learn to interpret a study from hypothesis/methods
- learn to read a flowchart
- does not exceed original "Tutorial Sheet 1" in technical demands

## Hypothesis

Humans will be quicker to identify animate objects than inanimate objects.

## Methods

Display images of either real animals or stuffed animals, ask for a (time-limited) keyboard response indicating (a)nimate, (i)nanimate.
- include the user input instructions with each image
- separate the images with short post-trial gaps

For now, we'll just collect and display two data points:
1. correct/incorrect?
2. response time

You'll have to use your imagination to assume that we go on to measure the results in a meaningful way.

## JSPsych implementation

A `timeline` with:
  - `jsPsychHtmlKeyboardResponse`: welcome/instructions
  - two `jsPsychImageKeyboardResponse` trials: one grizzly bear, and one teddy bear.

Here is a simple flowchart of the experiment program.
[placeholder]

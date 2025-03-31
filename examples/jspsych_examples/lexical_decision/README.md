# Lexical Decision Task

This is a simple lexical decision task implemented using jsPsych. In this experiment, participants are presented with words and nonwords one at a time and must decide whether each item is a real English word or not.

## Features

- 20 real words and 20 nonwords
- Randomized presentation order
- Response collection using F/J keys
- Response time and accuracy measurement
- Results display at the end of the experiment

## How to Run

1. Open `lexical_decision.html` in a web browser
2. Click "Begin" on the welcome screen
3. Read the instructions and click "Start"
4. For each trial:
   - A fixation cross (+) will appear for 1 second
   - A word or nonword will appear
   - Press F for real words
   - Press J for nonwords
5. At the end, click "View Results" to see your performance

## Stimuli

The experiment includes:
- 20 common English words (e.g., "house", "book", "tree")
- 20 pronounceable nonwords (e.g., "blark", "tremp", "flink")

## Data Collection

The experiment collects:
- Response time for each trial
- Accuracy (correct/incorrect responses)
- Stimulus type (word/nonword)
- Correct response for each trial

## Customization

To modify the experiment:
1. Edit the stimuli lists in the JavaScript section of `lexical_decision.html`
2. Adjust timing parameters (e.g., fixation duration)
3. Modify the instructions or welcome screen text
4. Add additional data collection variables 
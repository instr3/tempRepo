## misc
- the question order on SurveyMonkey is the same as in anonymization_lookup.json
  - except that the prompt is at the top of each page

## todo
- 统计时长
- after getting all the files,
  - update the time estimated to complete the survey on page 1
  - update intermission

## draft playground
Task: Drum to Others

In this task, the model is given a drum track and generates the remaining instruments to complete the song. It also receives the first 1–2 bars of the full song as a prompt. Below is the complete input provided to the model:

...

For clarity, the drum track is louder than the other instruments. All demos are synthesized with a basic sound engine and no fine-tuned dynamics. Please focus on the musical content, not the mixing quality.

Metrics:
- **Musicality**: Does it sound good as music?
- **Adherence**: Does it respect and accurately follow the input conditions?
- **Creativity**: Given the input conditions, is it creative in its musical decisions?

Task: Others to Drum

In this task, the model is given a complete song without its drum track and generates the missing drum part. No drum prompt is provided. Below is the complete input provided to the model:

...

For clarity, the drum track is louder than the other instruments. All demos are synthesized with a basic sound engine and no fine-tuned dynamics. Please focus on the musical content, not the mixing quality.

Metrics:
- **Musicality**: Does it sound good as music?
- **Adherence**: Does it respect and accurately follow the input conditions?
- **Creativity**: Given the input conditions, is it creative in its musical decisions?

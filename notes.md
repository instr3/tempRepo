## misc
- the question order on SurveyMonkey is the same as in anonymization_lookup.json
  - except that the prompt is at the top of each page

## todo
- 统计时长
- after getting all the files,
  - update the time estimated to complete the survey on page 1
  - update intermission

## draft playground
### Jingwei's welcome message
Welcome to our survey!
This survey takes 15-20 minutes. You will listen to 6 groups of music generation samples. The order of arrangements within a group is randomized. Please compare each sample and evaluate their music quality. Your feedback is very important to us. Enjoy the music!


NOTE: To ensure the best auditory experience and that all details can be heard, please wear headphones while completing the questionnaire.

All the best,
SMCLab, NUS
Music X Lab, NYU Shanghai & MBZUAI

### our welcome message
Welcome to our survey!
You will be listening to and evaluating generated music clips. The survey takes approximately 15-20 minutes to complete.
Your feedback is important to us. Enjoy the music!


All the best,
Music X Lab, MBZUAI

### Task instructions
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

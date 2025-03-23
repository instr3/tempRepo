## misc
- the question order on SurveyMonkey is the same as in anonymization_lookup.json
  - except that the prompt is at the top of each page

## todo
- 统计时长
- after getting all the files,
  - update the time estimated to complete the survey on page 1
  - update intermission

## draft playground
### our welcome message
Welcome to our survey!

This survey features a subjective study of several score (symbolic music) generation model. This survey takes 15-20 minutes. You will listen to 6 groups of music generation samples. Each group will feature one of the following tasks:

(1) Chord-conditioned melody generation (chord to melody)
(2) Drum-conditioned song generation (drum to others)
(3) Song-conditioned drum track generation (others to drum)

The order of arrangements within a group is randomized. Please compare each sample and evaluate their music quality. Your feedback is very important to us. Enjoy the music!

NOTE: To ensure the best auditory experience and that all details can be heard, please wear headphones while completing the questionnaire.

All the best,
SMCLab, NUS
Music X Lab, NYU Shanghai & MBZUAI

### Transition page

Thanks for your answers. The next section will be:

(1) Chord-conditioned melody generation (chord to melody)
(2) Drum-conditioned song generation (drum to others)
(3) Song-conditioned drum track generation (others to drum)

### Task instructions

Task: Chord to Melody

In this task, the model is given a chord track and generates the melody. It also receives the first 1-2 bars of the melody as a prompt. Below is the complete input provided to the model:

Task: Drum to Others

In this task, the model is given a drum track and generates the remaining instruments to complete the song. It also receives the first 1–2 bars of the full song as a prompt. Below is the complete input provided to the model:

...

For clarity, the drum track is louder than the other instruments. All demos are synthesized with a basic sound engine and no fine-tuned dynamics. Please focus on the musical content, not the mixing quality.

Metrics:
- **Musicality**: Does it sound good as music?
- **Adherence**: Does it respect and follow the input condition's music structure?
- **Creativity**: Given the input conditions, is it creative in its musical decisions?

Task: Others to Drum

In this task, the model is given a complete song without its drum track and generates the missing drum part. No drum prompt is provided. Below is the complete input provided to the model:

...

For clarity, the drum track is louder than the other instruments. All demos are synthesized with a basic sound engine and no fine-tuned dynamics. Please focus on the musical content, not the mixing quality.

### Additional page

Thank you for completing the survey! If you are interested, there are two additional survey questions regarding the task:

Drum-conditioned song generation (drum to others)

Do you want to listen to 2 additional samples and provide some feedbacks?

### Final page

Thank you for completing the additional part of the survey!

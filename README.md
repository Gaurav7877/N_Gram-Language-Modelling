# N_Gram-Language-Modelling

In this project, I have utilized the N_Gram Language Modelling technique to perform sentence generation in both forward and reverse direction.
To achive this goal:
- I first cleaned the text corpus using regular expressions, tagging each sentence with start and end tokens.
- Next, I crafted functions to generate and populate nested dictionaries serving as the Bi-gram, Tri-gram, and Four-gram probabilities for the subsequent word.
- Afterwards, I fed an initial string into the language modeling process, obtaining results for each of the models.
- For the reverse generation, I reversed the text corpus and repeated the previous processes to creat new libararies.
- I also added functionality to generate both ways which utilizes multiple dictionaries.

## The result as follows:

<img width="659" alt="Forward_Gen" src="https://github.com/Gaurav7877/N_Gram-Language-Modelling/assets/101136531/24b23095-8899-45b6-9c3d-cf8d6032fc04">

<img width="651" alt="Reverse_Gen" src="https://github.com/Gaurav7877/N_Gram-Language-Modelling/assets/101136531/5c8fb586-f4e5-42b1-b94c-c4701129880e">

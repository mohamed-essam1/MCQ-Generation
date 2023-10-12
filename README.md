# MCQ-Generation

This project aims to automatically generate multiple-choice questions (MCQs) using two different processes: the first process involves question generation, question answering, and distractor generation using specific models, while the second process utilizes Large Language Models (LLaMA v1) for MCQ generation.

## First Process

The first process consists of four steps to generate MCQs:

1. **Question Generation using flan_T5 model**: This step involves utilizing the flan_T5 model, which is a transformer-based model trained specifically for question generation tasks. It takes a given passage or context as input and generates relevant questions based on the content.

2. **Question Answering using distilbert model**: Once the questions are generated, the distilbert model comes into play. This model is used for question answering, which means it takes the generated questions and tries to find the most appropriate answer within the given passage or context.

3. **Distractor Generation using T5 model**: After obtaining the correct answer from the previous step, the T5 model is used for distractor generation. Distractors are the incorrect options provided in multiple-choice questions. The T5 model generates plausible distractors to accompany the correct answer.

4. **Integrate all to Generate MCQ**: In the final step, all the components are integrated to generate the complete MCQ. The question generated in step 1, along with the correct answer from step 2 and the distractors generated in step 3, are combined to form a comprehensive multiple-choice question.

## Second Process

The second process utilizes the Large Language Models (LLaMA v1) for MCQ generation. LLaMA v1 refers to a set of powerful language models that have been trained on vast amounts of text data. These models have the ability to understand context, generate text, and answer questions.

In this process, the LLaMA v1 model is used to directly generate MCQs without the need for separate question generation, question answering, and distractor generation steps. The model is capable of comprehending a given passage or context and generating MCQs with options, including the correct answer and plausible distractors.

## Conclusion

The MCQ-Generation project employs two different processes to automatically generate multiple-choice questions. The first process involves question generation, question answering, and distractor generation using specific models, while the second process utilizes Large Language Models (LLaMA v1) for MCQ generation. These processes provide efficient and automated ways to generate MCQs, saving time and effort for educators, content creators, and anyone in need of generating large volumes of multiple-choice questions.

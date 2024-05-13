## Prompting

The Six Components of a good Prompt

1. **Persona**: The role or character that the student is expected to assume when responding to the prompt
2. **Context**: The situation or setting in which the prompt is given. Include, Background information, What success looks like, Environment
3. **Task**: The specific activity or question that the prompt is asking the student to perform or answer.
4. **Example**: An example of a correct response to the prompt.
5. **Format**: The way in which the prompt is presented to the student.
6. **Tone**: The attitude or emotion that the prompt conveys.

## Ai for Learning

- Study
- Improve critical thinking
- Grasp & explain concepts
- Example complex code
- Generate study study documents (notes, flashcards, etc...)
- Generate questions (multiple choice, coding ...)
- etc...

## AI for professional career

- Improve existing code
- Simplify code
- Write Test Cases
- Make code more efficient
- Debug your code
- etc...

## Study Plan

### Main Concepts

- Aysnc IO Concept in Python
- asyncio library
- random.uniform

### Objectives

- `async` and `await` syntax
- How to execute an `async` program with `asyncio`
- How to run concurrent coroutines
- How to create asyncio tasks
- How to use the random module

## Prompting - ChatGPT, Llama2, Gemini

- Go over the resoruces
  NB:

  - note the diff between `time.time()` and `time.pref_counter()`
  - note key asyncio methods : `asyncio.gather`, `asyncio.run`, `asyncio.create_task`, `asyncio.wait`, `asyncio.sleep`, `asyncio.wait_for`,
    `asyncio.as_completed`
  - note -> rules of async io

- Go over the objectives
- Go over the excercise
- Create your prompt

  ```txt
  You are an experienced Python developer and a great teacher with years of experience. I am currently studying the following concepts in Python.

  - Aysnc IO Concept in Python
  - asyncio library
  - random.uniform
  - `async` and `await` syntax
  - How to execute an `async` program with `asyncio`
  - How to run concurrent coroutines
  - How to create asyncio tasks
  - How to use the random module
  - `time.time()` and `time.pref_counter()`
  - asyncio methods : `asyncio.gather`, `asyncio.run`, `asyncio.create_task`, `asyncio.wait`, `asyncio.sleep`, `asyncio.wait_for`,
    `asyncio.as_completed`

  Create an outline that can help me grasp the above concepts as a beginner. I will use this outline to further generate notes. Consider Python version 3.7. For all your outputs use markdown.
  ```

- Go over and generate notes for each section
- Go over the exercises

  - use the following prompt as a guide

  ```txt - PROMPT 1
  I am given this task and how should I go about solving it. I don't want the answer but a guide towards the answer.

  Question:
  Write an asynchronous coroutine that takes in an integer argument (max_delay, with a default value of 10) named wait_random that waits for a random delay between 0 and max_delay (included and float value) seconds and eventually returns it.

  Use the random module.
  ```

  ```txt - FOLLOW UP PROMPT
  can you give me a check list to follow?
  ```

- Creating Study Flash Cards

  ```
  Create Flash Cards for the core concepts in the following format wait for my answer and proceed

  **Term / topic / idea **

  short description
  ```

- Creating a Quiz

  ```
  Now it time to test my knowledge. Create a quiz with multiple choice questions that cover the concepts we covered. put the answers at the end.
  ```

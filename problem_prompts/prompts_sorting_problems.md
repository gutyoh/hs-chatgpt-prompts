# Prompts for Sorting steps problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
>You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in creating sorting steps problems in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language that are challenging and engaging for learners.

---

### Generating Sorting steps problem with zero-shot prompting
```
Create a sorting steps problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic, focusing particularly on the ["ENTER SPECIFIC CONCEPT OR TECHNIQUE HERE"] in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. The objective is to create a medium-difficulty sorting steps problem.
3. The problem MUST HAVE 4-6 steps or concepts that need to be arranged in a CORRECT LOGICAL sequence.
    - 4.1 When generating the problem question and steps YOU MUST consider that the user ONLY HAS BASIC KNOWLEDGE of: ["ENTER TOPIC PREREQUISITES HERE"]
4. Ensure that each step or concept description:
   - 4.1 Provides enough detail for comprehension while remaining concise.
   - 4.2 Is distinct, avoiding overlapping or vague descriptions.
   - 4.3 Is presented in a logical order that clearly illustrates the process or concept of the specified topic.
5. The output MUST BE text and have the following format:
   - 5.1 An engaging, DIRECT, and CLEAR problem question/description.
   - 5.2 Present each step or concept as a separate bullet point, using clear labeling or numbering to facilitate understanding of the sequence.
   - 5.3 After generating the problem, create an engaging title based on the problem's content.
   - 5.4 The title MUST BE LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Sorting Steps [/TITLE] and put the title FIRST in the output.
   - 5.5 The title MUST reflect the content of the problem without using generic terms.
6. Ensure you use simple words for the problem question/description and steps. AVOID advanced vocabulary or formal expressions.

7. The problem MUST BE theory-oriented BUT in case it includes code snippets:
   - 7.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
   - 7.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
   - 7.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

8. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: TODO

---

### Generating Sorting steps problem with few-shot prompting — based on specific topic section
```
Create a sorting steps problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic, focusing particularly on the ["ENTER SPECIFIC CONCEPT OR TECHNIQUE HERE"] in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium difficulty Matching problem using as reference the above theory.

3. The problem MUST HAVE 4-6 steps or concepts that need to be arranged in a CORRECT LOGICAL sequence.
    - 4.1 When generating the problem question and steps YOU MUST consider that the user ONLY HAS BASIC KNOWLEDGE of: ["ENTER TOPIC PREREQUISITES HERE"]
4. Ensure that each step or concept description:
   - 4.1 Provides enough detail for comprehension while remaining concise.
   - 4.2 Is distinct, avoiding overlapping or vague descriptions.
   - 4.3 Is presented in a logical order that clearly illustrates the process or concept of the specified topic.
5. The output MUST BE text and have the following format:
   - 5.1 An engaging, DIRECT, and CLEAR problem question/description.
   - 5.2 Present each step or concept as a separate bullet point, using clear labeling or numbering to facilitate understanding of the sequence.
   - 5.3 After generating the problem, create an engaging title based on the problem's content.
   - 5.4 The title MUST BE LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Sorting Steps [/TITLE] and put the title FIRST in the output.
   - 5.5 The title MUST reflect the content of the problem without using generic terms.
6. Ensure you use simple words for the problem question/description and steps. AVOID advanced vocabulary or formal expressions.

7. The problem MUST BE theory-oriented BUT in case it includes code snippets:
   - 7.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
   - 7.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
   - 7.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

8. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: TODO

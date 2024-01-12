# Prompts for Sorting steps problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in creating sorting steps problems in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language that are challenging and engaging for learners.

---

### Generating Sorting steps problem with zero-shot prompting
```
Create a sorting steps problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. The objective is to create a medium-difficulty sorting steps problem.
3. The problem MUST HAVE 4-6 steps or concepts that must be arranged in a CORRECT LOGICAL sequence.
4. YOU MUST ALWAYS output the steps in the EXPECTED CORRECT LOGICAL order WITHOUT SHUFFLING or altering the sequence!

5. Ensure that each step or concept description:
   - 5.1 Provides enough detail for comprehension while remaining SHORT and CONCISE.
   - 5.2 Is distinct, avoiding overlapping or vague descriptions.
   - 5.3 Is presented in a logical order that clearly illustrates the process or concept of the specified topic.
   - 5.4 YOU MUST NOT include steps like "Decide/Understand ...", "Determine/Evaluate ...", "Check if the file exists", or similar.

6. The output MUST BE text and have the following format:
   - 6.1 An engaging, DIRECT, and CLEAR problem question/description.
   - 6.2 Present each step or concept as a separate bullet point, using clear labeling or numbering to facilitate understanding of the sequence.
   - 6.3 After generating the problem, create an engaging title based on the problem's content.
   - 6.4 The title MUST BE LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
   - 6.5 The title MUST reflect the content of the problem without using generic terms.

7. The problem MUST BE theory-oriented BUT in case it includes code snippets:
   - 7.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
   - 7.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
   - 7.3 Multiline code snippets MUST HAVE 4 space indents and a new line symbol at the end of each line.

8. YOU MUST use simple words for the problem question/description and steps. AVOID advanced vocabulary or formal expressions.

9. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/PXnvx/title-establishing-a-python-socket-connection-and-sending-a-message-title

---

### Generating Sorting steps problem with few-shot prompting — based on specific topic section
```
Create a sorting steps problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium-difficulty sorting steps problem using as reference the above theory.

3. The problem MUST HAVE 4-6 steps or concepts that must be arranged in a CORRECT LOGICAL sequence.
4. YOU MUST ALWAYS output the steps in the EXPECTED CORRECT LOGICAL order WITHOUT SHUFFLING or altering the sequence!

5. Ensure that each step or concept description:
   - 5.1 Provides enough detail for comprehension while remaining SHORT and CONCISE.
   - 5.2 Is distinct, avoiding overlapping or vague descriptions.
   - 5.3 Is presented in a logical order that clearly illustrates the process or concept of the specified topic.
   - 5.4 YOU MUST NOT include steps like "Decide/Understand ...", "Determine/Evaluate ...", "Check if the file exists", or similar.

6. The output MUST BE text and have the following format:
   - 6.1 An engaging, DIRECT, and CLEAR problem question/description.
   - 6.2 Present each step or concept as a separate bullet point, using clear labeling or numbering to facilitate understanding of the sequence.
   - 6.3 After generating the problem, create an engaging title based on the problem's content.
   - 6.4 The title MUST BE LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
   - 6.5 The title MUST reflect the content of the problem without using generic terms.

7. The problem MUST BE theory-oriented BUT in case it includes code snippets:
   - 7.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
   - 7.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
   - 7.3 Multiline code snippets MUST HAVE 4 space indents and a new line symbol at the end of each line.

8. YOU MUST use simple words for the problem question/description and steps. AVOID advanced vocabulary or formal expressions.

9. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/SXfN6

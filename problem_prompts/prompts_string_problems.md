# Prompts for String (Text) problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
>You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in creating string problems with regexp solutions in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language that are challenging and engaging for learners.

---

### Generate String problem with zero-shot prompting
```
Create a string problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. The objective is to create a medium-difficulty string problem.

3. The problem's string solution MUST BE a single keyword, method, or very short text, NEVER multiple lines of code.
 - 3.1 DO NOT create long or complex regex patterns for the solution.
 
4. The problem's question MUST BE direct, clear, and unambiguous.
 - 4.1 DO NOT include the answer in the question!

5. The output MUST BE text and have the following format:
 - 5.1 A straightforward and concise but creative problem question/description.
 - 5.2 A single new line with the solution regex pattern in the following format 'Solution: ...' that:
    - Starts and ends with `\s*`.
    - Uses `\s*` around operators and blank spaces to account for different formatting styles.
    - If the solution is a function name, the REGEX PATTERN MUST MATCH the function name WITH and WITHOUT parentheses (e.g., `\s*print\s*(\(\))?\s*`).
    - For Java, JavaScript and C++ code the semicolon `;` at the end of the REGEX PATTERN MUST BE OPTIONAL. (e.g. `\s*int\s*counter\s*=\s*0\s*;?\s*`)
    - Matches both single (`'`) and double (`"`) quotes if they're part of the expected answer.
 - 5.3 Another single new line with the "plaintext solution" in the following format:  'Plain Text: ...'
 - 5.4 After generating the problem, create an engaging title based on the problem's description.
 - 5.5 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.

6. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 6.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 6.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 6.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.
 
7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
8. The output MUST only include the above information; DO NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/juHHh/title-python-file-reading-method-comprehension-title

---

### Generate String problem with few-shot prompting — based on specific topic section
```
Create a string problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium difficulty string problem using as reference the above theory.

3. The problem's string solution MUST BE a single keyword, method, or very short text, NEVER multiple lines of code.
 - 3.1 DO NOT create long or complex regex patterns for the solution.
 
4. The problem's question MUST BE direct, clear, and unambiguous.
 - 4.1 DO NOT include the answer in the question!
 
5. The output MUST BE text and have the following format:
 - 5.1 A concise but creative problem question/description.
 - 5.2 A single new line with the solution regex pattern in the following format 'Solution: ...' that:
    - Starts and ends with `\s*`.
    - Uses `\s*` around operators and blank spaces to account for different formatting styles.
    - If the solution is a function name, the REGEX PATTERN MUST MATCH the function name WITH and WITHOUT parentheses (e.g., `\s*print\s*(\(\))?\s*`).
    - For Java, JavaScript and C++ code the semicolon `;` at the end of the REGEX PATTERN MUST BE OPTIONAL. (e.g. `\s*int\s*counter\s*=\s*0\s*;?\s*`)
    - Matches both single (`'`) and double (`"`) quotes if they're part of the expected answer.
 - 5.3 Another single new line with the "plaintext solution" in the following format:  'Plain Text: ...'
 - 5.4 After generating the problem, create an engaging title based on the problem's description.
 - 5.5 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.

6. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 6.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 6.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 6.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
8. The output MUST only include the above information; DO NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/YnZot

# Prompts for Multiple Choice Question (MCQ) problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

### Generate MCQ problem with zero-shot prompting
```
Create a multiple-choice question (MCQ) problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. The objective is to create a medium-difficulty MCQ problem.
3. The problem MUST HAVE 4-5 concise and NOT very lengthy options.
4. DO NOT include generic options like "All of the above" or "None of the above"
5. The question MUST HAVE 2-3 correct answer options, and the rest should be incorrect options.

6. The output MUST BE text and have the following format:
 - 6.1 A concise but creative problem question/description.
 - 6.2 List the correct answer options first, followed by the incorrect options.
 - 6.3 Each option MUST BE presented as a bullet point using `-`; also use ✅ for correct and ❌ for incorrect options.
 - 6.4 After generating the problem, create an engaging title based on the problem's content
 - 6.5 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 
7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.

8. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 8.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 8.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 8.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

9. The output MUST only include the above information; DO NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/FD3TL/python-for-loop:-truth-or-bluff

---

### Generate MCQ problem with few-shot prompting — based on specific topic section
```
Create a multiple-choice question (MCQ) problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
 
2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium difficulty MCQ problem using as reference the above theory.
 
3. The problem MUST HAVE 4-5 concise and NOT very lengthy options.
4. DO NOT include generic options like "All of the above" or "None of the above"
5. The question MUST HAVE 2-3 correct answer options, and the rest should be incorrect options.
 
6. The output MUST BE text and have the following format:
 - 6.1 A concise but creative problem question/description.
 - 6.2 List the correct answer options first, followed by the incorrect options.
 - 6.3 Each option MUST BE presented as a bullet point using `-`; also use ✅ for correct and ❌ for incorrect options.
 - 6.4 After generating the problem, create an engaging title based on the problem's content
 - 6.5 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 
7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.

8. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 8.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 8.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 8.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

9. The output MUST only include the above information; DO NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/_bJX8 

---

### Generate feedback for incorrect options in (MCQ) problems
```
Given the following comprehension problem:

["ENTER FULL MCQ TASK DESCRIPTION/STATEMENT HERE"]
 
With the possible options being:
 
["ENTER ALL (BOTH INCORRECT AND CORRECT) MCQ OPTIONS HERE EACH ON A NEW LINE
 
Option 1
 
Option 2
 
Option 3

..."]

---
 
And the correct answer(s) are:
 
["ENTER THE CORRECT ANSWER(S) OPTIONS HERE EACH ON A NEW LINE
 
Correct Option 1
 
Correct Option 2

..."]
 
---
 
For each of the incorrect options below, provide a SINGLE feedback explanation within 120 characters.
 
Each feedback explanation should be comprehensive but clear and concise as well.
 
The feedback explanations MUST BE STANDALONE (not referencing or depending on other feedback explanations).
 
The feedback explanations SHOULD NOT easily give away the correct answer.
 
Ensure you use simple words for the explanation and avoid advanced vocabulary or formal expressions.

You MUST output each feedback explanation as a bullet point using `-` WITHOUT ANY additional text, prefix, or meta information.
 
Incorrect options:
 
["ENTER THE INCORRECT/WRONG ANSWER(S) OPTIONS HERE EACH ON A NEW LINE

Incorrect Option 1 

Incorrect Option 2
 
..."]
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/Ej-8j/understanding-python's-range()-function-and-its-usage-in-a-for-loop

# Prompts for Parsons problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
>You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in creating parsons problems in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language that are challenging and engaging for learners.

---

### Generate Parsons problem with zero-shot prompting

```
Create a Parsons problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. The objective is to create a medium-difficulty Parsons problem.
3. The number of code lines in the code snippet MUST BE between 8 and 15.
4. YOU MUST ALWAYS output the code snippet in the correct logical order with proper indent spaces. The platform will randomize the lines later!

5. The code snippet MUST NOT include comments and: 
 - 5.1 Ambiguous variable declarations
 - 5.2 Library "import" or "package" statements.
 
6. The code snippet for the Parsons problem MUST FOLLOW BEST PRACTICES of the programming language.

7. The output MUST BE text and have the following format:
 - 7.1 A straightforward but creative problem question/description. DO NOT include HINTS in the description.
 - 7.2 The FULL code snippet for the problem wrapped in triple backticks '```'.
 - 7.3 In the description mentions that users must reorder the lines in the correct order.

8. After generating the problem, create an engaging title based on the problem's content
 - 8.1 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 
9. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
10. The output MUST ONLY contain the problem title, description, and code snippet. DO NOT INCLUDE any additional information or meta text.
```

### 🚀 EXAMPLE USAGE 1: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/XhwxI/working-with-sqlite-in-python-comprehension

### 🚀 EXAMPLE USAGE 2: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/LoILt/title-parsing-csv-data-in-python-comprehension-title

---

### Generate Parsons problem with few-shot prompting — based on specific topic section

```
Create a Parsons problem following these guidelines:
1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium-difficulty Parsons problem using as reference the above theory.

3. The number of code lines in the code snippet MUST BE between 8 and 15.
4. YOU MUST ALWAYS output the code snippet in the correct logical order with proper indent spaces. The platform will randomize the lines later!

5. The code snippet MUST NOT include comments and:
 - 5.1 Ambiguous variable declarations
 - 5.2 Library "import" or "package" statements.
 
6. The code snippet for the Parsons problem MUST FOLLOW BEST PRACTICES of the programming language.

7. The output MUST BE text and have the following format:
 - 7.1 A straightforward but creative problem question/description. DO NOT include HINTS in the description.
 - 7.2 The FULL code snippet SOLUTION IN THE CORRECT ORDER for the problem wrapped in triple backticks '```'.
 - 7.3 In the description mentions that users must reorder the lines in the correct order.

8. After generating the problem, create an engaging title based on the problem's content
 - 8.1 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 
9. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
10. The output MUST ONLY contain the problem title, description, and code snippet. DO NOT INCLUDE any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/jVX7O/adding-data-to-csv-files-in-python
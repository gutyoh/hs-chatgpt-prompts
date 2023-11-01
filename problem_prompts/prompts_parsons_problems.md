# Prompts for Parsons problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

### Generate Parsons problem with zero-shot prompting
> Create a Parsons problem following these guidelines:
> 1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
> 
> 2. The objective is to create a unique/creative medium-difficulty Parsons problem.
> 3. The code snippet for the Parsons problem MUST FOLLOW BEST PRACTICES and BE IDIOMATIC for the language.
> 4. The code snippet MUST NOT include any library "import" or "package" statements.
> 5. The code snippet MUST BE in the correct order; the platform will take care of "scrambling" the code lines.
> 6. The number of lines of code in the code snippet MUST BE between 6 and 15.
> 7. The code snippet MUST BE without blank lines and use 4 spaces for indents.
> 8. The output MUST BE text and have the following format:
> - 8.1 A concise but creative problem question/description. DO NOT include HINTS in the description.
> - 8.2 The FULL code snippet for the problem wrapped in triple backticks '```'.
> - 8.3 After generating the problem, create an engaging title based on the problem's content
> - 8.4 The title must be LESS THAN 40 symbols in the format [TITLE] ... [/TITLE] and put the title FIRST in the output.
> 9. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
> 10. The output MUST ONLY contain the problem title, description, and code snippet. DO NOT INCLUDE any additional meta text apart from these three components.

### Generate Parsons problem with few-shot prompting — based on specific topic section
> Create a Parsons problem following these guidelines:
> 1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
> 
> 2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:
> ```
> ["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]
> ```
> - 2.1 DO NOT DIRECTLY replicate the above theory for the problem.
> - 2.2 The objective is to create a unique/creative medium-difficulty Parsons problem using as reference the above theory.
>
> 3. The code snippet for the Parsons problem MUST FOLLOW BEST PRACTICES and BE IDIOMATIC for the language.
> 4. The code snippet MUST NOT include any library "import" or "package" statements.
> 5. The code snippet MUST BE in the correct order; the platform will take care of "scrambling" the code lines.
> 6. The number of lines of code in the code snippet MUST BE between 6 and 15.
> 7. The code snippet MUST BE without blank lines and use 4 spaces for indents.
> 8. The output MUST BE text and have the following format:
> - 8.1 A concise but creative problem question/description. DO NOT include HINTS in the description.
> - 8.2 The FULL code snippet for the problem wrapped in triple backticks '```'.
> - 8.3 After generating the problem, create an engaging title based on the problem's content
> - 8.4 The title must be LESS THAN 40 symbols in the format [TITLE] ... [/TITLE] and put the title FIRST in the output.
> 9. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
> 10. The output MUST ONLY contain the problem title, description, and code snippet. DO NOT INCLUDE any additional meta text apart from these three components.
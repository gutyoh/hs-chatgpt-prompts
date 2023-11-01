# Prompts for String (Text) problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

### Generate String problem with zero-shot prompting
> Create a string problem following these guidelines:
> 1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
> 2. The objective is to create a unique/creative medium-difficulty string problem.
> 3. The problem's string solution MUST STRICTLY BE a concise code line or a specific keyword NOT multiple lines of code.
> - 3.1 DO NOT create long or complex regex patterns for the solution.
> 4. The problem's question MUST BE direct, clear, and unambiguous.
> - 4.1 DO NOT include the answer in the question!
> 5. The output MUST BE text and have the following format:
> - 5.1 A creative problem question/description.
> - 5.2 A single new line with the solution regex pattern in the following format 'Solution: ...' that:
>    - Starts and ends with `\s*`.
>    - Uses `\s*` around operators and blank spaces to account for different formatting styles.
>    - If the solution is a function name, the REGEX PATTERN MUST MATCH the function name WITH and WITHOUT parentheses (e.g., `\s*print\s*(\(\))?\s*`).
>    - For Java, JavaScript and C++ code the semicolon `;` at the end of the REGEX PATTERN MUST BE OPTIONAL. (e.g. `\s*int\s*counter\s*=\s*0\s*;?\s*`)
>    - Matches both single (`'`) and double (`"`) quotes if they're part of the expected answer.
> - 5.3 After generating the problem, create an engaging title based on the problem's description.
> - 5.4 The title must be LESS THAN 40 symbols in the format [TITLE] ... # Comprehension [/TITLE] and put the title FIRST in the output.
>
>6. If the problem includes code snippets:
>       - Wrap them in `<pre><code>` tags, specifying the programming language.
>       - Ensure the code is valid, idiomatic, and adheres to best practices of the programming language.
>       - Multiline code snippets must have proper indentation and a new line symbol at the end of each line.
> 
>7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
>8. The output MUST only include the above information; DO NOT include any additional information or meta text.


---

### Generate String problem with few-shot prompting — based on specific topic section
> Create a string problem following these guidelines:
> 1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
>
> 2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:
> ```
> ["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]
> ```
> - 2.1 DO NOT DIRECTLY replicate the above theory for the problem.
> - 2.2 The objective is to create a unique/creative medium difficulty string problem using as reference the above theory.
>
> 3. The problem's string solution MUST STRICTLY BE a concise code line or a specific keyword NOT multiple lines of code.
> - 3.1 DO NOT create long or complex regex patterns for the solution.
> 4. The problem's question MUST BE direct, clear, and unambiguous.
> - 4.1 DO NOT include the answer in the question!
> 5. The output MUST BE text and have the following format:
> - 5.1 A creative problem question/description.
> - 5.2 A single new line with the solution regex pattern in the following format 'Solution: ...' that:
>    - Starts and ends with `\s*`.
>    - Uses `\s*` around operators and blank spaces to account for different formatting styles.
>    - If the solution is a function name, the REGEX PATTERN MUST MATCH the function name WITH and WITHOUT parentheses (e.g., `\s*print\s*(\(\))?\s*`).
>    - For Java, JavaScript and C++ code the semicolon `;` at the end of the REGEX PATTERN MUST BE OPTIONAL. (e.g. `\s*int\s*counter\s*=\s*0\s*;?\s*`)
>    - Matches both single (`'`) and double (`"`) quotes if they're part of the expected answer.
> - 5.3 After generating the problem, create an engaging title based on the problem's description.
> - 5.4 The title must be LESS THAN 40 symbols in the format [TITLE] ... # Comprehension [/TITLE] and put the title FIRST in the output.
>
>6. If the problem includes code snippets:
>       - Wrap them in `<pre><code>` tags, specifying the programming language.
>       - Ensure the code is valid, idiomatic, and adheres to best practices of the programming language.
>       - Multiline code snippets must have proper indentation and a new line symbol at the end of each line.
>
>7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
>8. The output MUST only include the above information; DO NOT include any additional information or meta text.

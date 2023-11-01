# Prompts for Faded Parsons (Fill in the blanks) problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

## ⚠️ Generating a Faded Parsons problem requires TWO (2) PROMPTS ⚠️

1. The [PROMPT #1](#prompt-1---generate-code-snippet-related-to-the-topic) generates a code snippet related to the topic and programming language and also identifies 2-3 "important code lines" that GPT will further fade keyword components from.
2. The [PROMPT #2](#prompt-2---generate-the-faded-parsons-problem-with-zero-shot-prompting) instructs GPT to fade out the components, generate the problem title and description, and provide the code snippet with faded components with correct and incorrect options.


### PROMPT #1 - Generate code snippet related to the topic
>Generate a code snippet for a coding problem following these guidelines:
>
>1. The code snippet MUST BE about the Communicating with sockets topic from the Go programming language.
>2. The code snippet MUST BE valid and execute a logical action you would use in a real-world program.
>3. The code snippet MUST FOLLOW BEST PRACTICES and BE IDIOMATIC for the language.
>4. The code snippet MUST NOT have any comments.
>5. The number of lines of code in the code snippet MUST BE between 8 and 15.
>6. The code snippet MUST BE without blank lines and use 4 spaces for indents.
>
>---
>
>After generating the code snippet, identify 2-3 key code lines that convey a complete action. STRICTLY FOLLOW these rules:
>
>1. Each line of code MUST BE valid and work correctly within its context.
>2. DO NOT consider standalone symbols like '{', '}', '(', ')', and ';'. FOCUS ONLY in lines that convey a complete code action.
>3. The output should ONLY include the following:
> - 3.1 First output the ENTIRE code snippet wrapped in triple backticks '```'
> - 3.2 Then output the key lines of the code snippet as a bullet on a new line.
>4. The output MUST NOT include additional text or meta information.

## PROMPT #2 - Generate the faded parsons problem with zero-shot prompting
>Based on the following code snippet:
>```
> ["ENTER THE ENTIRE GENERATED CODE SNIPPET FROM THE PREVIOUS CHAT HERE"]
>```
>
>Fade out MULTIPLE CODE KEYWORDS from these lines of code following the below rules:
>```
> ["ENTER THE MOST IMPORTANT LINES OF CODE HERE
> ...
> ...
> ..."]
>```
>
>1. The faded-out keywords MUST FOCUS on the Communicating with sockets topic from the Go programming language.
>2. Each faded keyword should be UNIQUE. DO NOT fade out the same keyword more than once, even if it appears multiple times in the code.
>
>3. For method or function declarations:
> - 3.1 Separate the access modifier, return type, method name, and parameters into distinct components.
> - 3.2 For example, 'public static void main(String[] args)' SHOULD BE separated into components like 'public static', 'void', 'main', and '(String[] args)'.
>
>4. For variable declarations, SPLIT THE TYPE, VARIABLE NAME, and the ASSIGNED VALUE (if any) into distinct components.
>5. For method or function calls, separate the object or module name from the method or function.
>6. IGNORE standalone characters and DO NOT fade out symbols like '{', '}', '(', ')', ',' and `;`.
>7. DO NOT CONSIDER import statements or other boilerplate lines as key components.
>8. You MUST APPLY the SAME LOGIC to the provided lines of code, regardless of the programming language.
>9. Replace each faded component with the '▭' character.
>
>10. The output MUST BE text and have the following format:
>- 10.1 A creative but concise problem question/description. DO NOT include HINTS in the description.
>- 10.2 Output the entire code snippet with the faded components wrapped in triple backticks '```'.
>- 10.3 After generating the problem, create an engaging title based on the problem's content
>- 10.4 The title must be LESS THAN 40 symbols in the format [TITLE] ... [/TITLE] and put the title FIRST in the output.
>
>11. Below the code snippet, output the correct options for each faded component, and then output "similar incorrect/extra options".
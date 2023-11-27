# Prompts for Code problems with _Simple Test cases_ using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

## ⚠️ Generating a Code problem requires TWO (2) PROMPTS ⚠️

### PROMPT #1 - Generate Code problem description and test cases:

```
Generate a coding problem description following these guidelines:

1. The problem MUST BE FOCUSED on the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. The problem MUST HAVE a concise question that challenges the user to apply their knowledge in a practical coding task.
    - 2.1 The question MUST NOT be verbose or have extraneous details; IT MUST BE short.
    - 2.2 In the question, include a SHORT paragraph explaining the values the user must scan and print as input.
    - 2.3 The question MUST BE medium difficulty.
    - 2.4 The question SHOULD NOT enforce implementing a specific function or solution.
    - 2.5 DO NOT mention the topic or its prerequisites in the question.
    
3. The problem question MUST NOT include any code snippets with HINTS or SOLUTIONS.

4. YOU MUST NOT generate coding problems about:
    - 4.1 Using internal OS commands or system calls.
    - 4.2 Making requests to external websites or APIs.
    - 4.3 Working with files or databases.
    
5. The output MUST BE text and have the following format:
    - 5.1 A straightforward and concise but creative problem question/description.
    - 5.2 A list of test cases in the following format: 1. Input: ... Output: ...
        - Each 'input' MUST BE a single line containing a single primitive data type value (e.g., integer, float, string).
        - Each 'input' MUST BE independent and must not be part of a list or a compound data structure.
        - The 'output' MUST BE directly computable from the 'input' and MUST REPRESENT the expected result given the 'input'.
        - YOU MUST NOT generate lengthy or complex 'input' or 'output' values.
        - Each test case MUST HAVE 'input' separated by a single newline ('\\n') character within a single string and a single 'output' per line. YOU MUST NOT use commas or any other delimiter.
        - YOU MUST NOT wrap 'input' or 'output' values in quotation marks unless the input is a string.
    - 5.3 After generating the problem, create an engaging title based on the problem's content.
    - 5.4 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Application [/TITLE] and put the title FIRST in the output.
       
6. You MUST provide 2-3 SIMPLE, VERY SHORT standalone test cases.
7. DO NOT include any additional information or meta text in the output.
```

### PROMPT #2 - Generate Code problem boilerplate code template:

```
Create a code template for the following coding problem:

["ENTER THE GENERATED CODING PROBLEM DESCRIPTION HERE"]

That has the following test cases:

["ENTER THE GENERATED TEST CASES HERE"
 ...
 ...
 ..."]

YOU MUST STRICTLY follow these rules for creating the code template:

1. The code template MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. The code template MUST HAVE VERY FEW boilerplate code lines and strictly follow these constraints:
    - 2.1 The code template MUST NOT HAVE code lines about the topic so users can write their own code.
    - 2.2 The code template MUST NEVER INCLUDE the solution to the problem.
    - 2.3 The code template MUST NOT INCLUDE the test cases or example usages.
    - 2.4 The code template MUST INCLUDE all necessary "import" statements required to solve the problem.
    - 2.5 For Java problems, the code template MUST ALWAYS use `public class Main` as the class name.
    - 2.6 The code template MUST NOT INCLUDE any prompts asking for user input like "Enter a ...".
    
3. YOU MUST wrap the code template in triple backticks '```' in the output.
4. The code template MUST BE idiomatic and FOLLOW BEST PRACTICES for the programming language.

5. The code template MUST HAVE the following format:
    - 5.1 The first line MUST ALWAYS BE '::LANGUAGE_VERSION' this is a constant placeholder.
    - 5.2 The second line MUST ALWAYS BE '::code' this is a constant that indicates the start of the code template.
    - 5.3 After the second line, comes the ENTIRE CODE TEMPLATE.
    
6. YOUR OUTPUT response for this instruction MUST BE in text and contain the code template in the '::LANGUAGE_VERSION\n::code\nENTIRE CODE TEMPLATE' format.
7. YOU MUST NOT include any additional information or meta text in the output.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/6aqdi/squared-odd-integers-challenge
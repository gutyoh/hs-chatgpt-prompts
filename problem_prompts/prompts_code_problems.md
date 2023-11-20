# Prompts for Code problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

## ⚠️ Generating a Code problem requires TWO (2) PROMPTS ⚠️


### PROMPT #1 - Generate Code problem description and test cases:
```
Generate a coding problem description following these guidelines:

1. The problem MUST BE FOCUSED on the ["ENTER TOPIC TITLE/NAME HERE"] topic.
2. The problem MUST consider basic knowledge of functions and programming concepts of: ["ENTER PREREQUISITES HERE"].
3. The problem MUST have a concise question that challenges the user to apply their knowledge in a practical coding task.
    - 3.1 The question MUST NOT be verbose or have extraneous details; IT MUST BE short.
    - 3.2 In the question include a SHORT paragraph that explains the values the user must scan as input and print as output.
    - 3.3 The question MUST BE medium difficulty.
    - 3.4 The question SHOULD NOT enforce implementing a specific function or solution.
    - 3.5 DO NOT mention the topic or its prerequisites in the question.
4. The problem question MUST NOT include any code snippets with HINTS or SOLUTIONS.
5. YOU MUST NOT generate coding problems about:
    - 5.1 Using internal OS commands or system calls.
    - 5.2 Making requests to external websites or APIs.
    - 5.3 Working with files or databases.
6. YOUR OUTPUT response for this instruction MUST BE in JSON with the following properties:
    - 6.1 question (str),
    - 6.2 test_cases ('[[input, output], ...]' list of lists).
7. You MUST provide 2-3 SIMPLE, VERY SHORT standalone test_cases.
8. DO NOT include any additional information or meta text in the output.
```

### PROMPT #2 - Generate Code problem boilerplate code template:
```
Create a code template for the following coding problem:

["ENTER THE GENERATED CODING PROBLEM DESCRIPTION HERE"]

That has the following test cases:

["ENTER THE GENERATED TEST CASES HERE"]

Follow these rules for creating the code template:

1. The code template MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic.
2. The code template MUST consider basic knowledge of functions and programming concepts of: ["ENTER PREREQUISITES HERE"].
3. The code template MUST HAVE MINIMAL boilerplate code lines and strictly follow these constraints:
    - 3.0 ["ENTER COMMENT RULE BASED ON PREREQUISITES HERE"]
    - 3.1 The code template MUST NOT HAVE code lines of the ["ENTER SPECIFIC TOPIC HERE"] so users can write their own code.
    - 3.2 The code template MUST NEVER INCLUDE the solution to the problem.
    - 3.3 The code template MUST NOT INCLUDE the test cases or example usages.
    - 3.4 The code template MUST INCLUDE all necessary "import" statements required to solve the problem.
    - 3.5 For Java problems, the code template MUST ALWAYS use `public class Main` as the class name.
    - 3.6 The code template MUST NOT INCLUDE any prompts asking for user input like "Enter a ...".
4. YOU MUST NOT wrap the code template in triple backticks '```' in the output.
5. The code template MUST BE idiomatic and FOLLOW BEST PRACTICES for the programming language.
6. The code template MUST HAVE the following format:
    - 6.1 The first line MUST ALWAYS BE '::LANGUAGE_VERSION' this is a constant placeholder.
    - 6.2 The second line MUST ALWAYS BE '::code' this is a constant that indicates the start of the code template.
    - 6.3 After the second line, comes the ENTIRE CODE TEMPLATE.
7. YOUR OUTPUT response for this instruction MUST BE in str and contain the code template in the '::LANGUAGE_VERSION_PLACEHOLDER\n::code\nENTIRE CODE TEMPLATE' format.
8. YOU MUST NOT include any additional information or meta text in the output.
```

### 🚀 EXAMPLE USAGE: TODO
# Prompts for Matching problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
>You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in creating matching pairs problems in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language that are challenging and engaging for learners.

---

### Generate Matching problem with zero-shot prompting
```
Create a matching problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. The objective is to create a medium-difficulty matching problem.
3. The problem MUST HAVE 4-5 pairs of items to match.
4. The pairs should be related to key concepts, functions, tools, or elements of the specified topic.
5. YOU MUST ensure that each pair description:
 - 5.1 Provides enough detail for comprehension while remaining concise.
 - 5.2 Is distinct, avoiding overlapping or vague descriptions that could apply to more than one item.
 - 5.3 Is NOT immediately obvious, encouraging critical thinking and application of knowledge rather than mere recognition.
6. The output MUST BE text and have the following format:
 - 6.1 An engaging BUT CONCISE and CLEAR problem question/description.
 - 6.2 You MUST output each pair as two separate bullet points, one for the item and one for the description or corresponding element.
 - 6.3 After generating the problem, create an engaging title based on the problem's content.
 - 6.4 The title MUST BE LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 - 6.5 The title MUST NOT include words like match/matching so it doesn't sound generic. 
 - 6.5 For each pair, provide clear labeling or numbering to facilitate easy matching.

7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.

8. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 8.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 8.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 8.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

9. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/FBr4x/unraveling-python-sockets-comprehension

---

### Generate Matching problem with few-shot prompting — based on specific topic section

```
Create a matching problem following these guidelines:

1. The problem MUST BE about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:

["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]

 - 2.1 YOU MUST NOT EXACTLY replicate the above theory for the problem.
 - 2.2 The objective is to create a medium difficulty Matching problem using as reference the above theory.
 
3. The problem MUST HAVE 4-5 pairs of items to match.
4. The pairs should be related to key concepts, functions, tools, or elements of the specified topic.
5. YOU MUST ensure that each pair description:
 - 5.1 Provides enough detail for comprehension while remaining concise.
 - 5.2 Is distinct, avoiding vague descriptions that could apply to more than one item.
 - 5.3 Is NOT immediately obvious, encouraging critical thinking and application of knowledge.
6. The output MUST BE text and have the following format:
 - 6.1 An engaging BUT CONCISE and CLEAR problem question/description.
 - 6.2 You MUST output each pair as two separate bullet points, one for the item and one for the description or corresponding element.
 - 6.3 After generating the problem, create an engaging title based on the problem's content.
 - 6.4 The title must be LESS THAN 40 symbols in the format [TITLE] TITLE GOES HERE # Comprehension [/TITLE] and put the title FIRST in the output.
 - 6.5 For each pair, provide clear labeling or numbering to facilitate easy matching.

7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.

8. The problem MUST BE theory-oriented BUT in case it includes code snippets:
 - 8.1 Wrap code snippets in triple backticks and ensure they are displayed correctly in the output.
 - 8.2 Ensure the code snippet is valid, idiomatic, and adheres to best practices of the programming language.
 - 8.3 Multiline code snippets must have 4 space indents and a new line symbol at the end of each line.

9. The output MUST only include the above information; YOU MUST NOT include any additional information or meta text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/FDHYG
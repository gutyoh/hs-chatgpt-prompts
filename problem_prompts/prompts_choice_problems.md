# Prompts for Multiple Choice Question (MCQ) problems using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

---

### Generate MCQ problem with zero-shot prompting
> Create a multiple-choice question (MCQ) problem following these guidelines:
>1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
>2. The objective is to create a unique/creative medium-difficulty MCQ problem.
>3. The problem MUST HAVE 4-5 concise and NOT very lengthy options.
>4. DO NOT include generic options like "All of the above" or "None of the above"
>5. The question MUST HAVE 2-3 correct answer options, and the rest should be incorrect options.
>
> 6. The output MUST BE text and have the following format:
>- 6.1 A creative problem question/description.
>- 6.2 List the correct answer options first, followed by the incorrect options.
>- 6.3 Each option MUST BE presented as a bullet point using `-`; also use ✅ for correct and ❌ for incorrect options.
>- 6.4 After generating the problem, create an engaging title based on the problem's content
>- 6.5 The title must be LESS THAN 40 symbols in the format [TITLE] ... # Comprehension [/TITLE] and put the title FIRST in the output.
> 
>7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
>8. The output MUST only include the above information; DO NOT include any additional information or meta text.

Example usage: TODO

---

### Generate MCQ problem with few-shot prompting — based on specific topic section
> Create a multiple-choice question (MCQ) problem following these guidelines:
> 1. The problem must be about the ["ENTER TOPIC TITLE/NAME HERE"] topic from the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
> 
> 2. Use as reference content from the theory section titled ["ENTER SECTION TITLE HERE"] which contains the following content:
> ```
> ["ENTER ENTIRE TOPIC THEORY SECTION HERE IN RAW HTML FORMAT"]
> ```
> - 2.1 DO NOT DIRECTLY replicate the above theory for the problem.
> - 2.2 The objective is to create a unique/creative medium difficulty MCQ problem using as reference the above theory.
> 
> 3. The problem MUST HAVE 4-5 concise and NOT very lengthy options.
> 4. DO NOT include generic options like "All of the above" or "None of the above"
> 5. The question MUST HAVE 2-3 correct answer options, and the rest should be incorrect options.
> 
> 6. The output MUST BE text and have the following format:
> - 6.1 A creative problem question/description.
> - 6.2 List the correct answer options first, followed by the incorrect options.
> - 6.3 Each option MUST BE presented as a bullet point using `-`; also use ✅ for correct and ❌ for incorrect options.
> - 6.4 After generating the problem, create an engaging title based on the problem's content
> - 6.5 The title must be LESS THAN 40 symbols in the format [TITLE] ... # Comprehension [/TITLE] and put the title FIRST in the output.
>
>7. Ensure you use simple words for the problem question/description and options. AVOID advanced vocabulary or formal expressions.
>8. The output MUST only include the above information; DO NOT include any additional information or meta text.

Example usage: TODO

---

### Generate feedback for incorrect options in (MCQ) problems
> Given the following comprehension problem:
> 
> ["ENTER FULL MCQ TASK DESCRIPTION/STATEMENT HERE"]
> 
> With the possible options being:
> 
> ["ENTER ALL (BOTH INCORRECT AND CORRECT) MCQ OPTIONS HERE EACH ON A NEW LINE
> 
> Option 1
> 
> Option 2
> 
> Option 3
> 
> ..."]
> 
> ---
> 
> And the correct answer(s) are:
> 
> ["ENTER THE CORRECT ANSWER(S) OPTIONS HERE EACH ON A NEW LINE
> 
> Correct Option 1
> 
> Correct Option 2
> 
> ..."]
> 
> ---
> 
> For each of the incorrect options below, provide a SINGLE feedback explanation within 120 characters.
> 
> Each feedback explanation should be comprehensive but clear and concise as well.
> 
> The feedback explanations MUST BE STANDALONE (not referencing or depending on other feedback explanations).
> 
> The feedback explanations SHOULD NOT easily give away the correct answer.
> 
> Ensure you use simple words for the explanation and avoid advanced vocabulary or formal expressions.
> 
> You MUST output each feedback explanation as a bullet point using `-` WITHOUT ANY additional text, prefix, or meta information.
> 
> Incorrect options:
> 
> ["ENTER THE INCORRECT/WRONG ANSWER(S) OPTIONS HERE EACH ON A NEW LINE
> 
> Incorrect Option 1
> 
> Incorrect Option 2
> 
> ..."]

**Example usage: https://chatgpt-ui.aks-internal.int.hyperskill.org/chat/e4754307-7d59-4910-a887-d20063891099**

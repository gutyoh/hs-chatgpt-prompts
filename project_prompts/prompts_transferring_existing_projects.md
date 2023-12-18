# Prompts for transferring existing projects from one programming language to another using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator

```
You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in working with the `hs-test` library, which has the following features:

- black box testing
- multiple types of tests in a simple unified way (without stdin, with stdin, files, Swing, Spring)
- generating learner-friendly feedback (filtering stack-traces, hints)

Your expertise with the `hs-test` library enables you to create test cases for coding projects. Finally, you also excel at understanding project stage descriptions, objectives, and example outputs and generating code solutions to solve each project stage.
```

---

## 📋 Steps to transfer projects from one programming language to another 🔢

Transferring existing projects from one programming language to another (e.g., from Java to Python or from Python to Go) is a three (3) step process that is usually done in the following order:

1. Generate a code reference solution and ensure it passes all the test cases.

2. Determine the topic prerequisites for the stage of the project.

3. Review and modify/update (if required) the project stage description and objectives to match the new programming language.

### ⚠️ Optional step: Translating test cases from Python↔️Java ⚠️

There is one optional step, which is to translate the project test cases from Python to Java or vice versa; this step is NOT always required; however, it can be useful in some cases like:

- **Language proficiency**: If the project author is more proficient in the source language than the target language of a project (e.g., skilled in Java but NOT in Python, or vice versa), it can be convenient to translate the test cases. This approach makes it easier for the Project Author to maintain or fix the test cases during the testing process and in the future.

- **Framework compatibility**: The `hs-test-python` does NOT support testing JVM languages (Java, Kotlin, Scala) solutions, so if you want to transfer a project from Python to a JVM language track, you will need to translate the test cases from Python to Java first before generating the code reference solution.

- **Overall language consistency**: While it's possible to test Python solutions with Java tests, it's considered a best practice to have test cases in the same language as the project solution.

---

### PROMPT #1 - Generate a code reference solution and ensure it passes all test cases:

```
Below are the Stage Description, Objectives, and Examples of expected output for the ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE PROJECT STAGE DESCRIPTION AND EXAMPLES IN HTML FORMAT HERE"
    ...
    ...
    ..."]

Now, based on the above information, YOU MUST provide the FULL CODE SOLUTION in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] language for ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project following these rules:

1. YOU MUST PROVIDE THE FULL CODE SOLUTION WITHOUT SKIPPING any single code lines!

2. YOU MUST review the "Objectives" and the "Example" sections in detail, and MUST ENSURE that your code solution produces the SAME EXPECTED outputs mentioned in those sections!

3. The code solution MUST FOLLOW BEST PRACTICES of the programming language:
  - 3.1 The code solution MUST BE IDIOMATIC, CLEAR, and EASY TO UNDERSTAND.
  - 3.2 THE code solution MUST BE VALID AND WITHOUT ANY ERRORS.
  - 3.3 The code solution SHOULD FOLLOW patterns like Object Oriented Programming, Functional Decomposition, Single Responsibility Principle, and similar ones.
  - 3.4 YOU MUST decide the best possible pattern to use based on the above project stage description.

4. The code solution MUST NOT include the '>' character when requesting user input!

5. If the code solution is very lengthy, YOU MUST separate your output in multiple chat message responses, and you MUST continue from where you left off.

6. The output MUST ONLY include the code solution. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/bDsRK

---

### PROMPT #2 - Determine the topic prerequisites for the stage of the project:

```
Below is the FULL code solution in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language of ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE FULL PROJECT STAGE CODE SOLUTION HERE"
    ...
    ...
    ..."]


Now, based on the above code solution and programming techniques used, YOU MUST PROVIDE the TOPIC PREREQUISITES for the stage of the project following these rules:

1. YOU MUST determine the topic prerequisites from the below list of topics in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] track:

["ENTER THE LIST OF WITH NAMES OF ALL TOPICS IN THE TRACK HERE"
    ...
    ...
    ..."]

2. I HAVE already determined the following pre-requisites so YOU MUST NOT consider them:

["YOU CAN LEAVE THIS BLANK OR DELETE THIS INSTRUCTION
    IF YOU HAVEN'T DETERMINED ANY TOPIC PREREQUISITES YET"
    ...
    ...
    ..."]

3. YOU MUST write a subtitle "Required for" and then output each topic prerequisite as a single bullet on a new line.

4. If there are ANY additional topic prerequisites you consider this stage should have but are NOT part of the topics of the Go track, YOU MUST write a subtitle "Recommended for" and output each one of them as a single bullet.

5. The output MUST ONLY include the topic pre-requisites. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/NZv9g

---

### PROMPT #3 - Review and modify/update (if required) the project stage description and objectives to match the new programming language:

```
Below are the Stage Description, Objectives, and Examples of expected output for the ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE PROJECT STAGE DESCRIPTION AND EXAMPLES IN HTML FORMAT HERE"
    ...
    ...
    ..."]

Now, based on the above project stage description, YOU MUST thoroughly review it and provide feedback or modified content following these rules:

1. YOU MUST keep the theoretical explanations, instructions, and examples as close to the original text as possible. DO NOT alter any part of the text unrelated to technical or programming specific terms.

2. YOU MUST replace ALL language-specific information, code snippets, or terminology with equivalents in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.

3. YOUR OBJECTIVE is to ensure that the project stage description is seamlessly adapted for students of the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language while preserving the educational objectives of the original content.

4. The output MUST BE in HTML wrapped in triple backticks, and it MUST NOT include any additional information explanation or meta-text!
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/CrF_M


---

### OPTIONAL PROMPT — Translate project test cases from one programming language to another:

```
Below are the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] test cases of ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project that uses the `hs-test` library:

["ENTER THE PROJECT TEST CASES HERE"
    ...
    ...
    ..."]

Now, YOU MUST go ahead and TRANSLATE the above ["ENTER OLD TEST CASES PROGRAMMING LANGUAGE NAME HERE"] code into ["ENTER NEW TEST CASES PROGRAMMING LANGUAGE NAME HERE"] following these rules:

1. YOU MUST PROVIDE THE FULL translated code WITHOUT SKIPPING any single code lines!
2. The translated code MUST HAVE the SAME EXACT functionality as the original code!
3. The translated code MUST BE IDIOMATIC AND VALID WITHOUT ANY ERRORS.
4. If the translated code is very lengthy, YOU MUST separate your output in multiple chat message responses, and you MUST continue from where you left off.
5. The output MUST ONLY include the translated code. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/MkBbz

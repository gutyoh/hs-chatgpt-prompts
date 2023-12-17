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

## ⚠️ Steps to transfer projects from one programming language to another ⚠️

Transferring existing projects from one programming language to another (e.g., from Java to Python or from Python to Go) is a four (4) step process that is usually done in the following order:

1. Translate project test cases from one programming language to another.
2. Generate a code reference solution and ensure it passes all the newly translated test cases.
3. Determine the topic prerequisites for the stage of the project.
4. Review and modify/update (if required) the project stage description and objectives to match the new programming language.

The above order is flexible; you could try following a different order. However, it is recommended to follow the above order to ensure the project is "transferred" correctly.

---

### PROMPT #1 - Translate project test cases from one programming language to another:

```
Below are the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] test cases of ["ENTER PROJECT STAGE HERE] of the ["ENTER PROJECT TITLE/NAME HERE"] project that uses the `hs-test` library:

["ENTER THE PROJECT TEST CASES HERE"
    ...
    ...
    ..."]

Now, YOU MUST go ahead and TRANSLATE the above Java code into Python following these rules:

1. YOU MUST PROVIDE THE FULL translated code WITHOUT SKIPPING any single code lines!
2. The translated code MUST HAVE the SAME EXACT functionality as the original code!
3. The translated code MUST BE IDIOMATIC AND VALID WITHOUT ANY ERRORS.
4. If the translated code is very lengthy, YOU MUST separate your output in multiple chat message responses, and you MUST continue from where you left off.
5. The output MUST ONLY include the translated code. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: TODO

---

### PROMPT #2 - Generate a code reference solution and ensure it passes all the newly translated test cases:

```
Below are the Stage Description, Objectives, and Examples of expected output for the ["ENTER PROJECT STAGE HERE] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE PROJECT STAGE DESCRIPTION AND EXAMPLES IN HTML FORMAT HERE"
    ...
    ...
    ..."]

Now, based on the above information, YOU MUST provide the FULL CODE SOLUTION in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] language for ["ENTER PROJECT STAGE HERE] of the ["ENTER PROJECT TITLE/NAME HERE"] following these rules:

1. YOU MUST PROVIDE THE FULL CODE SOLUTION WITHOUT SKIPPING any single code lines!
2. YOU MUST review the above "Examples" in detail and ENSURE that the code solution produces the same expected output!
3. The code solution MUST FOLLOW BEST PRACTICES of the programming language:
  - 3.1 The code solution MUST BE IDIOMATIC, CLEAR, and EASY TO UNDERSTAND.
  - 3.2 THE code solution MUST BE VALID AND WITHOUT ANY ERRORS.
  - 3.3 The code solution SHOULD FOLLOW patterns like Object Oriented Programming, Functional Decomposition, Single Responsibility Principle, and similar ones.
  - 3.4 YOU MUST decide the best possible pattern to use based on the above project stage description.
3. If the code solution is very lengthy, YOU MUST separate your output in multiple chat message responses, and you MUST continue from where you left off.
4. The output MUST ONLY include the code solution. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: TODO

---

### PROMPT #3 - Determine the topic prerequisites for the stage of the project:

```
Below is the FULL code solution in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language of ["ENTER PROJECT STAGE HERE] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE FULL PROJECT STAGE CODE SOLUTION HERE"
    ...
    ...
    ..."]


Now, based on the above code solution and programming techniques used, YOU MUST PROVIDE the TOPIC PREREQUISITES for STAGE 1 of the project following these rules:

1. YOU MUST determine the topic prerequisites from the below list of topics in the Go track:

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

### 🚀 EXAMPLE USAGE: TODO

---

### PROMPT #4 - Review and modify/update (if required) the project stage description and objectives to match the new programming language:

```
Below are the Stage Description, Objectives, and Examples of expected output for the ["ENTER PROJECT STAGE HERE] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE PROJECT STAGE DESCRIPTION AND EXAMPLES IN HTML FORMAT HERE"
    ...
    ...
    ..."]

Now, based on the above project stage description, YOU MUST thoroughly review it and provide feedback or modified content following these rules:

1. YOU MUST replace ALL language-specific information, code snippets, or terminology with equivalents in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
2. YOU MUST ensure that the theoretical explanations, examples, and instructions are VALID and applicable to the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language WHILE RETAINING the original objective of the project stage!
3. YOUR OBJECTIVE is to ensure that the project stage description is seamlessly adapted for ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language students WHILE PRESERVING the original content's educational objectives.
```

### 🚀 EXAMPLE USAGE: TODO

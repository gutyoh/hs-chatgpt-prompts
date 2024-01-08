# Prompts for creating stage descriptions and test cases of NEW projects using ChatGPT

## Initial Conversation prompt

### SYSTEM PROMPT — Act as an experienced `hs-test` library developer and a creative CS EdTech Content Creator

```
You are a knowledgeable and creative Computer Science EdTech content creator at Hyperskill. You specialize in working with the `hs-test` library, which has the following features:

- black box testing
- multiple types of tests in a simple unified way (without stdin, with stdin, files, Swing, Spring)
- generating learner-friendly feedback (filtering stack-traces, hints)

Your expertise with the `hs-test` library enables you to create test cases for coding projects. Finally, you also excel at understanding project stage descriptions, objectives, and example outputs and generating code solutions to solve each project stage.
```

---

## ⚠️ IMPORTANT – Context for using these prompts

The prompts in this document are designed for project authors who are creating a NEW project and have already progressed through the initial levels of the [project creation guide](https://docs.google.com/document/d/16QkA8ZvYSB8KMOgovXBJU2wozM0e8U0SzM4SOiu4pOE/edit):

- #### Level 1: Idea
- #### Level 2: Plan
- #### Level 3: Reference Solution

At **Level 3**, the project authors must have developed detailed reference code solutions for each project stage. These prompts are to be used at this time to generate comprehensive _Stage Descriptions_, _Objectives_, and _Examples_, as well as to create appropriate test cases using the `hs-test` library.

## 📋 Steps to use the prompts 🔢

Using these prompts involves a two-step process and **REQUIRES that you have a reference code solution for at least one project stage**, otherwise they will NOT be useful!

1. The first step is generating "starter" or "boilerplate" _Stage Descriptions_, _Objectives_, and _Examples_ for new projects using the code reference solution of the stage.

   - **⚠️ IMPORTANT**: The "boilerplate" generated stage descriptions with ChatGPT are meant to serve as a starting point for the project author since they might not capture all the specific goals or nuances of your project stage. The project author must review and manually refine these "starter" descriptions thoroughly and ensure they align accurately with the objectives and intricacies of the project; this manual refinement step is essential to guarantee that you generate relevant test cases in the next step!

2. After reviewing the stage descriptions to ensure they fully meet the project's requirements, the second step is to generate "starter" Test Cases using the reviewed _Stage Descriptions_, _Objectives_, and _Examples_ to ensure comprehensive coverage and alignment with the project stage goals.

---

### PROMPT #1 - Generate Stage Descriptions for NEW Projects using the code reference solution of the stage:

```
Below is the FULL CODE SOLUTION for the ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE FULL PROJECT STAGE CODE SOLUTION HERE"
    ...
    ...
    ..."]

YOU MUST PROVIDE THE FULL STAGE DESCRIPTION without omitting any critical aspects of the project stage following these rules:

1. Start by reviewing the above code solution in detail:
  - 1.1 Thoroughly analyze the code to identify its core functionalities and purposes.
  - 1.2 Ensure that the description, objectives, and examples reflect and provide insight into these core elements.

2. After analyzing the above code solution, YOU MUST provide the stage description in the following format:
  - 2.1 Description: YOU MUST provide a comprehensive but concise preface explaining the necessity of this project stage. Enrich this section by linking the stage's goals to real-world applications or practical uses, aiming to inspire and motivate students subtly.

  - 2.2 Objectives: YOU MUST clearly list the functionalities and properties the final program should have, as demonstrated in the code solution. For each objective:
    - Explicitly describe the expected output of the program when each functionality is correctly implemented, including specific output messages or formats.
    - Include how the program should respond in specific scenarios (e.g., missing inputs, error handling).

  - 2.3 Examples: YOU MUST show multiple instances of expected input/output. Ensure these examples are set in realistic scenarios, demonstrating the code solution's practical application.


  - 2.3 Examples: YOU MUST show multiple instances of expected input/output. Ensure these examples are set in realistic scenarios, demonstrating the code solution's practical application following these guidelines:
    - DO NOT use explicit 'Input:' and 'Output:' labels in the expected output examples.
    - List each example output in the format: "Example N: ..." <-- and replace the ... with a short description about the current example.
    - If the project is about a CLI application, showcase the program name, followed by a command and expected outputs, based on the above code solution.

3. The stage description MUST FOLLOW the following best practices:
  - 3.1 The Description MUST BE ENGAGING, CLEAR, and EDUCATIONAL.
  - 3.2 The Objectives MUST BE DETAILED, covering all code functionalities.
  - 3.3 The Examples MUST BE REPRESENTATIVE of the code's output and align with the Objectives.
  - 3.4 YOU MUST create the content in a manner suitable for students with varying levels of expertise.

4. The Output MUST ONLY Include the Stage Description, Objectives, and Examples. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/mcEqq

---

### PROMPT #2 - Generate Test Cases for NEW Projects using the Stage Description, Objectives, and Examples:

```
Below are the Stage Description, Objectives, and Examples of expected output for the ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project:

["ENTER THE PROJECT STAGE DESCRIPTION AND EXAMPLES IN HTML FORMAT HERE"
    ...
    ...
    ..."]

Now, based on the above information, YOU MUST provide the FULL TEST CASES using Hyperskill's hs-test library in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language for the ["ENTER PROJECT STAGE NUMBER HERE"] of the ["ENTER PROJECT TITLE/NAME HERE"] project strictly following these rules:

1. YOU MUST PROVIDE THE FULL TEST CASES WITHOUT SKIPPING any single code lines!

2. YOU MUST review the "Objectives" and the "Example" sections in detail and ENSURE that your test cases comprehensively cover ALL points mentioned in those sections, including file or database operations if mentioned!

3. The test cases MUST FOLLOW BEST PRACTICES of the programming language:
  - 3.1 The test cases MUST BE IDIOMATIC, CLEAR, and EASY TO UNDERSTAND.
  - 3.2 The test cases MUST BE VALID AND WITHOUT ANY ERRORS.
  - 3.3 The test cases MUST INCLUDE concise comments to explain what is being tested.
  - 3.4 YOU MUST decide the best possible test cases pattern to use based on the above project stage description.

4. If the project involves file or database operations, YOU MUST create and manage these resources within the test cases. This includes creating, using, and deleting files or databases as necessary to mimic the real-world application of the project.

5. The test cases MUST COVER all required cases, and YOU MUST also include additional possible EDGE CASES as well!

6. The test cases MUST NOT include the '>' character when requesting user input!

7. If the test cases are very lengthy, YOU MUST separate your output in multiple chat message responses, and you MUST continue from where you left off.

8. The output MUST ONLY include the code with the test cases. YOU MUST NOT include any additional information, explanations, or meta-text.
```

### 🚀 EXAMPLE USAGE: https://chatgpt-ui.aks-internal.int.hyperskill.org/s/Tj1ER

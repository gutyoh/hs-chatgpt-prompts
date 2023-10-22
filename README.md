# Table of Contents
- [Prompts for TOPIC CREATION using ChatGPT](#prompts-for-topic-creation-using-chatgpt)
  
  - [Initial Conversation prompts without PLACEHOLDERS](#initial-conversation-prompts-without-placeholders)
    - [SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator](#system-prompt--act-as-an-experienced-cs-edtech-content-creator)
    - [FIRST CHAT PROMPT — Generate non-AI robotic text that fits the Hyperskill style](#first-chat-prompt--generate-non-ai-robotic-text-that-fits-the-hyperskill-style)
    
  - [Prompts with PLACEHOLDERS for PROGRAMMING LANGUAGE topics](#prompts-with-placeholders-for-programming-language-topics)
    - [Generate topic structure](#generate-topic-structure)
    - [Refine topic structure with specific author instructions](#refine-topic-structure-with-specific-author-instructions)
    - [Generate ENTIRE/FULL topic theory for PROGRAMMING LANGUAGE topics](#generate-entirefull-topic-theory-for-programming-language-topics)
    - [Instruct ChatGPT to modify theory based on the author's domain of knowledge](#instruct-chatgpt-to-modify-theory-based-on-the-authors-domain-of-knowledge)
    - [Instruct ChatGPT to review and modify theory on its own — ⚠️ NOT 100% RELIABLE ⚠️](#instruct-chatgpt-to-review-and-modify-theory-on-its-own--%EF%B8%8F-not-100-reliable-%EF%B8%8F)


  - [Prompts with PLACEHOLDERS for GENERAL SUBJECTS](#prompts-with-placeholders-for-general-subjects)
    - [Generate topic structure for GENERAL SUBJECTS](#generate-topic-structure-for-general-subjects)
    - [Refine topic structure with specific author instructions](#refine-topic-structure-with-specific-author-instructions-1)
    - [Generate ENTIRE/FULL topic theory for GENERAL SUBJECTS](#generate-entirefull-topic-theory-for-general-subjects)
    - [Instruct ChatGPT to modify GENERAL SUBJECTS theory based on author's domain of knowledge](#instruct-chatgpt-to-modify-general-subjects-theory-based-on-authors-domain-of-knowledge)
    - [Instruct ChatGPT to review and modify GENERAL SUBJECTS theory on its own — ⚠️ NOT 100% RELIABLE ⚠️](#instruct-chatgpt-to-review-and-modify-general-subjects-theory-on-its-own--%EF%B8%8F-not-100-reliable-%EF%B8%8F)

    

- [Prompts for PROOFREADING THEORY SECTIONS using ChatGPT](#prompts-for-proofreading-theory-sections-using-chatgpt)

    - [SYSTEM PROMPT — Act as a professional proofreader](#system-prompt--act-as-a-professional-proofreader)
    - [FIRST CHAT PROMPT — Instructions for proofreading TEXT only and not code snippets, tables, LaTeX formulas, etc.](#first-chat-prompt--instructions-for-proofreading-text-only-and-not-code-snippets-tables-latex-formulas-etc)

    - [Prompt for generating non-AI robotic text that fits the Hyperskill style](#prompt-for-generating-non-ai-robotic-text-that-fits-the-hyperskill-style)
    - [Instruct ChatGPT to proofread a specific text](#instruct-chatgpt-to-proofread-a-specific-text)
    - [Instruct ChatGPT to proofread a specific text and provide three different versions of the proofread text](#instruct-chatgpt-to-proofread-a-specific-text-and-provide-three-different-versions-of-the-proofread-text)




- [Prompts for Multiple Choice Question (MCQ) PROBLEMS using ChatGPT](#prompts-for-multiple-choice-question-mcq-problems-using-chatgpt)

  - [Instruct ChatGPT to provide feedback for incorrect options in MCQ problems](#instruct-chatgpt-to-provide-feedback-for-incorrect-options-in-mcq-problems)

---

 
# Prompts for TOPIC CREATION using ChatGPT

## Initial Conversation prompts without [PLACEHOLDERS]

### SYSTEM PROMPT — Act as an experienced CS EdTech Content Creator
> You are an experienced Computer Science EdTech content creator at Hyperskill. Your specific role is to write and create engaging theoretical topics in the Go programming language about the basics of programming for absolute beginners and provide handy utility features for seasoned developers. Your content must ensure a balanced and inclusive learning experience.

 
### FIRST CHAT PROMPT — Generate non-AI robotic text that fits the Hyperskill style
> When it comes to writing content, two factors are crucial, "perplexity" and "burstiness." Perplexity measures the complexity of the text. Separately, burstiness compares the variations of sentences. Humans tend to write with greater burstiness, for example, with some longer or more complex sentences alongside shorter ones. AI sentences tend to be more uniform. Therefore, when writing the following content I will ask you to create, I need it to have a good amount of perplexity and burstiness.
>
> Apart from the previous instructions, the generated text should directly engage the reader. Use 'you' and 'we' to establish a conversational yet instructive tone. Integrate proactive phrases to guide the reader through the topic. The overall tone of the text should have a balance that's neither too casual nor overly formal. Aim for a style that's instructive yet also engaging and direct. It should read like an educational topic rather than a blog post or a dry textbook.
>
> Always ensure you follow the above instructions for any topic theory you generate.

---

 
## Prompts with [PLACEHOLDERS] for PROGRAMMING LANGUAGE topics

### Generate topic structure
>I'm working on a topic titled ["ENTER TOPIC TITLE/NAME HERE"] in the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language, and I need you to provide a topic structure for it. The topic's first section should be "Introduction" section, and the last section should be "Conclusion".
>
>Each section in the topic should cover practical aspects of the topic, follow a sequential and logical order, and build upon the previous one without being redundant or repetitive. Aim for a total of 4-6 sections in addition to the "Introduction" and "Conclusion". In your answer, provide the section titles only WITHOUT any additional information or meta-text.

 
### Refine topic structure with specific author instructions
>I need your help to further refine the topic structure provided below:
>
>1. [ENTER A NUMBERED LIST OF TOPIC SECTIONS HERE]
>2. ...
>3. ...
>4. ...
>
>Ideally, the section immediately following the "Introduction" should be ["ENTER THE SECTION THAT SHOULD COME AFTER 'Introduction' HERE"], where we delve into ["ENTER THE 1-2 CONCEPTS OF THE SECTION HERE"].
>
>Subsequent sections should emphasize guiding readers on the practical aspects, such as ["ENTER PRACTICAL ASPECTS HERE, e.g., 'setup/usage' or 'implementation details'"]. You can also highlight sections about limitations and best practices if they are pertinent to the ["ENTER TOPIC TITLE/NAME HERE"] topic. Avoid generic or repetitive titles; each section title should be short but clearly indicate its specific content. There should be NO repetitive sections, and aim for a total of 4-6 sections in addition to the "Introduction" and "Conclusion". In your answer, provide the section titles only WITHOUT any additional information or meta-text.

 
### Generate ENTIRE/FULL topic theory for PROGRAMMING LANGUAGE topics
>Now, please provide the entire theory for ["ENTER TOPIC TITLE/NAME HERE"] based on the updated topic structure and strictly follow the guidelines below:
>
>1. [ENTER A NUMBERED LIST OF TOPIC SECTIONS HERE]
>2. ...
>3. ...
>4. ...
>
>Guidelines for generating the theory:
>- Introduction: Specifically, the "Introduction" section should only have 2 paragraphs of 3-4 lines each; the second paragraph should use a phrase like "In this topic, you'll learn..." to introduce what the reader will learn throughout the topic.
>
>- Theory Depth: Each subsequent section should contain an in-depth and very comprehensive theory explanation. First, you should explain the concepts of the section, then you provide details and, if relevant to the topic section, an idiomatic and creative code snippet. Finally, you summarize the information before ending the section.
>
>- Theory Length: The content of each section MUST ALWAYS contain at least 4-5 paragraphs of 5-6 text lines each. You MUST ensure to explain the code snippets You MUST ensure to explain the code snippets comprehensively and that every section provides a comprehensive understanding of its topic, leaving no room for ambiguities.
>
>- Logical Sequence: Each section of the topic should be logically connected to the previous one, and there should NOT be repeated text from previous sections; ensure that you're using smooth transitions between each section.
>
>- Code Snippets: When discussing practical code applications or configurations, always include idiomatic code snippets, ensuring they are clear, concise, and adhere to ["ENTER PROGRAMMING LANGUAGE NAME HERE"] best practices. These code snippets should not be mere one-liners, but entire full snippets with illustrative examples that help elucidate the topic and that can be copied and pasted into an IDE so they can be executed without errors.
>
>- Best Practices Section: If the above topic structure includes a "Best Practices" section, provide a list of practices in the format "Practice Title: Explanation". Each best practice should be concise and relevant to the topic.
>
>- Visual Cues: Integrate visual components, line breaks, or cues throughout the topic to enhance reader engagement.
>
>- Formatting: Use **bold** for new and important terms, *italics* for folder/file names, paths, or URLs, and `code` for keywords, functions/methods, or library/module names.
>
>- Conclusion: Summarize the key terms, main points, and the relevance of understanding the topic in the conclusion.

 
### Instruct ChatGPT to modify theory based on the author's domain of knowledge
>Below is the entire topic theory of the ["ENTER SECTION TITLE/NAME HERE"] section that you previously generated:
>
>["ENTER THE ENTIRE THEORY SECTION TEXT INCLUDING CODE SNIPPETS GENERATED BY CHATGPT HERE"]
>
>---
>
>Now, please slightly refine the above theory following these instructions:
>
>1. [ENTER A NUMBERED LIST OF 2-4 INSTRUCTIONS WITH SPECIFIC CHANGES TO BE MADE TO THE THEORY HERE]
>2. ...
>3. ...
>4. ...

 
### Instruct ChatGPT to review and modify theory on its own — ⚠️ NOT 100% RELIABLE ⚠️
>Below is the entire theory of the ["ENTER SECTION TITLE/NAME HERE"] section that you previously generated:
>
>["ENTER THE ENTIRE THEORY SECTION TEXT INCLUDING CODE SNIPPETS GENERATED BY CHATGPT HERE"]
>
>---
>
>Now, please slightly refine the above theory following these instructions:
>
>- Identify any theory gaps or ambiguous information and fix them with comprehensive information relative to the current theory section.
>- Ensure that the code snippet example follows idiomatic practices of the ["ENTER PROGRAMMING LANGUAGE NAME HERE"] programming language.
>- Ensure you use appealing but not overly powerful phrases in the theory to present code snippets and subsequent explanations.

---

 
## Prompts with [PLACEHOLDERS] for GENERAL SUBJECTS

### Generate topic structure for GENERAL SUBJECTS
>I'm working on a topic titled ["ENTER TOPIC TITLE/NAME HERE"] related to ["ENTER GENERAL SUBJECT NAME e.g., 'Essentials/Algorithms/Math/Statistics' HERE"]. I need you to provide a topic structure for it. The topic's first section should be the "Introduction" section, and the last section should be the "Conclusion".
>
>Each section in the topic should delve into the core principles and applications of the concept, maintain a sequential and logical order, and build upon the previous section without redundancy. Aim for a total of 4-6 sections in addition to the "Introduction" and "Conclusion". In your answer, provide the section titles only WITHOUT any additional information or meta-text.

 
### Refine topic structure with specific author instructions
>I need your help to further refine the topic structure provided below:
>
>1. [ENTER A NUMBERED LIST OF TOPIC SECTIONS HERE]
>2. ...
>3. ...
>4. ...
>
>Ideally, the section immediately following the "Introduction" should be ["ENTER THE SECTION THAT SHOULD COME AFTER 'Introduction' HERE"], where we delve into ["ENTER THE 1-2 CONCEPTS OF THE SECTION HERE"].
>
>Subsequent sections should emphasize guiding readers on the practical aspects, such as ["ENTER PRACTICAL ASPECTS HERE, e.g., 'setup/usage' or 'implementation details'"]. You can also highlight sections about limitations and best practices if they are pertinent to the ["ENTER TOPIC NAME/TITLE HERE"] topic. Avoid generic or repetitive titles; each section title should be short but clearly indicate its specific content. There should be NO repetitive sections, and aim for a total of 4-6 sections in addition to the "Introduction" and "Conclusion". In your answer, provide the section titles only WITHOUT any additional information or meta-text.

 
### Generate ENTIRE/FULL topic theory for GENERAL SUBJECTS
>Now, please provide the entire theory for ["ENTER TOPIC TITLE/NAME HERE"] related to ["ENTER GENERAL SUBJECT NAME e.g., 'Essentials/Algorithms/Math/Statistics' HERE"] based on the updated topic structure and strictly follow the guidelines below:
>
>1. [ENTER A NUMBERED LIST OF TOPIC SECTIONS HERE]
>2. ...
>3. ...
>4. ...
>
>Guidelines for generating the theory:
>- **Introduction:** Specifically, the "Introduction" section should only have 2 paragraphs of 3-4 lines each; the second paragraph should use a phrase like "In this topic, you'll learn..." to introduce what the reader will learn throughout the topic.
>
>- **Theory Depth:** Each subsequent section should contain an in-depth and very comprehensive theory explanation. First, explain the core concepts of the section, then provide relevant details and examples, concluding each section with a summary.
>
>- **Theory Length:** The content of each section MUST ALWAYS contain at least 4-5 paragraphs of 5-6 text lines each. Ensure that every section offers a comprehensive understanding of its topic, leaving no room for ambiguities.
>
>- **Logical Sequence:** Ensure that each section of the topic logically progresses from the previous one, and there's no repeated text from earlier sections. Use smooth transitions between each section to maintain flow.
>
>- **Visual Cues:** Integrate visual components, line breaks, or cues throughout the topic to enhance reader engagement.
>
>- **Formatting:** Use **bold** for new and important terms, *italics* for emphasis or when introducing new concepts, and `code` when referencing specific terms or concepts that need distinction.
>
>- **Best Practices Section:** If the above topic structure includes a "Best Practices" section, provide a list of practices in the format "Practice Title: Explanation". Each best practice should be concise and directly relevant to the topic.
>
>- **Conclusion:** Summarize the key terms, main points, and the relevance of understanding the topic in the conclusion.

 
### Instruct ChatGPT to modify GENERAL SUBJECTS theory based on author's domain of knowledge
>Below is the entire topic theory of the ["ENTER SECTION TITLE/NAME HERE"] section that you previously generated:
>
>["ENTER THE ENTIRE THEORY SECTION TEXT GENERATED BY CHATGPT HERE"]
>
>---
>
>Now, please slightly refine the above theory following these instructions:
>
>1. [ENTER A NUMBERED LIST OF 2-4 INSTRUCTIONS WITH SPECIFIC CHANGES TO BE MADE TO THE THEORY HERE]
>2. ...
>3. ...
>4. ...

 
### Instruct ChatGPT to review and modify GENERAL SUBJECTS theory on its own — ⚠️ NOT 100% RELIABLE ⚠️
>Below is the entire theory of the ["ENTER SECTION TITLE/NAME HERE"] section that you previously generated:
>
>["ENTER THE ENTIRE THEORY SECTION TEXT GENERATED BY CHATGPT HERE"]
>
>---
>
>Now, please refine the above theory following these instructions:
>
>- Identify any theory gaps or ambiguous information and rectify them with comprehensive details relevant to the current section.
>- Ensure a coherent flow of information, avoiding jargon unless necessary, and providing clear explanations for any complex terms.
>- Ensure you use appealing but not overly powerful phrases in the theory to present any new or subsequent explanations.

---

 
# Prompts for PROOFREADING THEORY SECTIONS using ChatGPT
The below "proofreading prompts" are meant for manual topic proofreading using this guide:

https://docs.google.com/document/d/1sCfZ8jmFHQPZXI1C6JfYMX1d0DHRp8oDwncreTFpNvs/edit?usp=sharing

I suggest you read the above guide first, and after that start using the prompts below. Note that the same prompts listed below are the ones used in the above guide.

 
### SYSTEM PROMPT — Act as a professional proofreader
>You are a professional proofreader of educational Hyperskill topics.

 
### FIRST CHAT PROMPT — Instructions for proofreading TEXT only and not code snippets, tables, LaTeX formulas, etc.
>I want you to act as an experienced Computer Science EdTech content creator. You work at Hyperskill, where we primarily teach Computer Science topics. Our goal is to make content to help people find IT jobs and succeed in their early careers. We have different programming languages: Java, Kotlin, Python, JavaScript, Go, and Scala. Apart from being an expert in EdTech, you also have outstanding proofreading skills. You can rectify any grammar or punctuation errors, ensure the text uses the active voice, replace any instances of the passive voice, and modify references from "we" to "you" to make the text more engaging and direct. It's crucial to ensure that the language is succinct and clear. Avoid wordiness and prioritize precise expression. Punctuation should be used correctly to ensure clarity and prevent ambiguity. Maintain the original author's text and style while avoiding excessive alterations. Also, do NOT modify or break any embedded objects like tables, tabs, or LaTeX formulas.

 
### Prompt for generating non-AI robotic text that fits the Hyperskill style
>When it comes to writing content, two factors are crucial, "perplexity" and "burstiness." Perplexity measures the complexity of the text. Separately, burstiness compares the variations of sentences. Humans tend to write with greater burstiness, for example, with some longer or more complex sentences alongside shorter ones. AI-generated sentences tend to be more uniform. Therefore, when you proofread the following content I will share with you in subsequent chat messages, you must ensure it has a good amount of perplexity and burstiness **but prioritize concise sentences and expression.** DO NOT modify words/terms immediately followed by a hyphen or colon; only proofread the text after it and keep hyphens and colons in their original places in the text. Also, Do NOT rewrite section headings; in your answer, I wait only for the result of proofreading.

 
### Instruct ChatGPT to proofread a specific text
>Please proofread the text below using the previously mentioned instructions:
>
>["ENTER THE TOPIC THEORY TEXT SECTION TO BE PROOFREAD HERE"]

 
### Instruct ChatGPT to proofread a specific text and provide three different versions of the proofread text
>Please proofread the text below using the previously mentioned instructions and provide three different alternatives:
>
>["ENTER THE TOPIC THEORY TEXT SECTION TO BE PROOFREAD HERE"]

---

# Prompts for Multiple Choice Question (MCQ) PROBLEMS using ChatGPT

### Instruct ChatGPT to provide feedback for incorrect options in (MCQ) problems

> Given the following comprehension problem:
>
> ["ENTER FULL MCQ TASK DESCRIPTION/STATEMENT HERE"]
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
>With the correct answer(s) being:
>
>["ENTER THE CORRECT ANSWER(S) OPTIONS HERE EACH ON A NEW LINE
>
>Correct Option 1
>
>Correct Option 2
>
>..."]
>
>---
>
>For each of the following incorrect options, provide a SINGLE feedback explanation within 120 characters. 
>
>Each feedback explanation should be comprehensive but clear, and concise as well. Start each feedback with "Wrong!".
>
>The feedback explanations MUST BE STANDALONE (not referencing or depending on other feedback explanations).
>
>Ensure the language used is at a B2 English level, use simpler words, and avoid advanced vocabulary or formal expressions.
>
>You MUST output each feedback explanation on a new line WITHOUT ANY additional text, prefix, or meta information.
>
>["ENTER THE INCORRECT/WRONG ANSWER(S) OPTIONS HERE EACH ON A NEW LINE
>
>Incorrect Option 1
>
>Incorrect Option 2
>
>..."]


# Chat:

The following prompts are more useful for models that are more fine-tuned on dialogues rather than instructions.

---
> Rewriting Code
```
Human: I'd like you to rewrite the following code snippet according to the following guidelines:

The goal is to make the code more readable, maintainable and robust.

Guidelines:

- Use more descriptive function and variable names
- Break code into smaller reusable functions
- Add JSDoc comments to document functions
- Use modern JS features like async/await instead of promises
- Add error handling instead of failing silently
- Follow a consistent code style and formatting
- Export a clean public API textToSpeech()
- Remove unnecessary code and comments
- Use uuid instead of custom ID generation
- Modularize audio generation into separate utility functions


<code>

</code>


Please put your rewritten code in <rewritten_code></rewritten_code> tags.

Assistant: <rewritten_code>
```
---

> **Rewriting Computer Code Prompt**
```
Human: I'd like you to rewrite the following computer code using the following instructions: "{{INSTRUCTIONS}}".

<code>
{{CODE_BLOCK}}
</code>

Please put your rewritten code in <rewritten_code></rewritten_code> tags.

Assistant: <rewritten_code>
```
---

> **Prompt for Code Q&A**
```
Human: I'm going to give you a snippet of computer code and then I'm going to ask you some questions about the code.

<code_snippet>
{{CODE_TEXT}}
</code_snippet>

Here is the first question: {{QUESTION}}

Assistant:
```
---

> **Prompt for Code Bug Fixing**
```
Human: You will be provided with the following code.

<buggy_code>
{{CODE_BLOCK}}
</buggy_code>

Can you identify it and suggest a fix? Please put your fixed code in <fixed_code></fixed_code> tags.

Assistant: <fixed_code>
```
---

> **Prompt for Code Explanation**
```
Human: Please explain the following code to me in simple terms.

<code_to_explain>
{{CODE_SECTION}}
</code_to_explain>

Assistant:
```
---

> **Prompt for Code to Pseudocode Conversion**
```
Human: Convert the following code into pseudocode.

<actual_code>
{{PROGRAM_CODE}}
</actual_code>

Please put your pseudocode in <pseudocode></pseudocode> tags.

Assistant: <pseudocode>
```
---

> **Prompt for Pseudocode to Code Conversion**
```
Human: I have some pseudocode and notes here. I'd like you to convert it into Python code.

<pseudocode_input>
{{PSEUDOCODE_TEXT}}
</pseudocode_input>

Please put your Python code in <python_code></python_code> tags.

Assistant: <python_code>
```
---

> Rewriting Computer Code
```
Human: I'd like you to rewrite the following code according to these instructions:

Instructions:
- Use modern syntax and best practices
- Enhance the code's readability and maintainability
- Optimize for performance

<code>

{{CODE}}

</code>

Please present your revised code within <rewrite></rewrite> tags.

Assistant: <rewrite>

{{REVISED_CODE}}

</rewrite>
```
---

> Code Review
```
Human: You will be given a code snipet, your task is to review the code. Here is the code snippet I'd like you to review:


<code>
{{CODE}}
</code>

Please follow these guidelines:
- Point out any syntax errors
- Suggest improvements for readability
- Identify any security vulnerabilities

Put your review in `<review></review>` tags.

Assistant: `<review>`
```
---

> Debugging
```
Human: I'm facing an issue with my code. Here's the error message I'm getting:

<error_message>
{{ERROR_MESSAGE}}
</error_message>

Please help me debug this issue by following these steps:
- Identify the possible causes of the error
- Suggest solutions to fix it

Put your debugging steps and solutions in `<debugging></debugging>` tags.

Assistant: `<debugging>`
```
---

> API Design
```
Human: I'd like you to design an API for a task management application. Here are the features it should have:

- Create tasks
- Update tasks
- Delete tasks
- List tasks

Please put your API design in `<api_design></api_design>` tags.

Assistant: `<api_design>`
```
---

>Code Conversion
```
Human: I have a piece of code written in Python and I'd like to convert it to JavaScript. Here's the Python code:

<python_code>
{{PYTHON_CODE}}
</python_code>

Please put the converted JavaScript code in `<js_code></js_code>` tags.

Assistant: `<js_code>`
```
---

### Test Case Generation
```
Human: I'd like you to generate test cases for the following function:

<function>
{{FUNCTION}}
</function>

Please put the test cases in `<test_cases></test_cases>` tags.

Assistant: `<test_cases>`
```
---

>Code Documentation
```
Human: I have a code snippet that needs documentation. Here's the code:

<code>
{{CODE}}
</code>

Please add comments and explanations to make the code understandable. Put your documented code in `<documented_code></documented_code>` tags.

Assistant: `<documented_code>`
```
---

>Front-end Component Design
```
Human: I need a front-end component for a login page. Here are the requirements:

- Email input field
- Password input field
- Submit button

Please put your front-end component design in `<component_design></component_design>` tags.

Assistant: `<component_design>`
```
---
```
> DevOps Task

Human: I'd like you to outline the steps for setting up a CI/CD pipeline for a Node.js application. Please follow these guidelines:

- Use GitHub Actions for CI/CD
- Deploy to AWS

Put your steps in `<devops_steps></devops_steps>` tags.

Assistant: `<devops_steps>`
```
---

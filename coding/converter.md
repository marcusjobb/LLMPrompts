# Convert code from one language to another

## Description

Uses the LLM model to convert code from one language to another. The model is trained on a dataset of code snippets in multiple languages.

## Prompt

```plaintext
**Task:** Convert the following Python code into equivalent Java code without altering its logic or structure.

**Details:**
- **Source Language:** Python
- **Target Language:** Java

- **Instructions:** Translate the {Source Language} into {Target Language} line by line, maintaining the same logical structure, function names, variable names, and any inline comments where possible.
- **Code Practices:** Use appropriate {Target Language} syntax and conventions, such as type declarations, `for` loops, and method definitions. Aim for simplicity and clarity over optimizations or refactoring. Always use the latest version of the code language.
- **Error Handling:** If the {Source Language} uses constructs that don't have a direct {Target Language} equivalent, use the closest alternative and include a comment explaining any changes or assumptions made.
- **External Libraries:** If the source uses external libraries, use the standard library or common equivalents in the target language.
- **Testing:** Ensure the translated code is functional by running it through a code compiler or interpreter for the {Target Language}.

**{Source Language}:** (Place your code here)
```

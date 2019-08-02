# How to Use the 20 min Lambda Rule Effectively: Basics for Troubleshooting

### 1. Check your code editor for typos and syntax errors

- Typo Checker Extension for VSC Code: [https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

### 2. Check for Written/ Console Log Errors

### 3. Go Through the Code Line by Line

- Use any debugging tools available for the language and dig into the problem
  - Inspect the values of variables. What did you expect vs what the variable is showing?
  - Debugger Extension for VS Code: [https://code.visualstudio.com/api/extension-guides/debugger-extension](https://code.visualstudio.com/api/extension-guides/debugger-extension)
- If it's a UI (user interface issue), use your browser's developer tools. Toggle styles off and on & see which ones are being over-written by others
- If necessary, comment out blocks of code to zero-in on where the issue is
- THE DEEPER YOUR UNDERSTANDING DURING THIS STEP, THE MORE HYPOTHESES YOU CAN CREATE

### 4. Use Google Effectively

- "Even Experienced developers need to Google their way out of problems on a regular basis. Good developers are also, very often, good Googlers"
- Structure of a decent google query:
  - List the Language, library or framework, then add your spoken word OR error message

### 5. Try to Recreate the issue away from the project

- If you still haven’t fixed your problem, you can head to somewhere like CodePen and share your broken code snippet
- This can be helpful if you're dealing with CSS problems

### 6. If the Error is still not fixed: Prepare to Share Your Code

- Make sure its well formatted
- Ensure the code you're sharing recreates the error

### 7. Ask Good Questions

- **Provide potential answers**
  - This helps your TL understand what you know and what you don’t, which means they’ll have an easier time helping you
  - “My best guess is this works like this, because of X and Y, but I’m still a little confused - could you explain this?” (There are times you've resolved the error but don't understand how)
- **Describe the Steps you Took Including:**
  1. What are you trying to accomplish (what did you expect to happen if everything worked)?
  2. The code you're using (or just relevant parts)
  3. Error messages you've gotten
  4. Attempted Solutions and results
  5. Current Error Status (resolved or unresolved)
  6. Tools you're using (version numbers, OS, dependencies, etc) if relevant
- **Ask Open-ended Questions**
  - “What would a good result look like?”
  - “Why is this solution not sufficient?”

### 8. Document your Error: Your future self & others will benefit!

- **Please Post the Following Steps in the "Debug" Thread That I will create for each module**

1. What are you trying to accomplish (what did you expect to happen if everything worked)?
2. The code you're using (or just relevant parts)
3. Error messages you've gotten
4. Attempted Solutions and results
5. Current Error Status (resolved or unresolved)

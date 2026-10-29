# Document Code and Scripts 

Tools to document data analysis when working with code and scripts include **in-line comments** and **version control**.  

To illustrate how these documentation tools can be helpful, imagine you're using code to analyse your research data. Perhaps you don't look at the code for a while during an illness or a vacation. If you return to your code after several weeks, could you quickly identify the right script and understand what it does? Or could you explain to a teammate how you produced a figure? In-line comments make it easier to understand, re-use and return to projects involving scripts.  

Then, to avoid losing work or confusion over which file is the latest version, using version control can help to maintain a clear history of changes. Let's look at each tool in more detail:   

 

## In-line comments 

In-line comments or code notes are in-line notes that you can add to source code while making changes to code and software in a terminal or command line interface.  They're not executable (they don't run with the code), but they give explanation or context about the code’s purpose, logic, and the important decisions that you've made while writing and testing the code.  

 
:::{dropdown} Good practices for code comments
- Use in-line comments to explain why a decision was made, especially when the reason is not obvious from the code itself.  

- Document assumptions, chosen parameters, units, thresholds, data-cleaning rules and any manual decisions that affect the results.  

- Do not make in-line comments on every line. Rather, comment only on elements that may not be clear to someone reading the code.  

- Keep in-line comments up to date when you change the code; incorrect comments can be more confusing than no comments.  

- For reusable functions, add a short description of what the function does, with its inputs and outputs.  

- In-line comments do not replace a README file. Use them for local explanations within the code. Use a README to explain the wider project, scripts, data, and dependencies.
:::

 

## Version control  

Version control is a way to keep a history of changes to the research software and code. It helps you identify which version of the analysis produced a particular result, compare or restore earlier versions, and collaborate without overwriting each other’s work. It can also help you maintain a traceable workflow from the original research objects through processing and analysis to the final results. 

You do not need to master all Git features at once. Start by keeping a clear history of your changes and writing meaningful commit messages. 

:::{dropdown} Good practices for version control 
- Use a version-control system such as Git to record changes to research software and code. Platforms such as GitHub or GitLab can be used to store and share the repository online. 

- Make small, regular commits (snapshot of changes) rather than saving many changes at once. 

- Add clear messages to the commits to explain what changed and why, for example 

- Keep the scripts, configuration files, and documentation needed to reproduce your analysis together in the repository. 

- Do not upload confidential information, personal data, passwords or sensitive project files to a public repository! 

- Keep a clear link between your raw research objects, processing scripts and final results. For example, maintain a record of which input files a script uses and what outputs it produces. 
:::





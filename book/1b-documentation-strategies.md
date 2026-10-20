# 1b. Documentation Strategies  

While planning your project, you should define which tools you will use to document different stages of the research cycle. Here, we'll introduce and describe a variety of documentation strategies. There isn't a single “right” way to do documentation because the selected documentation tools and practices need to **fit the project and process**. We'll look at key questions and types of documentation that correspond to two important stages of the research project cycle: data collection and processing/analysis.  

## Document data collection  

During and after data collection you must document the experimental conditions and research methods used to collect the raw data. You will need to select tools and practices that fit the specifics of your project; the type(s) of documentation needs to fit the processes by which you plan to collect the data. Let's look at strategies that are often used to document how data was collected or to explain features of data that's been collected:  

 
### Ways to document data collection  

 
#### README file 

**What is it?** 
A README file is a human-readable file that provides essential information about a whole project or about individual research object(s) such as datasets and software. README files accompany a project and/or research object to ensure these can be interpreted correctly (Fuchs et al., 2018).  

 **What details are included in a README?**  
::::{card-carousel} 2

:::{card} A README for a **dataset** generally includes:
- Title of the dataset
- Creator
- Description of the dataset
- Location of data collection
- Methodology/how the data was collected
- Date(s) of data collection
- File formats
- Software or tools required to open, process, or use the files
- Relationship between files
- Access, reuse, or licence information, where relevant 
:::
:::{card} A README for a piece of **software** generally includes:  
- The name of the software
- The steps for installation
- Guidelines for contributing to the software
- The license and copyright holder
- Citation
- Acknowledgements  
:::
::::

**Good practices for a README** 

1. It's recommended that researchers create READMEs to accompany all research objects. 

2. Use a human-readable, commonly accessible format, such as plain text (.txt) or Markdown (.md). 

3. Update the README throughout the project 

4. Use clear and consistent terminology, file names, and identifiers 

5. Keep the README close to what it's describing:  

6. A README that provides detailed information about a particular research object should be stored in the same folder as the research object that it is describing. A project-level README is stored in the root folder or main folder for a project. It describes the project, its overall folder structure, and the research objects it contains.

:::{dropdown} More information & templates for README's
- <a href="https://cornell.app.box.com/v/ReadmeTemplate" target="_blank"> README template for data </a>- You can download the template, save it as a .txt file, and fill in the information specific to the data for your project.  

- <a href="https://data.research.cornell.edu/data-management/sharing/readme/#best%20practices" target="_blank"> Writing READMEs for research data </a>- This page explains each component of a README file. If you're unsure about any part of the README template, you can refer to this guide for help. 

- <a href="https://github.com/SS-NES/meta-template/blob/main/meta/template/README.md.jinja" target="_blank"> README template for software  </a>- This template can be filled with the information specific to the software for your project.
:::



#### Lab notebook  

**Definition:** A lab notebook is used to take detailed notes on experimental procedures and to collect data during an experiment. A digital lab notebook can be shared between collaborators and can be backed up more easily than paper lab notebooks. TU Delft has two digital lab notebooks: RSpace and eLabJournal. We'll do a brief introduction to each. Then, if one of these lab notebooks fits the needs of your project, you can experiment with it further.  

**What details are entered in a lab notebook?**  

- description of procedures 

- description of experimental conditions 

- hardware and software specifications and configurations (e.g. instrument models, software versions, calibration and measurement settings)  

- description of settings used  

- materials and equipment used  

- observations and results 

- references to related files or outputs 

- experimental protocols 

:::{dropdown} More information about lab notebooks
Watch this 2-minute-long introductory video to learn about the features of RSpace:   

<iframe
width="560"   
height="315"
src="https://www.youtube.com/embed/q2CEnZRC1_o?si=bb0TCLkbZHIzDGDf"
align="center"
frameborder="0"
allowfullscreen
></iframe>   

Watch this video for an introduction to key features of the eLabJournal electronic lab notebook:  

<iframe
width="560"   
height="315"
src="https://www.youtube.com/embed/ys4BKEWWnEc?si=6CAoZU0JBKiZehkL"
align="center"
frameborder="0"
allowfullscreen
></iframe>  
:::
 

#### Data dictionary 

##### Definition
A data dictionary explains data that has been entered in a spreadsheet. It allows others to clearly interpret variable names and values (OSF Support). 

##### What details are included in a data dictionary?  

- a list of elements/variables found in the dataset 

- definitions for all codes or abbreviations used in the dataset 

- units of measure included in the dataset 

- data types/formats 

- the source of the data  

##### Good practices for data dictionaries  

- Write in clear and consistent variable names to make sure that others can understand and use the data dictionary.  

- Use clear and plain language to explain each variable, explaining what it represents how it was measured or calculated.  

- Specify measurement units, explain all the codes and categories used 

- Record relevant measurement details 

- Update the data dictionary regularly to make sure the information stays accurate as the data is processed further. 

:::{dropdown} More information + templates for data dictionaries 

These links give an explanation, a general template, and more examples of data dictionaries:  

-  <a href="https://www.youtube.com/watch?v=Fe3i9qyqPjo" target="_blank"> Data Dictionaries video from the University of Wisconsin </a> 
  
- <a href="https://help.osf.io/article/217-how-to-make-a-data-dictionary" target="_blank"> How to make a data dictionary </a>  

- <a href="https://library.si.edu/sites/default/files/tutorial/pdf/datadictionaries20180226.pdf" target="_blank"> Guide for creating a data dictionary </a>   
:::

```{note}
Please note: Similar documentation to a data dictionary may be referred to as a “codebook" in some fields or for certain types of data, such as survey or qualitative data. Codebooks are relevant for coded responses and categories used in surveys and qualitative data. They are often used in the social sciences. 
```
 

 

#### File naming conventions 
File naming conventions and folder structures also support efficient documentation because they can give insights into how a project has been structured. For example, file names can help indicate the runs of an experiment and how it was sequenced, and folders can suggest key components of the project workflow. To learn more about creating intentional file names and folder structures, visit the mini-module <a href="https://tu-delft-library.github.io/file_naming_and_folder_organisation/home.html" target="_blank"> File Naming & Folder Organisation </a>.  



 

## Document Your Analysis 

During data processing and analysis you must **document your workflow** to maintain a **clear link between the data, your analysis method(s), and your results**.  

You need to document how you have processed and analysed the data to arrive at research findings, particularly when your project combines different types of research objects, methods, tools and equipment. Your documentation should make it possible for someone else to understand: 

- which data were used and how they were collected 

- how the data were processed and analysed, including the methods scripts, software versions, dependencies, hardware configurations (where relevant), and analysis parameters used 

- which input files produced which outputs or results 

- how results presented in your final report can be traced back to the underlying data and analysis 


In this way, you will provide documentation for your process of analysis: by doing so, you will keep the link between your research objects, processing steps, and findings. This will help you retrace your own work, explain and justify your conclusions, and correct or update your analysis later. It also allows your instructors and classmates to understand and verify how the findings in your report were produced. 

 
### Ways to document your analysis:  

Two of the documentation tools already discussed for data collection can also be used to document the process of data analysis: **a README** and **lab notebook**.  

#### README file for analysis   

An analysis README uses the same README structure. It can be used to document:  

- which input data were used 

- the processing steps 

- the scripts/software used 

- the generated outputs  

 

#### Lab notebook  

A computational or digital lab notebook (e.g. Jupyter Notebook, Quatro). It	can be used to:  

- combine code , explanatory text, and outputs such as tables and figures 

- document the analysis and the results of that analysis  

- bring together your methodology, the code, and analysis in one 	document. 


:::{dropdown} More information about Jupyter Notebook 
Jupyter Notebook is an open-source web application that combines live python code, equations, visualizations, and explanatory text in a single document. It ensures that figures and outputs are generated directly from the underlying data analysis, which reduces mistakes and improves transparency: 

- <a href="https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html" target="_blank"> Jupyter Notebook Beginner Guide </a> 

- <a href="https://github.com/burkesquires/jupyter_training" target="_blank"> Jupyter Notebook Training </a> 

- A TU Delft project, <a href="https://jboss.tudelft.nl/cover/" target="_blank"> JBOSS </a>, lets you integrate your analysis, documentation, and writing through Jupyter Book and Git, enabling seamless connections between code, results, and manuscript preparation. It allows you to write your thesis, including your analysis and present it as your final report - where it automatically generates a pdf of your thesis (via Latex).
  
::: 


### Additional tools to document analysis 

Additional tools to document data analysis when working with codes and scripts include **code comments** and **version control**.  

To illustrate how these documentation tools can be helpful, imagine you're using code to analyse your research data. Perhaps you don't look the code for a while during an illness or a vacation. If you return to your code after several weeks, could you quickly identify the right script and understand what it does? Or could you explain to a teammate how you produced a figure? Code comments make it easier to understand, re-use and return to projects involving scripts.  

Then, to avoid losing work or confusion over which file is the latest version, using version control can help to maintain a clear history of changes. Let's look at each tool in more detail:   

 

#### Code comments 

Code comments or code notes are in-line notes that you can add to source code while making changes to code and software in a terminal or command line interface.  They're not executable (they don't run with the code), but they give explanation or context about the code’s purpose, logic, and the important decisions that you've made while writing and testing the code.  

 

**Good practices for code comments:** 

- Use comments to explain why a decision was made, especially when the reason is not obvious from the code itself.  

- Document assumptions, chosen parameters, units, thresholds, data-cleaning rules and any manual decisions that affect the results.  

- Do not make comments on every line. Rather, comment only on elements that may not be clear to someone reading the code.  

- Keep comments up to date when you change the code; incorrect comments can be more confusing than no comments.  

- For reusable functions, add a short description of what the function does, with its inputs and outputs.  

- Comments do not replace a README file. Use comments for local explanations within the code. Use a README to explain the wider project, scripts, data, and dependencies. 

 

#### Version control  

Version control is a way to keep a history of changes to the research software and code. It helps you identify which version of the analysis produced a particular result, compare or restore earlier versions, and collaborate without overwriting each other’s work. It can also help you maintain a traceable workflow from the original research objects through processing and analysis to the final results. 

**Good practices for version control:**  

- Use a version-control system such as Git to record changes to research software and code. Platforms such as GitHub or GitLab can be used to store and share the repository online. 

- Make small, regular commits (snapshot of changes) rather than saving many changes at once. 

- Add clear messages to the commits to explain what changed and why, for example 

- Keep the scripts, configuration files, and documentation needed to reproduce your analysis together in the repository. 

- Do not upload confidential information, personal data, passwords or sensitive project files to a public repository! 

- Keep a clear link between your raw research objects, processing scripts and final results. For example, maintain a record of which input files a script uses and what outputs it produces. 

- You do not need to master all Git features at once. Start by keeping a clear history of your changes and writing meaningful commit messages. 

 



 

 

 

## Check your understanding  

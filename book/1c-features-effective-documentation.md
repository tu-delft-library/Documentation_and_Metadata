# 1c. Features of effective documentation  

Here, we'll look at characteristics of “good” data documentation that make research objects reproducible. We'll include a scenario for each to make these features more concrete:   

### Complete: 
The documentation includes all details and contextual information that would be required to understand what was done and, where applicable, reproduce the testing conditions to repeat or continue the work. 

```{admonition} Scenario: incomplete documentation  
:class: tip
A researcher is testing the load capacity (fatigue behaviour) of a new type of composite material. The experiment involves placing small samples of the composite material into a hydraulic testing machine that's connected to a software program.

During testing, the software automatically records data for the samples; it collects data on the stress and strain on the specimen and temperature changes on the surface of the specimen. The researcher also uses a lab notebook to record any machine settings that could greatly impact the conditions of the experiment: for example, the temperature of the testing chamber, the loading frequency of the machine, and the amount of force that was applied during each run of the experiment. However, the researcher forgets to include the temperature of the testing chamber in the documentation file.

Due to this incomplete documentation, it's not possible for others to assess the validity of the experimental results, recreate the experiment, or reproduce the results.  
```  
This example shows the importance of including relevant details and **complete** information about experimental conditions in documentation files. 

### Consistent: 
Units, names, terminology, variables are documented, and documentation practices are used consistently throughout the project. 

For collaborative projects, the planned documentation strategy should remain consistent across collaborators. You can imagine how confusing and unnecessarily difficult it would become if each collaborator documents differently. Thus, it's important to establish norms for documentation early on when doing projects with other people.  

```{admonition} Scenario: Inconsistent Documentation Practices 
:class: tip
A team of researchers is collaborating to design a new sensor for measuring air quality. At the beginning of the project, the team does not establish a shared plan for documenting experimental results, design decisions, or changes to the design. Nor do they form consensus about who is responsible for maintaining the documentation or where the documentation will be stored.  

As the project develops, the team conducts experiments to test different components in the sensor. Without a unified documentation strategy, the results are recorded in a variety of different ways. Some team members keep personal notes about the conditions under which experiments were performed, while others store data in separate files and neglect to document the specific testing conditions. Some test results are discussed during meetings, but never formally recorded. And at several points, team members update the design files without documenting what was changed and why.  

At the end of the project, the team needs to write a final report explaining the development of the sensor, the experiments that were conducted, and how these results informed the final design. However, because the project was not consistently documented, the researchers struggle to reconstruct the sequence of experiments and design decisions. They have difficulty determining which experimental results support particular design choices. In some cases, they cannot establish the conditions under which earlier experiments were performed. The team therefore has to spend considerable time searching through personal notes, data files, meeting records, and different versions of the design to reconstruct the project's history. Thus, the final report is more difficult to produce and may provide an incomplete or uncertain account of how the final design was developed.  
```

This example shows how important it is to discuss plans for documentation and come to consensus within your team before you start to collect or process any research data. **Consistency** can save everyone significant time and headaches.   

 

### Accurate
The documentation describes exactly what was done. The documentation should be a concise but accurate description of exact steps that were followed. The level of specificity may vary from field to field.  

```{admonition} Scenario: Inaccurate Documentation 
:class: tip
A researcher provides images and instructions for the assembly of a load-bearing piece of hardware which consists of multiple components bolted together. The researcher accidentally lists the wrong size of bolts required for assembly: the researcher specifies a 6 mm bolt, but a 8 mm bolt is required. This means that anyone trying to build the piece of hardware will use undersized bolts. The too-small bolts won't be able to safely withstand the same heavy loads and force factors that were tested during the original experiment. The error in documentation could lead to accidents.  
```  

### Up-to-date
The documentation is maintained and updated **throughout the project**.   

```{admonition} Scenario: Documentation not updated 
:class: tip
A researcher is developing software to analyse research data. The researcher uses several external libraries to build the software. Partway through the project, the researcher updates one of these libraries to a newer version. However, the researcher forgets to record the update in the project's documentation or list of software dependencies. When other researchers later try to reuse the software, they may install a different version of the library, which causes errors and produces different results. As a result, they are unable to reliably reproduce the original researcher's outputs.  
```

### Accessible
Documentation is most accessible if it is digital, machine-readable, findable, and stored in an open or commonly used format.  

```{admonition} Scenarios: Inaccessible documentation  
:class: tip
- Scenario 1: A lab moved and the original documentation for a project (stored in paper notebooks) cannot be found.  

- Scenario 2: It's difficult to find the documentation file for a project because the location of the file is not clear (e.g. it's not clearly named or it's not saved next to the research object that it's describing).   

- Scenario 3: The documentation for an experiment is locked behind a paywall or a restricted access portal.  
``` 

## Section summary 
To summarize, complete, consistent, accurate, up-to-date and accessible documentation creates transparency by making it clear what was done to generate outputs, how, and why.  

 

 


 

 

nt of the severity of these risks, and mitigation measures for the risks. 

Transparency on the model itself is also recommended by publishing the source code (properly versioned), algorithms, and parameters, at least.  

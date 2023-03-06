# Learner Log Entry #6

## Prompts
*Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:*

### Rose:
**The highlight from the previous FOSS session, such as something you found particularly interesting. This could also be something you're excited to implement now.**  
*This week in FOSS we reviewed reproducible research.  They distinguished Repeatibility of the investigator executing their work with the same result, Replicable, with an example of a someone in the same lab to replicate the work, and Reproducibility with other labs being able to repeat the work.  A way to create experiments that can allow for reproducible science for computational work is using package managers.  It was mentioned that two popular package managers are pip and conda.  It was mentioned that conda packages heve greater quality control and may be safer to use.  Pip may also have some dependency conflict.  When installing libraries or packages it's important to specify version, or the latest version may be installed that could cause compatibility issues.  
It was also mentioned that repositories with files for environment specifications can be stored in github, and although github repositories cannot usually get DOIs, there is a method when specifying environments that it is possible to get a DOI utilizing Github actions and Zenodo.
For R environments, people often use renv package as a versioning tool.
The best way to make data science analysis and tools reproducible is to use containers, of which Docker is a ubiquitous open source container engine software.
Containers are similar to virtual machine, but gain efficiency by using the running computer's kernel, rather than creating full virtualization of hardware and OS which is done for virtual machines.
A few tools for container creation and protocols are Docker Hub for Python and R studio Rocker Project for R.
In the breakout session we also spoke about the use of Google Colab or Github Codespaces for writing code.  Github Codespaces has excellent synch functionality with Github.  You would use vscode on the virtual machine to write the code, package it into a container with appropriate packages, and then pull the code and containers to a Github library.*    
### Bud: 
**Something that you are looking forward to digging into deeper. This could also be ideas on how to apply concepts to your research in the future.**  
*I started reading about containers and docker in preparation for container camp.  To migrate to containers I'll need to build current installation step into scripts called Docker files, and the deployment documents into a descriptive application menifest using Docker Compose or Kubernetes format.*

### Thorn: 
**Something that was challenging that could be worked on, such as anything that wasn't 100% clear and could be elaborated on. Any sticking points should be addressed here.**  
*I need to reproduce the tutorial for the bioinformatics analysis tutorial with mamba and nextflow.  This is an example Of using script automation, with another example is using snakemake files*

## Additional thought
**Write anything that you think would be important for YOU later on.**  
*Continue to write code, even if its bad code.*

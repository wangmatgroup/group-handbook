# Data archiving

#### Backup your data <a href="#id-3.datacurationandarchiving-whycurate-archive" id="id-3.datacurationandarchiving-whycurate-archive"></a>

Redundancy is your friend. Make sure you have a backup of all files needed to reproduce your work and also a backup of your backup:

* input/output files of the calculations that made it into the paper (usually on [TACC Ranch](https://portal.tacc.utexas.edu/user-guides/ranch)). Wennie also recommends having a smaller subset of files on your local computer
* scripts and intermediate files that are needed to reproduce your work

Most OS come with a backup tool (on Ubuntu, Deja-dup has a simple GUI). Backup data on your local computer regularly (at least once a week if not everyday) and on the supercomputing cluster regularly (at least once a month).&#x20;

#### Why curate/archive <a href="#id-3.datacurationandarchiving-whycurate-archive" id="id-3.datacurationandarchiving-whycurate-archive"></a>

* **Reproducibility:** Science as a whole benefits from having results that are traceable and reproducible. As our ability to generate data continues to increase, making sure that previous work is not lost is extremely important.&#x20;
* **Accessibility**: Sometimes other people want to use your data to try new things (this is good! It’s a great indicator that what we are doing is relevant in the field). Sometimes I will need to access the data and figures, especially after you leave the group. And sometimes you will need to access old data you did at an earlier point in your career (e.g., replotting a figure or checking how you did something). Make sure the hard work you put in doesn’t get lost!

You can read more about making data [FAIR](https://www.go-fair.org/fair-principles/).&#x20;

#### What to curate/archive <a href="#id-3.datacurationandarchiving-whattocurate-archive" id="id-3.datacurationandarchiving-whattocurate-archive"></a>

Once the paper is close to completion (i.e., published), your next task is to curate the relevant files generated and archive them. Essentially what went into writing the paper (suggested file organization):

* **Electronic notebook or file** that describes how the files are related to each other, what they were used for, and reproduces the figures and data analysis- essentially a  thorough README file. Anyone should immediately be able to tell your workflow for generating and analysing the data. Jupyter notebooks is a great tool for this because you can embed images, hyperlink, run scripts and plotting procedures, etc. I highly recommend using such kind of electronic notebooks; an example can be found in [\*.pdf ](https://wikis.utexas.edu/download/attachments/343548162/main-notebook.pdf?version=1\&modificationDate=1650312235620\&api=v2)and [\*.ipynb](https://wikis.utexas.edu/download/attachments/343548162/main-notebook.ipynb?version=1\&modificationDate=1650312235692\&api=v2) formats.
* **Figures/Tables**: including scripts, intermediate files used to make the figures/tables, and the final versions of the figures/tables submitted
* **Scripts**: other scripts used in data analysis, setting up calculations, etc.; be sure to have put in enough comments so that someone else or you in the future understands what the script is supposed to do, how that is accomplished, how to use it, and limiting use-case scenarios (if applicable)
* **Paper**: include the final version of the paper, reviewer comments/responses, and other related submission materials
* As a side note, in addition to the final curation of the paper, Wennie a separate file organization system for all the data and analysis done beforehand, including the data that does not necessarily make it into a paper.
* Archive your work and (like any data) have at least one backup (see above).
* Both you and Wennie should have a copy of the completed data curation at the end of this process.&#x20;

#### Where to curate/archive <a href="#id-3.datacurationandarchiving-wheretocurate-archive" id="id-3.datacurationandarchiving-wheretocurate-archive"></a>

Zenodo → generates DOI\


Electronic notebook software: [https://openbis.ch/](https://openbis.ch/)

* **Wrap up the project:** Once we have finished the proof stage and the paper is published, send Wennie (and any relevant co-authors) the final pdf along with a full citation (with all author names, title, page numbers, the works), DOI, full text acknowledgements, and bullet points summarizing the acknowledgements.&#x20;


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

Once the paper is close to completion (i.e., published), your next task is to curate the relevant files generated and archive them. The curation is intended to essentially capture what went into writing the paper (suggested file organization):

* **Electronic notebook or file** that describes the software used, how the files are related to each other, what they were used for, and reproduces the figures and data analysis. Jupyter notebooks are a great tool for this because you can embed images, hyperlink, run scripts and plotting procedures, etc.; an [example](https://utexas.box.com/s/i9hzs56c31uirg4sbelok0w0950hjeoe) can be found in our group shared folder.

> &#x20;**Note:** It is recommended to include the metadata (e.g., describing file structure, how each input relates to the published figure or table).&#x20;

* **Figures/Tables**: including scripts, intermediate files used to make the figures/tables, and the final versions of the figures/tables submitted
* **Scripts**: other scripts used in data analysis, setting up calculations, etc.; be sure to have put in enough comments so that someone else or you in the future understands what the script is supposed to do, how that is accomplished, how to use it, and limiting use-case scenarios (if applicable)
* **Paper**: include the final version of the paper; for internal data curation, include the reviewer comments/responses, and other related submission materials (e.g., list of requested reviewers and editors, author information, publishing agreements)
* **Inputs/Outputs:** Provide a minimum set of input, raw data files, output files that are needed to reproduce each distinct calculation. A rule of thumb is if the calculation was included in the paper, then it is a calculation to be curated. For example, it is sometimes but not usually necessary to save the wave function or charge density files, which often have the largest memory footprint. For VASP calculations, omit the POTCAR file used.&#x20;
* As a side note, in addition to the final curation of the paper, send Wennie a separate file organization system for all the data and analysis done beforehand, including the data that does not necessarily make it into a paper.
* Archive your work and (like any data) have at least one backup (see above).
* Both you and Wennie should have a copy of the completed data curation at the end of this process.&#x20;

#### Options for curating/archiving data for outside access <a href="#id-3.datacurationandarchiving-wheretocurate-archive" id="id-3.datacurationandarchiving-wheretocurate-archive"></a>

* [Zenodo](https://zenodo.org/) → hosted by CERN, generates DOI
* [Figshare](https://figshare.com/)
* Electronic notebook software: [https://openbis.ch/](https://openbis.ch/)

> **Note**: Double check that the DOI link is working.

#### Curating/archiving data within the group

In addition to preparing the data to be shared outside the group, upload your curated data to the shared folder on Ranch (see [Group Accounts](https://utexas.box.com/s/217scejibg75iq5k05uocjtuqsa8rrvi) in the group shared folder).

#### **Wrap up the project**

Once we have finished the proof stage and the paper is published, send to co-authors or upload to a shared Box folder:

* final set of documents of the manuscript, the manuscript with changes highlighted, and reviewer report (e.g., \*zip of LaTeX, \*.docx \*\*and\*\* \*.pdf)&#x20;
* a document containing the full citation and DOI
* a document containing full text acknowledgements, and bullet points summarizing the acknowledgements (who for what funding source).&#x20;

See also [After publishing](writing-a-manuscript/after-publishing.md).


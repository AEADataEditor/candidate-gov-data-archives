# List of candidate US government data that is only present on uncurated gov't websites

This repo has a CSV file [candidates-us-gov-data.csv](candidates-us-gov-data.csv) that lists potential candidates for curation. 

The US Government (regulatory and statistical agencies) provide a wealth of data. Not all of it is easily usable, so users have made efforts to render data more accessible. The underlying data is not always robustly archived - permanent URLs are rare, DOIs are even rarer, and the occassional website reorg obliterates access to some data.

The fix is to have the research community archive these data. This list is a start. We have listed the dataset, the article (often forthcoming at the time it is first posted) that uses the data. Willing users can archive these data as follows, and let us know:

- Create a separate (new) openICPSR deposit, or Dataverse, Zenodo, etc. are also OK. We'll call this the "USGOV deposit"
  - The title would be something meaningful, like "Historical FERC Form 714 submissions"
  - "Authors" are the depositors, and ideally list the government agency as well (makes it easier to find).
  - Dump the raw files (unmodified) from the US gov't website in there
  - Create a simple README that summarizes the processing, including any manual editing that is often necessary (needs to be transparent, not necessarily computationally reproducible).
  - Choose a license, which might include a requirement to cite a related paper. For "mostly data" deposits like this, we suggest CC-BY (standard on openICPSR), or CC-BY-NC (you retain the ability to separately assign commercial rights, should there be such a possibility)
  - Also provide any scripts you used for cleaning, but the key part is the verbose description of what happened between raw files and cleaned files
  - (OPTIONAL, if AVAILABLE) Upload the cleaned files as well (e.g. to a directory "cleaned/") - these are the "ready-to-use" files that authors might use in their article, but which are also of use to others
- Once satisfied, publish (if openICPSR: submit to AEA) this deposit. 
  - This gives you a DOI, which allows you (and others) to cite the data. 
  - It also makes the data findable through Data Set Searches

If you are the original author, back in your current paper/deposit, do NOT provide any of the files you already uploaded to the USGOV deposit. Rather, cite the deposit (in paper, in README), and name the files that a user should use (i.e., "all the files in "cleaned/").


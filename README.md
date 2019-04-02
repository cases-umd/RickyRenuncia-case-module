# Using this CASE Files Template

This repository holds a set of files that provide a template for creating your
own CASE File for contribution to the cases.umd.edu website. You can use the Git
fork feature (upper right button) to start your own CASE File repository,
starting from these files. Then you will have your own Git repository where you
can edit it into your own CASE File.

These templates and the pedagogy around them continue to develop. We welcome your suggested changes to this template, primarily via GitHub pull requests.

## Template Files
* index.ipynb - Overview of the project subject matter and source data.
* lesson-plan.ipynb - Guidance for an instructor who want to teach from these notebooks.
* notebook-N.ipynb - Individual units or lessons that apply a computational technique to the data.

## CASE File Metadata
Jupyter Notebooks include a metadata section, which is invisible in the JupyterLab editor, but is visible from the standard Jupyter Notebook interface, under **Edit -> Edit Metadata**. If you are using JupyterLab, you may edit the metadata by right-clicking on the notebook in the file browser, then select **Open With -> Editor**. Each CASE File contains an index.ipynb file is where any metadata fields that describe the overall CASE File are expected, under the "case_info" key.

For now, the expected metadata will be a list of computational practices that are involved in the CASE File. The values enlisted here come from the Computational Practices listed on the homepage of the cases.umd.edu site. Here is a snippet of such a metadata section:

```json
"metadata": {
  "cases_info": {
   "computational_practices": [
    "cas:dp_collecting_data",
    "cas:dp_creating_data"
   ]
  },
...
```


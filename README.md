# NiW: Notebooks into Workflows

This is a project to convert [Jupyter Notebooks](http://jupyter.org) into [WINGS workflows](http://www.wings-project.org).

## How to use NiW

To execute NiW, open the terminal and enter:
```
$ niw example/Disease+Analysis.ipynb
```

NiW creates: 
* a folder **workflow** and a subfolder **DiseaseAnalysis**, based on the notebook filename after removing spaces and any special characters.
* a zip file for each component of the corresponding WINGS workflow.

TODO:
* Integrate NiW with the WINGS API to create automatically the WINGS workflow, workflow components, component types and data types. For more details about the WINGS workflows, see [WINGS tutorial](http://www.wings-workflows.org/tutorial/).
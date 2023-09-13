# Sample MaterialX Learn Codespace

This is a sample repository which has been set up to run Jupyter notebook examples
from the [MaterialX Learn repo](https://github.com/kwokcb/MaterialX_Learn)

## Contents

There is currently a [single notebook](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/notebooks/mtxl_json_notebook.ipynb) which contains parts of the JSON serialization notebook as a test.
![image](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/assets/49369885/9a080432-25ac-472a-ab25-a6bea02765eb)

The [devcontainer.json](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/.devcontainer/devcontainer.json) file includes a startup command to install package dependencies from the [requirements.txt](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/requirements.txt).
This file includes minimally the IPython and MaterialX packages. 

## Usage

Users can create a new repo or fork from this repo as a starting point and copy over whatever content they wish from the [Materialx Learn repository](https://github.com/kwokcb/MaterialX_Learn/) or create their own.

If usnig MaterialX Learn notebook examples, it is advisable to copy over the [mtlxutils](https://github.com/kwokcb/MaterialX_Learn/tree/main/pymaterialx/mtlxutils) subfolder from the [pymaterialx](https://github.com/kwokcb/MaterialX_Learn/tree/main/pymaterialx) folder which contains
the various notebooks as some notebooks depend on Python utilitues from that folder.


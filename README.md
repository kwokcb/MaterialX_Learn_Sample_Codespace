# Sample MaterialX Learn Codespace

This is a sample repository which has been set up to run Jupyter notebook examples
from the [MaterialX Learn repo](https://github.com/kwokcb/MaterialX_Learn)

## Contents

There is currently a [single notebook](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/notebooks/mtlx_json_notebook.ipynb) which contains parts of the JSON serialization notebook as a test.
![image](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/assets/49369885/9a080432-25ac-472a-ab25-a6bea02765eb)

The [devcontainer.json](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/.devcontainer/devcontainer.json) file includes a startup command to install package dependencies from the [requirements.txt](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/requirements.txt).
This file includes minimally the IPython and MaterialX packages. 

### Codespaces vs Colab

Please see the [hosting document](https://kwokcb.github.io/MaterialX_Learn/documents/hosting.html) information about hosting and differences between hosting on Github Codespaces vs Google Colab.

For the Colab, recommended additional setup information is included for the sample notebook to clone this repo and perform MaterialX installs fron PyPi.
For Codespaces, a new space only needs to be created from your own repo as mentioned above. 

## Usage

Users can create a new repo or fork from this repo as a starting point and copy over whatever content they wish from the [Materialx Learn repository](https://github.com/kwokcb/MaterialX_Learn/) or create their own.

If using MaterialX Learn notebook examples, it is advisable to copy over the [mtlxutils](https://github.com/kwokcb/MaterialX_Learn/tree/main/pymaterialx/mtlxutils) subfolder from the [pymaterialx](https://github.com/kwokcb/MaterialX_Learn/tree/main/pymaterialx) folder which contains
the various notebooks as some notebooks depend on Python utilitues from that folder.


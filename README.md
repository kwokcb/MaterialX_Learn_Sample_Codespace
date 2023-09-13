# Sample MaterialX Learn Codespace

This repository has a codespace associated with it which can be used to run Jupyter notebook examples
from the [MaterialX Learn repo](https://github.com/kwokcb/MaterialX_Learn)

## Contents

There is currently a [single notebook](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/notebooks/mtxl_json_notebook.ipynb) which takes parts of the JSON serialization notebook as a test.

The [devcontainer.json](https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/.devcontainer/devcontainer.json) file includes a startup command to install package dependencies from the [requirements.txt](
https://github.com/kwokcb/MaterialX_Learn_Sample_Codespace/blob/main/requirements.txt).
This file includes minimally the IPython and MaterialX packages. 

## Usage

Users can copy orfork this repo as a starting point and copy over whatever content they wish from the Materialx Learn repoository or create their own.

If copying from this repo, it is advisable to copy over the `mtlxutils` subfolder from the `pymaterialx` folder which contains
the various notebooks as some notebooks depend on Python utilitues from that folder.


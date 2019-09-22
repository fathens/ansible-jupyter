# Jupyter Kernels
Ansible role for Jupyter Notebook and Kernels

###

| name | required? | description |
|---|---|---|
| jupyter_kernels | no | name of kernels to be installed (default: all of availables) |
| jupyter_port | no | port number of jupyter notebook (default: 8888) |
| jupyter_notebook_storage_repo | no | repository of storing jupyter's storage |

if `jupyter_notebook_storage_repo` is not defined, it will be just ignored.

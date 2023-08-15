# huggingfacepocs
all pocs done for hugging faces and its documnetation
Installed latest verision of Ubuntu Linux using the documenettaion -> https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview
The updated the OS with all latest packages, including Python.  However, new pacakges cannot be installed directly from the prompt.
So created a new virtual space for Python using the doumenetation. -> https://www.omgubuntu.co.uk/2023/04/pip-install-error-externally-managed-environment-fix

    sudo apt install python3-venv
    python3 -m venv /home/robin/.venv/python-venv-huggingface/bin
    source /home/robin/.venv/python-venv-huggingface/bin/activate

I am using VScode to run the python code. So I have to set the interpreter to the new location of venv.
Used the documenttaion -> https://code.visualstudio.com/docs/python/environments

Then followed to the documenetaion 
    https://huggingface.co/docs/transformers/installation
Installed Pytorch -> https://pytorch.org/get-started/locally/

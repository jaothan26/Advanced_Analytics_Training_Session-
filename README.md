Mayato Analytics Training
==================================

##Installation

### Getting the package and enviroments
Please download this package from
[Link](https://mayato.com) or clone it with

```bash
git clone https://mayato.com
```

Next, create the Anaconda environment as defined in the .yml file in the folder envs.


```bash
cd example-package\envs
conda env create -f <env>.yml
```

To activate an Ananconda environment use one of the following. Depending if you use bash or windows shell, mac
**conda** has to be removed or added in front of activate.

```bash
conda activate <env>
activate <env>
```

To update your existing envs to new dependencies added by other developers us:

```bash
activate <env>
conda env update --file <env>.yml
```

### Start Jupyter Notebook
If you want to run a jupyter notebook with this repository, please follow these steps:
1. Open a terminal
2. Activate your environment
3. Start jupyter notebook using this command
```bash
jupyter notebook
```

This should enable you to edit and run scripts in the browser with the packages you have installed in your environment

### Integrate into PyCharm
1. Open PyCharm and navigate to **File>Open**
2. Select the downloaded repository
3. Add the environments
    1. Navigate to **File>Settings>Project Interpreter**
    2. Click on the gear symbol on the top right and click **add**
    3. Select **Conda Enviroment** and **Existing environment**
    4. Add your envs. They are often located under
    ''C:\Users\xxxxx\AppData\Local\conda\envs\<envname>''
    or ''C:\Users\xxxxx\.conda\envs\<envname>''.
    If they are hidden files, you need to type the path manually into pycharm


# How to Setup a Jupyter Notebook

### Step 1. Create project folder

```
# syntax
mkdir <folder name>


# example
mkdir myproject
```

### Step 2. Create, activate & select your virtual environment

Navigate to / open your project folder and create a virtual environment inside of it:


```
# syntax
python3 -m venv <virtual environment name>

# example
# that would create a virtual environment named 'myenv'
python3 -m venv myenv
```

Now activate the virtual environment and when VS CODE prompts you to set it as default for the project, hit yes.

```
# syntax
source <virtual environment name>/bin/activate

# example
source myenv/bin/activate
```

### Step 3. Install ipykernel

```
pip3 install ipykernel
```

### Step 4. Create new kernel

```
# syntax
python3 -m ipykernel install --user --name=<projectname>


# example
# That would create a kernel named 'myproject'
python3 -m ipykernel install --user --name=myproject
```

### Step 5. Select kernel for project

Now you can assign the kernel to the project in VS CODE.

### Step 6.1: Create a new Jupyter notebook

* Open the VSCODE search bar: cmd+shift+p

* Type in & choose: “Create: New Jupyter Notebook”

### Step 6.2: Choose your kernel

* Open the VSCODE search bar: cmd+shift+p

* Type in & choose: “Notebook: Select Notebook Kernel”

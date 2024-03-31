## Getting Started
Create a virtual environment(venv) and install the necessary Python packages using the commands below! A virtual environment is essentially an isolated workspace that allows programmers to download python packages/dependencies that only apply to the directory the venv is created in. This is nice because different projects require different packages with different versions. Virtual environments let you download packages for one project without affecting your other projects.
* Pull up a terminal and create a venv using this command:
  ```sh
  $ python -m venv venv
  ```
* Activate the venv -- after running this command, you should see (venv) next to your terminal prompts:
  ```sh
  $ source venv/bin/activate
  ```
* Install the requirements listed in `requirements.txt`! Every python project typically has a `requirements.txt` file that lists all the dependencies for that project. The following command will install every package listed in the `requirements.txt` file using `pip`, a common python package installer/manager:
  ```sh
  $ pip install -r requirements.txt
  ```
* Side note: Likewise, you can uninstall every requirement in `requirements.txt` with
  ```sh
  $ pip uninstall -r requirements.txt
  ```
* Side note 2: To leave the venv, just type `deactivate` in the terminal. You should no longer see (venv) next to your terminal prompt.

Now you should be good to run the Jupyter Notebook! If you need to start from the beginning of all this, just `deactivate` the venv and and delete the `venv/` directory.

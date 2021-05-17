# Creating an isolated Environment

Working in an isolated environment is strongly recommended so that you can work on different projects without conflicting library versions. 

Install **virtualenv** by running following pip command.

If you want to install virtualenv for all users on your machine, remove `--user` and run this command with administrative rights.

`python3 -m pip install --user -U virtualenv`

Now you can create an isolated Python environment by typing this:

`cd $path`

`python3 -m virtualenv myenv`

Now everytime you want to activate this environment, juts open terminal and type the following:

`cd $path`

`source myenv/bin/activate # on Linux or macOS`

`.\myenv\Scripts\activate # on Windows`


# Using the LSST DM Stack from Python

The Jupyter Notebook in this repository is a self-guided tutorial that walks the reader through writing a simple processing script using LSST Data Management Python libraries.


If you're participating at an DM-hosted event for this prupose, you can use a JupyterLab environment (a technology we're considering as a major component for the LSST Science Platform) we've set up for the meeting.  To do so, request membership in the [`lsst-dm-tutorial` GitHub organization](https://github.com/lsst-dm-tutorial) -- you may need to have one our organizers confirm your identity if your GitHub account isn't one we recognize.  This may not be available until Tuesday.

You should then be able to log into https://tutorial.lsst.codes, using your GitHub credentials.  Once there, start a server, spawn an environment (use Weekly 2018_01 or whatever the most recent weekly option offered is), and open a terminal (File->New->Terminal).  

Then in your terminal:

```
cd notebooks
git clone https://github.com/lsst-dm-tutorial/lsst2017.git
```

The tutorial folder and notebook should appear in the `Files` tab of the interface, and you can double-click on it to launch it in a Python kernel with the LSST DM Stack already setup. Note: the tutorial asks you to fix some things as a learning exercise. If you are impatient and just want to turn to the solution in the back of the book, check out the 'answers' branch after doing the above:

```
git checkout answers
```
That will run through with no errors (there are some warnings you can ignore, they will be addressed soon)

**IMPORTANT: When you are not actually working on the tutorial, please release resources for other users by using the menu to save and exit the JupyterLab environment (File->Save All Exit and Logout) and CLOSE YOUR BROWSER TAB when instructed.  The next time you log in, the notebook cells you've worked through will have to be re-executed, but otherwise everything should be as you left it.**

It also should be possible to run the tutorial notebook on any system on which the LSST stack (version `w_2018_01` is recommended) has been installed.  Instructions for installing the stack can be found at http://pipelines.lsst.io.

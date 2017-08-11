# Using the LSST DM Stack from Python

The Jupyter Notebook in this repository is a self-guided tutorial that walks the reader through writing a simple processing script using LSST Data Management Python libraries.

If you are going through this tutorial at the LSST2017 Project and Community Workshop, you can drop by the DM Hack Room to find people who can help you with any questions you have.  The DM Hack Room will be running continuously during all parallel sessions, but we'd recommend you come during one of the sessions below to guarantee you can find someone who knows about the tutorial:

 - Monday 9:00am - 10:30am
 - Monday 11:00am - 12:30pm
 - Tuesday 1:30pm - 3:00pm
 - Wednesday 11:00am - 12:30pm
 - Thursday 11:00am - 12:30pm
 - Friday 11:00am - 12:30 pm
 - Friday 1:30pm - 3:00 pm
 - Friday 3:30pm - 5:00 pm

If you're at LSST2017, you can use a JupyterLab environment (a technology we're considering as a major component for the LSST Science Platform) we've set up for the meeting.  To do so, request membership in the [`lsst-dm-tutorial` GitHub organization](https://github.com/lsst-dm-tutorial) -- you may need to drop by the DM Hack Room to have one our organizers confirm your identity if your GitHub account isn't one we recognize.

You should then be able to log into https://tutorial.lsst.codes, using your GitHub credentials.  Once there, start a server, spawn an environment, and  open a terminal.  Then do:

```
cd notebooks
git clone https://github.com/lsst-dm-tutorial/lsst2017.git
```

The tutorial folder and notebook should appear in the `Files` tab of the interface, and you can double-click on it to launch it in a Python kernel with the LSST DM Stack already setup.

**IMPORTANT: When you are not actually working on the tutorial, please use the menu to save and exit the JupyterLab environment.  The next time you log in, the notebook cells you've worked through will have to be re-executed, but otherwise everything should be as you left it.**

It also should be possible to run the tutorial notebook on any system on which the LSST stack (version `w_2017_31` is recommended) has been installed.  Instructions for installing the stack can be found at http://pipelines.lsst.io.

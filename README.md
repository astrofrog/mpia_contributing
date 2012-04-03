We are going to try and contribute a patch to a fake project, 
'mpia_contributing' (feel free to actually do this, since the project is 
just set up for this purpose!). The instructions here are a simplified version of:

    http://astropy.readthedocs.org/en/latest/development/workflow/development_workflow_advanced.html

1. Make sure you are logged in to http://www.github.com.

2. Go to https://github.com/python4mpia/mpia_contributing

3. Click on the 'fork' button, and if it says 'Where do you want to fork this to?', select 'Fork to <username>' where <username> is your GitHub username

4. Once the 'Hardcore forking action' is complete, you should be presented with your fork of the project. Now clone the project:

    git clone https://astrofrog@github.com/<username>/mpia_contributing.git

5. Now, create a new branch and switch to it:

    cd mpia_contributing
    git branch my-new-feature
    git checkout my-new-feature

6. Hack away! For example, we can add a new file 'myscript.py' that we have just created:

    git add myscript.py

7. Commit the changes, and push to GitHub:

    git commit -m "Added a new script"
    git push origin my-new-feature

8. Go back to your fork on GitHub, and switch to your new branch, in this case 'my-new-branch'

9. Click on 'Pull Request' at the top right, and make sure that it says:

    'You're asking python4mpia to pull 1 commit into python4mpia:master from <username>:my-new-feature'

10. Add a description and explanation for the pull request, and then click on 'Files changed' to see the changs you are including in the pull request. Make sure you didn't include any unecessary files/edits by mistake!

11. Click 'send pull request' - done!


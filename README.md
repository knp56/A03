# A03

GIT - A version control system that allows you to make changes to exsiting codes and/or create codes.
  1. Click on https://git-scm.com/downloads
  2. Click on the device you plan on downloading GIT on and then download GIT
  3. It will bring you to another website and so you click download once more
  4. Once it is downloaded, install it into your device 
  5. Once installed, link GIT with GITHUB and then it is ready to be used


GITHUB - Github is used in partnership with GIT. You write the code on GIT and Github allows you to store your project and networks with people.
  1. Go on www.github.com
  2. Create a profile and then wait until you link your GIT with GITHUB
  
  
Repository - primarily used to organize a single project and may contain folders, files, images, videos, data sets and spreadsheets
  1. Click on the (+) icon next to your avatar and click NEW REPOSITORY.
  2. Name your repository.
  3. Write a description if you choose to do so (it is not mandatory).
  4. Click INITALIZE THIS REPOSITORY WITH A README.
  5. Click CREATE REPOSITORY. 


Clone - local copy on your computer that can be synced within two locations.
  1. Find the main page of the Repository.
  2. Click CLONE OR DOWNLOAD which should be located under the repository name.
  3. Copy the clone URL.
  4. Open terminal.
  5. Change the current working directory to your desired location for the clone.
  6. Type git clone followed by the URL from part 3.
  7. Press enter.

Commit - saved changes and commit message describes why you made the change.
  1. Click README.md file.
  2. On the upper right corner of the file there should be pencil icon, click that to edit.
  3. Write something in the editor.
  4. Then write a commit message that explains the changes you made.
  5. Click COMMIT CHANGES.

Push - moving commits made on the local branch to the remote repository.
  1. Type GIT PUSH <rREMOTENAME> <BRANCHNAME>

Pull - Allows you and the main project's maintainer to communicate. Therefore, allowing them to see revisions you have made and potentially be apart of the offical/new project/repository by putting in the pull request.
  1. Click PULL REQUEST tab and then click the green NEW PULL REQUEST button.
  2. Once you see the EXAMPLE COMPARISONS box, click on the branch you created.
  3. Look through and revise the changes on the compare page.
  4. When satisfied, click CREATE PULL REQUEST.
  5. Name and descirbe your pull request.

Branch - Working on different versions of a repository simutaneously
  1. Click on your new repository.
  2. Search for the file list that says BRANCH:master and click on the drop down located at the top of the file.
  3. Type in the branch name where it says new branch text box.
  4. Click CREATE BRANCH.

Merge - Combining the changes (readme-edits with master branch)
  1. Click on MERGE PULL REQUEST.
  2. Click CONFIRM MERGE.
  3. Click on DELETE BRANCH since the changes successfully went through. 

Merge Conflict - If you have competing commits the branches will merge due to the fact that GIT does not know which one to actually implement.
  1. Click PULL REQUEST under the repository name.
  2. Then click the pull request with the merge conflict that is to be solved.
  3. Click RESOLVE CONFLICTS.
  4. Decide the final changes being made, which branch keeps what.
  5. Once solved click COMMIT MERGE, merging all branches into the head branch.
  6. Then if completely sure, click I UNDERSTAND, UPDATE BRANCH.
  7. Finally, click MERGE PULL REQUEST.

Fetch - Recieve new work from other people without merging.
  1. Type in $ git fetch <repository_name_here> in the terminal

Remote - Storing your code.
  1. Type GIT REMOTE ADD command to get the remote URL with the name.

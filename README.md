# Hi Violet!

## Steps to the Git workflow after someone has written some finalized code:
- Note: You should only be doing this if you can confirm that your code is error / bug-free. 
- Note: You do not need to fork this project repo - everyone will be working out of the same repo. 

- Step 1: Make a new branch for yourself. 
- Step 2: Add, commit, and push the work to Github 
    - Note: REMEMBER to upload your code ONLY to your specific branch. 
    - NEVER UPLOAD DIRECTLY TO THE MAIN / MASTER / DEFAULT BRANCH
- Step 3: When you are confident that your code is ready to be finalized and merged with the main / master / default branch, follow these steps:
    - a: Go to the "pull requests" tab in the homepage of the repo 
    - b: Click on where it says "new pull request"
    - c: You will be taken to a page called "Compare Changes". There will be 2 dropdown menus. Make sure that the left dropdown menu is set to your main / master / default branch, and the right-hand branch is set to your personal branch where you were writing your code drafts. 
    - d: If you did not make a merge conflict or other git error, it will say in green "Able to merge". You will now click "create pull request". 
    - e: You will be taken to a new page where you can enter in comments about the code that you've written. Write a description of the code you've built. Once you've written some comments, click "Create Pull Request"
    - f: After you click "Create Pull Request", you will be taken to a window where it will list out all the commits getting merged to the main/master/default branch AND give you the option to approve the merge. 
        - Note: You should only do this step when you have ALL group members present and able to look over your code that you are getting ready to merge. 
            - If the code looks fine, then you can click "Merge Pull Request" and click through to approve it. 
            - If the code is NOT ready, then the dev who is trying to merge will go back and fix their code. The pull request will be denied. 
- Step 4: Once the merge request has been finalized and the default/main/master branch has been updated with that dev's code, that dev who made the merge request will go to their local repo and `git pull origin main` to update their local main branch with the finalized code. 
    - Note: All other group members, once the merge request has been finalized, should ALSO go to their local main/master/default branch and `git pull origin main` to update their codebase. 
    - NOTE!!!!!!!!!!!!!!!!!!!! ALWAYS CHECK WHEN YOU ARE DOING THIS STEP THAT YOU ARE IN FACT ON YOUR LOCAL MAIN BRANCH AND NOT ON YOUR PERSONAL BRANCH. IF YOU ACCIDENTALLY UPDATE YOUR PERSONAL BRANCH, YOU WILL HAVE TO REVERT THE COMMIT. 
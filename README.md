# background-generator -------

- ``` git clone < github repository HTTP >``` 
- ``` git status ``` // to find the status of the project files
- ``` git add <filename> ```   // to allow for all update files to to be added to the got  repository
- ``` git add .  ```//to add multiple  file at the same time.
- ``` git commit -m" comment " ``` /// to commit the changes 
- ``` git push origin main ``` // to push the code on my computer to the github repository
- ``` git pull ```// to get the updated version of the code from the github repository to the computer
 
 
# Keeping Your Fork Up To Date

- ```git remote -v ``` and press Enter. You'll see the current configured remote repository for your fork.
- ``` git remote add upstream ```, and then paste the URL you would copy from the original repository if you were to do a git clone. Press Enter.
- To verify the new upstream repository you've specified for your fork, type ``` git remote -v ``` again. You should see the URL for your fork as origin, and the URL for the original repository as upstream.
- Now, you can keep your fork synced with the upstream repository with a few Git commands.   One simple way is to do the below command from the master of your forked repository: 
- ``` git pull upstream master ```
 
  


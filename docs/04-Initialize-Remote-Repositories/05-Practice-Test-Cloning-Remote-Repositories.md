

Solutions to practice test - cloning remote repositories
- Run cd /home/max; git clone http://git.example.com/nadeem/ui-repo.git
  
  <details>
  
  ```
  $ cd /home/max
  $ git clone http://git.example.com/nadeem/ui-repo.git
  ```
  
  </details>
  
- Check the contents of the cloned repository. Confirm that you can see nadeem's story and history of commit by running git log and validate author info, commit message etc.

  <details>
  
  ```
  $ cd /home/max
  $ git log
  ```
  
  </details>

- Max has written his story about The 🦊 frontend test 🍇 View the file he created and its contents. You may read the story if you wish to. But don't spend all day 😝 

  <details>
  
  ```
  $ cd /home/max
  $ cat frontend-test.txt
  ```
  
  </details>
  
 - Run git add frontend-test.txt and then git commit -m 'Added frontend-test story'

  <details>
  
  ```
  $ cd /home/nadeem
  $ git add frontend-test
  $ git config user.email "nadeem@example.com"
  $ git config user.name "nadeem"
  ```
  
  </details>

- Run the git remote -v command to check the remote repository
  
  <details>
  
  ```
  $ git remote -v
  ```
  
  </details>
  
- Run git push origin master
  
  <details>
  
  ```
  $ cd /home/max
  $ git push origin master
  ```
  
  </details>
  
- The account owner - nadeem needs to add you as a collaborator. While logged in to the Gitea UI as user nadeem go to Settings -> Collaborators of the project and add max as collaborate with Write permissions.
  
  <details>
  
  ```
  From GUI --> Repositories --> nadeem/ui-repo --> settings --> collaborators
  ```
  
  </details>
  

- Simply run git push origin master to push and input login credentials
  
  <details>
  
  ```
  $ cd /home/max
  $ git push origin master
  ```
  
  </details>

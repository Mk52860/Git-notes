
    
 Solutions to practice test - merging branches
 - Run cd /home/nadeem/ui-repo; git checkout master and then list the files ls
    
   <details>
    
   ```
   $ cd /home/nadeem/ui-repo
   $ git checkout master
   $ ls
   ```
   
   </details>
   
- Run cd /home/nadeem/ui-repo and then list the files ls

  <details>

  ```
  $ cd /home/nadeem/ui-repo
  $ ls
  ```
  </details>
  
- Run git branch
    
  <details>
  
  ```
  $ git branch
  ```
  
  </details>
    
- Run git log

  <details>
  
  ```
  $ git checkout master
  $ git log
  $ git checkout database-test
  $ git log
  ```
  
  </details>

- Run git merge database-test. Check git log now and it should show commit message as Merge branch 'database-test' into master

  <details>
  
  ```
  $ git checkout master
  $ git merge database-test
  $ git log
  ```
  
  </details>
  
- List the files in the master branch and make sure both the stories are visible.
  
  <details>
  
  ```
  $ ls
  ```
  
  </details>

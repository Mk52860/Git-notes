
  
Solutions to practice test - Branches
- Refer the previous lecture, Branch is nothing but a pointer to a specific commit in GIT
  
  <details>
  
  ```
  Pointer to a specific commit in git
  ```
  
  </details>
  
- By default the branch used is master
  
- Simply run cd /home/nadeem/ui-repo; git log --name-only
  
  <details>
  
  ```
  $ cd /home/nadeem/ui-repo
  $ git log --name-only
  ```
  
  </details>
  
- Check branch in the git log --decorate output

  <details>
  
  ```
  $ git log --decorate
  ```
  
  </details>
  
- Run git checkout -b database-test

  <details>
  
  ```
  $ git checkout -b database-test
  ```
  
  </details>
  
- Check branch HEAD pointer in git log output

  <details>
  
  ```
  $ git log
  ```
  
  </details>

- Run git add database-test.txt; git commit -am 'Add incomplete database-test story'

  <details>
  
  ```
  $ git add database-test.txt
  $ git commit -am 'Add incomplete database-test story'
  ```
  
  </details>

- Run git checkout master

 <details>
  
  ```
  $ git checkout master
  ```
  
  </details>

- Use vi editor to edit the file and fix the typo. Then run the command git commit -am 'Fix typo in story title' 

  <details>
  
  ```
  $ git commit -am 'Fix typo in story title'
  ```
  
  </details>

- Run the command git checkout database-test

  <details>
  
  ```
  $ git checkout database-test
  ```
  
  </details>

- Run the command git commit -am 'Completed database-test story'

  <details>
  
  ```
  $ git commit -am 'Completed database-test story'
  ```
  
  </details>

- Change to directory cd /home/nadeem/website and run git branch command

  <details>
  
  ```
  $ cd /home/nadeem/website
  $ git branch
  ```
  
  </details>

- Checkout to directory git checkout feature/signout; git log --graph --decorate

  <details>
  
  ```
  $ git checkout feature/signout
  $ git log --graph --decorate
  ```
  
  </details>

- Checkout to directory git checkout feature/signout; git log --graph --decorate

  <details>
  
  ```
  $ git checkout feature/signout
  $ git log --graph --decorate
  ```



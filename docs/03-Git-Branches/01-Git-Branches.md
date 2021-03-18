
 
In this section, we will take a look at git branches

## Branches
- Keep project versioned using branch
- A branch is basically a pointer to the last commit
  
  ![gitb1](../../images/gitb1.PNG)
  
- If you are working on a feature, you might work on a feature branch (eg. feature/signup), once the features are tested, you can merge to master branch

  ![gitb2](../../images/gitb2.PNG)
  
- To create a new branch
  ```
  $ git branch nadeem
  ```
  
- To create a new branch and switch to it
  ```
  $ git checkout -b nadeem
  ```
  
- To list of all of our branches
  ```
  $ git branch
  ```
  
  ![gitb3](../../images/gitb3.PNG)
  
- Switch to exisiting branch
  ```
  $ git checkout nadeem
  ```

- Delete a branch
  ```
  $ git branch -d max
  ```
  
  

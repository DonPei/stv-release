## STV

The project has been designed for **Seiemic Tracedisplay View** 


### Git Commands

1. Clone the project:

 ```bash
   # clone it 
   git clone git@github.com:DonPei/stv-release.git stv-release
   ```

   You should be prompted for username and password. Alternatively you could set up username and password in global configuration.

2. Change directory to your working folder:

  ```
   cd ${working_folder}
   ```

3. Check out the `develop` branch and get the latest:

  ```
   git checkout develop
   git pull
   ```

4. Check status of branch (should be up-to-date with `'origin/develop'` with nothing to comit, working directory clean):

  ```
   git status
   ```

5. Create your feature branch

   Use the below naming convention for your feature branch, and ensure that yor branch is based off the `develop` branch:

  ```
   git checkout -b [feature]/[JIRA-ID]-[storyname]-[short-description]
   ```

6. Develop the story or fix.

7. Check your changes:

  ```
   git status
   ```

   The above command should show all that is modified, use the add command to add it to your local git repo:

   ```
   git add .
   ```

8. Commit changes frequently and incrementally, so as to maintain a clear log of what was changed. Always commit your changes with a clear and concise message:

  ```
   git commit -m "Example message that explains what changes were made."
   ```

9. Push your local branch to the remote branch:

   ```
   git push --set-upstream origin [your-feature-branch]
   ```

## How to build

To build all the modules run in the project root directory the following command with Maven 3:

```
mvn clean install
```

## Testing

There are three levels of testing contained in the project:

unit test in core: this show-cases classic unit testing of the code contained in the bundle. To test, execute:

```
mvn clean test
```

### TO DO

- Junit test cases
- More custom component examples

## Reference Content

TBD.



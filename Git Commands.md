
# Step-by-Step Guide to Basic Git Commands

If you're new to Git, here’s a simple guide to help you get started with version control. Below are the step-by-step Git commands that you can follow to create, manage, and commit files to a Git repository.

## 1. Create a new directory for your project
First, let's create a directory where your project files will be stored.

```bash
mkdir git-for-devops
```

## 2. Navigate to the project directory
Use the following command to move into the new directory.

```bash
cd git-for-devops/
```

## 3. List the contents of the directory
To check if the directory is empty (or what files are inside), run:

```bash
ls
```

## 4. Display your current working directory
You can check where you are located in your file system by running:

```bash
pwd
```

## 5. Create and edit a new file
Let’s create a text file named `hello-dosto.txt`. You can edit it using `vim`.

```bash
vim hello-dosto.txt
```

## 6. View the contents of your file
After editing, you can check the contents of your file with:

```bash
cat hello-dosto.txt
```

## 7. Initialize a new Git repository
Now, initialize a new Git repository within your project directory:

```bash
git init
```

## 8. List all files (including hidden ones)
To see all files, including hidden ones like `.git`:

```bash
ls -a
```

## 9. Check the current status of your repository
To see the status of your working directory, use:

```bash
git status
```

## 10. Clear the terminal
To clean up your terminal screen:

```bash
clear
```

## 11. Create and edit more files
Let’s add some more files to our project:

```bash
vim a.txt
vim b.txt
```

## 12. Add files to the staging area
You can stage all changes or select specific files to add to Git:

- Stage all files:
  ```bash
  git add .
  ```

- Stage a specific file:
  ```bash
  git add a.txt
  ```

## 13. Remove a file from the staging area
If you’ve added a file by mistake, you can unstage it with:

```bash
git rm --cached a.txt
```

## 14. Commit your changes
Once your files are staged, commit them with a message:

```bash
git commit -m "added files"
```

## 15. Configure Git settings (optional)
If needed, you can configure Git settings using:

```bash
git config
```

## 16. View the current Git configuration
To see the current Git configuration settings, use:

```bash
config --list
```

## 17. Show detailed configuration with origin
To view the configuration settings with origin details:

```bash
config --list --show-orogin
```

## 18. Restore uncommitted changes
To discard changes that have not been committed yet:

```bash
git restore
```

## 19. Make additional commits
Whenever you make new changes, don’t forget to commit them:

```bash
git commit -m "new changes in files"
```

## 20. View the commit history
To see a log of all commits made to the repository:

```bash
git log
```

---

### Conclusion
These are the basic Git commands you can follow to manage files and track changes in a project. Version control with Git helps in keeping your work organized and trackable. Happy coding!

# Exercise README

This exercise is designed to help you practice basic Git commands by creating a repository locally on your machine and pushing it to GitHub. Follow the steps below to complete the exercise:

1. **Create a new repository locally on your machine:**
   - Initialize a new Git repository in your desired directory using the command `git init`.

2. **Create a new GitHub repository:**
   - Go to [GitHub](https://github.com/) and create a new repository. Name it whatever you want.

3. **Connect your local repo to the GitHub repo:**
   - Add the remote repository URL using the command `git remote add origin <repository_url>`.

4. **Optional: rename the default branch from master to main:**
   - If you prefer to use the `main` branch as the default, rename it using the command `git branch -m main`.

5. **Make a new file called `favorites.txt`:**
   - Create an empty file named `favorites.txt` in your local repository. Add and commit this file to the `main` branch.

6. **Push up your `main` branch to GitHub:**
   - Use the command `git push -u origin main` to push your changes to the `main` branch on GitHub.

7. **Create two branches: `foods` and `movies`:**
   - Create two new branches using the commands `git checkout -b foods` and `git checkout -b movies`.

8. **Switch to the `foods` branch:**
   - Use the command `git checkout foods` to switch to the `foods` branch. Add three or more of your favorite foods to the `favorites.txt` file. Add and commit your changes on the `foods` branch.

9. **Switch to the `movies` branch:**
   - Use the command `git checkout movies` to switch to the `movies` branch. Add three or more of your favorite movies to the `favorites.txt` file. Add and commit your changes on the `movies` branch.

10. **Push up your `foods` branch to GitHub:**
    - Push the `foods` branch to GitHub using the command `git push origin foods`.

11. **Push up your `movies` branch to GitHub:**
    - Push the `movies` branch to GitHub using the command `git push origin movies`.

12. **Merge the `foods` and `movies` branches into the `main` branch:**
    - Switch to the `main` branch using the command `git checkout main`.
    - Merge the `foods` branch into the `main` branch using the command `git merge foods`.
    - Merge the `movies` branch into the `main` branch using the command `git merge movies`.
    - Resolve any conflicts if necessary.

13. **Push up the latest work on your `main` branch to GitHub:**
    - Push the changes on the `main` branch to GitHub using the command `git push origin main`.

Congratulations! You have completed the exercise. Your `favorites.txt` file on GitHub should now contain your favorite foods and movies.

# First-Contributions

#### Read this in your preferred language:

<kbd>[Hindi](translations/Translations.md)</kbd>
<kbd>[Gujarati](translations/README.gu.md)</kbd>
<kbd>[Punjabi](translations/README.pa.md)</kbd>
<kbd>[Kannada](translations/README.kn.md)</kbd>
<kbd>[Marathi](translations/README.mr.md)</kbd>
<kbd>[Odia](translations/README.or.md)</kbd>
<kbd>[Tamil](translations/README.ta.md)</kbd>
<kbd>[Telugu](translations/README.te.md)</kbd>
<kbd>[Marwari](translations/README.mw.md)</kbd>


This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

### If you don't have git on your machine, [install it](https://git-scm.com/downloads).

# Forking:

- Forking refers to creating a copy of a repository on GitHub under your own GitHub account.
- Forking is typically done when you want to contribute to someone else's project or experiment with changes without affecting the original project.
- When you fork a repository, you have your own separate copy of the project that you can modify independently.

# Cloning:

- Cloning refers to creating a local copy of a repository on your own computer.
- When you clone a repository, you download the entire repository, including all its files, commit history, and branches, to your local machine.
- Cloning allows you to work on the project locally, make changes, and then push those changes back to the remote repository (usually on GitHub).



# Forking and Cloning Repositories

# Forking a Repository

### 1. Create a Fork
   - To create a fork of a repository on GitHub, navigate to the repository's page and click the "Fork" button in the upper right corner.
   - This action creates a copy of the repository under your GitHub account.

### 2. Clone Forked Repository
   - After forking, clone the forked repository to your local machine using the `git clone` command followed by the URL of your forked repository.
   - Example: 
     ```
     git clone https://github.com/your-username/forked-repository.git
     ```

### 3. Configure Remote
   - By default, Git names the remote pointing to the original repository as `origin`. You need to configure a new remote pointing to your fork.
   - Navigate into the cloned repository directory:
     ```
     cd forked-repository
     ```
   - Add a new remote named `origin` pointing to your forked repository:
     ```
     git remote add origin https://github.com/your-username/forked-repository.git
     ```

# Cloning a Repository

### 1. Clone Repository
   - To clone a repository from GitHub to your local machine, use the `git clone` command followed by the URL of the repository.
   - Example:
     ```
     git clone https://github.com/original-owner/original-repository.git
     ```

### 2. Navigate into Cloned Repository
   - Once cloned, navigate into the directory of the cloned repository using the `cd` command.
   - Example:
     ```
     cd original-repository
     ```

### 3. Configure Remote (Optional)
   - By default, Git sets the remote name as `origin`. You can directly work with this remote if you want to push changes to the original repository.
   - If you want to push changes to your own fork, you may configure a new remote pointing to your forked repository as described in the forking section.



# Additional Information

Here are a few additional tips and resources to help you make meaningful contributions to open-source projects:

1. **Understanding the Project**: Take time to understand the project's structure, guidelines, and contribution policies.

2. **Communication**: Reach out to project maintainers or the community if you have questions or need clarification.

3. **Follow Contribution Guidelines**: Adhere to contribution guidelines to ensure smooth acceptance of your contributions.

4. **Testing and Quality Assurance**: Test your changes thoroughly before submission to maintain project quality.

5. **Submit Pull Requests**: Provide clear descriptions and be open to feedback during the pull request process.

6. **Review and Iteration**: Engage in the review process and be responsive to feedback for continuous improvement.

7. **Celebrate Your Contributions**: Take pride in your accomplishments and contributions to the open-source community.

By following these practices, you can become an effective collaborator and make meaningful contributions to open-source projects.

---

## Where to go from here?


You can also create a new branch in your forked repository to work on new features or bug fixes without affecting the main branch. This allows you to isolate your changes until they are ready to be merged into the main project.

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

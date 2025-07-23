# Assignment Logistics

- We will use [GitHub Classroom](https://classroom.github.com/classrooms) for assignments in this course

- Why?

  1. Gain experience using industry-standard tools like Git and GitHub, preparing you for professional environments
  2. Get better feedback on your work via automated actions and manual review
  3. Collaborate more effectively with your fellow students, mirroring real-world software development team interactions and workflows
  4. Reap the benefits of version-control, including rollbacks, diffs, branches, etc.

- What is it?

  - [GitHub](http://www.github.com): a web-based platform which stores your content (code, documents, media, etc.) in named **repositories (repos)** and facilitates version-control, workflows, collaboration, etc.
  - [GitHub Classroom](https://classroom.github.com/classrooms): a tool that facilitates managing course assignments using GitHub repos
  - [Git](https://git-scm.com): a distributed version control system which enables tracking code/content changes in a repo as atomic commits

## Your Workflow

### 1. Accept The Assignment

  1. I'll distribute each assignment on the course Canvas as a link of the form https://classroom.github.com/a/blahblah
  2. When you go to the assignment link in your browser:
     1. If you're not signed into GitHub it will ask you to **sign in** or create an account
     
     2. If you don't have a GitHub account, **sign up** for a free account
        - I also recommend applying for a free **Student Developer Pack** that unlocks premium functionality at no cost to students
     3. After you sign in to GitHub
        1. If this is you first assignment in the course, it will ask you to join the course's GitHub Classroom and to **link your GitHub account** to the your student identifier (i.e. name, ID, or email)
        2. If you haven't previously accepted this assignment, it will ask you to **accept the assignment**
           1. Once you accept the assignment, you'll be granted access to your own **new GitHub repo** for the assignment (containing instructions, starter code, scaffolding, etc.)

### 2. Clone It

1. If you don't have **Git** installed on your computer, follow the instructions [here](./install-git.md) to install and configure it
2. **Clone** your private GitHub repo for the assignment to your computer, following the instructions [here](./git-clone.md)

### 3. Modify and Push

1. Follow the assignment instructions in the **README.md** file in your local repo

2. Modify/add files as needed/instructed

3. Commit your changes locally using the following commands (this only adds a version to your local version control and does not push the changes to GitHub)

   ```bash
   git add .
   git commit -m "Short, clear description of the changes e.g. implemented Counter methods"
   ```

4. Push your committed local changes to the GitHub repo using the following command

   ```bash
   git push
   ```

   > [!IMPORTANT]
   >
   > You must  `git push`. Otherwise your changes will be local to your system and I won't be able to see your changes in GitHub.

   - Some assignments will have automated actions (e.g. run tests) on GitHub that will run every time you push. Check the 'Actions' tab on your GitHub repo to see the status of those runs

   

> [!TIP]
>
> Commit and push changes frequently e.g. after completing a logical unit of work



> [!NOTE]
>
> If you're not familiar with version-control or Git, no worries. For now just follow the instructions here. If it makes sense for the course, I'll cover version control in class. If that's not relevant for the course, you just need to know what's in these instructions so that you can execute the assignment workflow.

## Grading

- I'll grade the assignment **only after the deadline** passes
  - So don't worry about pushing changes frequently before the deadline
  - Also, if you need **help before the deadline**, reach out to me and I'll take a look at your current version pushed to GitHub
- For grading, I'll use the latest version that you pushed to your GitHub repo
- I'll provide **inline comments** on your work using the GitHub Pull Request (PR) mechanism
  - If you're not familiar with PRs, no worries. All you need to know is that you'll receive an email with my feedback on your assignment
- I'll score your assignment in Canvas

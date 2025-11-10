# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.

### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
Complete this section with details from your setup:
- Repository URL: ...
- Output of `git remote -v`:
- The output of `git log --oneline`:

### Reflections

Q1) 

a)

Before this assignment, I was already using Git and Github for my code and just using semantic strings for different versions of my documents. But before I was using Git and Github I just used semantic strings for code as well and had a bunch of different code files and it became very confusing. One specific advantage of Git is that it provides you with an easy way to develop a large project such as a large coedebase where multiple versions are created and it allows you to pull them all together in a way that is easy and minimizes manual labor. Another advantage of Git is that you can have multiple people all working on the same codebase and all contributing in an organized way which is paramount in industry where teams are large and codebases are even bigger. 

b) The biggest case in my profesional career where Git's commit history became useful was during my first co-op where I developed a python-based downtime tracker desktop app and my boss would review my code and make changes himself. My boss would make changes to my codebase and also give me feedback on why he made those changes and that was very efficient to do in Git / Github. This solves the problem of just sending code back and forth like in an email and streamlines efficiency. 

Q2)

a) It is important to keep the class_repo and my_repo seperate because the class_repo is a resource for the entire class and my_repo is just my work so the entire class does not need to see the work that I do and this also allows for the entire class to have a common "base" where they pull resources from that is not convoluted by other peoples work. If everything was put into one repository then it would get very confusing because all resources from the class (relevant or not) would be combined into one place along with my own work and answers (relevant or not) - so there would be a lot of extra files that are uneeded and keeping therm seperate is a way to isolate what is important and what is not along with what is relevant and what is not. 

b) In my future coursework (assuming my group / classmates are familiar and competent with Git) I will use git to handle group project work but only if it involves code and a entire codebase is needed for a project. I still believe that using something like Box is an easier way to organize resources like documents but for a project that requires code I will not use Git to organize all of the work (assuming my group is competent and merging other peoples work does not lead to more problems).

Q3) 

a) The second commit message "Add hw3a solution documenting Git workflow and repository structure" is significantly more useful than just "update". The more detailed message tells you exactly what was added (hw3a solution) and what it contains (Git workflow and repository structure documentation). Other developers (or yourself in the future) can understand what changed without having to examine the actual file changes. It is also more professional. 
One might need this again when needing to find your Git workflow notes.

b) After completing a logical unit of analysis (finishing data cleaning, completing exploratory analysis, building a model). When I've successfully implemented a new feature or function that works
Before starting a major change or experimental approach

### Graduate Questions

q1) 

a) It was valuabe to commit the README and .gitignore together and the hw3a-solution.md seperately because this allows for a more clear project history and also allows for an easier rollback if issues arise. Context and clarity would be lost if this was not done. 

b) You should commit the "Write code to load data" , "fix a typo in a comment" and "update README" immediately and wait on the new analysis. This is because you should only commit things that are finished to the main branch as it is good practice. The staging area helps you experiment without commiting to the main branch. 

c) Git status helps make decisions about whaty to stage and commit by showing the current labeled state of files which you can use to help guide your next action (like commit or work on more / finish). You should use it in your workflow when you are starting work , making changes and when you are ready to commit. 

q2) 

a) Git is “distributed” because every clone (class_repo) contains the entire project history and can commit, branch, and inspect locally without talking to any server. You only interact with others when you choose to push or pull, so work continues even offline and different clones can evolve independently. Google drive and Dropbox do not have this feature and a single project will all evolve as people work on it. 

b) The workflow described is valuable because it can enable developers to work anywhere (not just a place with good internet connection) and continue to contribute to a project and this also allows for experimentation and compartmentilization of work. 

c) Git clone copies an entire repo which includes all supporting files and history. git pull fetches new commits and merges them into your local branches so you stay up to date. git push does the opposite, it sends your local commits back to a remote branch once you have permission. You can pull from class_repo because we have read access so everyone can clone or fetch updates. They block pushes to keep that canonical repo under their control, so your credentials don’t have write permission. Your my_repo is your own remote (or one where you have write access), so after cloning you can both pull updates and push your work back up, letting you synchronize your personal copy with the remote service.

q3) 

a) Before deciding to commit you should decide if your work is complete and polished enough to be committed to the repo. I will commit when I make large enough changes to the repo and/or small fixes to something that I know I want to keep that way I can keep track of my work but it will not get overly complicated. 

b) A README for a personal repo is going to consist of less than a README for an open-source repo. An open-source repo will consist of a lot more such as a template for commit messages and a template for push requests and contain more "in the weeds" documentation while a README for a personal portfolio will just consist of highlights and how to read the repo at a high level. 

c) I will consider adding more work to this portfolio later on to highlight my skills and abilities so that employers will look at. 



What is Git?

Git is a Distributed Version Control System (DVCS) used to track changes in source code during software development.

In simple words:

It keeps a history of all code changes.

It allows multiple people to work together without overwriting each other’s work.

It helps you roll back to previous versions if something breaks.

It works offline, and code history is stored on every developer’s machine.

Git was created by Linus Torvalds (creator of Linux) in 2005.



Why Do We Use Git? (Uses of Git)

1️⃣ Version control

Git tracks every change made to your files.
You can always go back to a previous working version.

2️⃣ Collaboration

Many developers can work on the same project at the same time without conflicts.

3️⃣ Branching & merging

You can create separate branches for:

New features

Bug fixes

Experiments

Then merge them back into the main code.

Git makes branching fast & lightweight.

4️⃣ Backup

Because every developer has a full copy, it’s almost impossible to lose the code.

5️⃣ Continuous Integration / Deployment

Tools like Jenkins, GitHub Actions, GitLab CI/CD work directly with Git.

6️⃣ Open-source contribution

Most open-source projects use Git and GitHub/GitLab/Bitbucket.

✅ Git Architecture (Very Simple Understanding)
Repo Type	Meaning
✅ Git Architecture (Very Simple Understanding)
Repo Type	Meaning
Local Repository	On your laptop
Remote Repository	On GitHub/GitLab/Bitbucket

You commit changes locally → then push to remote.

🔁 Alternatives to Git

Git is the most used system today, but there are other Version Control Systems too:

⭐ 1. Subversion (SVN)

Centralized Version Control System (CVCS)

Old but still used by some enterprises

Not distributed like Git

⭐ 2. Mercurial

Also a distributed version control system

Similar to Git but simpler

Used by companies like Mozilla (previously)

⭐ 3. Perforce (Helix Core)

Used heavily in gaming & large enterprises

Very good for large binary files

Fast, scalable

⭐ 4. CVS (Concurrent Versioning System)

Very old; used before SVN

Not common now

⭐ 5. IBM ClearCase

Enterprise-level, used in big corporations

Heavy and complex system

🥇 Which is best?

Git is the industry standard because:

Free & open-source

Distributed

Fast

Used by 95% of companies

Best community support
Local Repository	On your laptop
Remote Repository	On GitHub/GitLab/Bitbucket
You commit changes locally → then push to remote.


What is a Repository?

A repository (repo) is a storage space where your project’s files + full version history are stored.

In simple words:

A repository is a folder for your project that also tracks all code changes.

It contains:

Source code

Commit history

Branches

Tags

Config files

✅ Is it called a Git repository or GitHub repository?
✔️ Both terms are correct — but they mean different things.
🔹 1. Git Repository (Local Repository)

Stored on your computer.

Created with:

git init


It contains:

.git folder

Your commits

Your branches

Staging area

This is local version control.

🔹 2. GitHub Repository (Remote Repository)

Stored on GitHub’s cloud servers.

Created on GitHub website.

It is a remote copy of your project used for:

Collaboration

Backup

Pull Requests

CI/CD

Team access

You connect your local repo to GitHub using:

git remote add origin <url>
git push -u origin main

🧠 Simple way to remember
Term	Meaning
Git Repository	Exists on your laptop (local)
GitHub Repository	Exists on GitHub cloud (remote)

################# **Step-by-Step Guide to Learn Git** ###########################

STEP 1: Configure Git (very important)

Run these commands once:

git config --global user.name "Your Name"

git config --global user.email "your@email.com"

Git uses this info to track who made changes.

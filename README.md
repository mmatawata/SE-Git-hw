# SE-Git-hw

Repository was created for CINS 5318 Software Engineering Git/ GitHub assignment. Demonstrates repository creation, commits, branches, pull requests, collaboration, issue tracking, and merge-conflict resolution.



\*\* Project Files

hello.py — Prints Hello World message. I later modified during merge-conflict exercise.

apple.py — Prints I eat apple.



\*\* Running the Programs



Python must be installed. From the repository folder, run:



py hello.py

py apple.py



\*\* Branch and Pull Request Workflow



The feature-1 branch was created to develop apple.py separately from the main branch. After the program was tested, the file was committed and pushed to GitHub. Pull Request #1 was created to propose merging the feature into main. A classmate reviewed the work and merged the pull request.



\*\* Merge-Conflict Resolution



A merge conflict was simulated using the main and conflict-demo branches. The same line in hello.py was changed differently on each branch. When conflict-demo was merged into main, Git could not automatically determine which version to keep.



The conflict was resolved by:



Opening hello.py and reviewing the conflict markers.

Removing the conflict markers and selecting a final greeting.

Testing the resolved program with py hello.py.

Staging the resolved file with git add hello.py.

Completing the merge with a new commit.

Pushing the resolved changes to GitHub.



The resolved output is:

Hello, World! Merge conflict resolved.



\*\* GitHub Issues

Issue #2 — Expand README with project documentation: Assigned to Marc Mata. The README was expanded with the project purpose, program descriptions, branch and pull-request workflow, and merge-conflict resolution steps.

Issue #3 — Review/test Python programs: Assigned to a classmate to review both Python files, verify their output, and report the results.



\*\* Concepts Demonstrated

Git installation and configuration

Local and remote repositories

Commits and version history

Feature branches

Pull requests and collaboration

Merge-conflict identification and resolution

GitHub Issues and task assignment

Project documentation


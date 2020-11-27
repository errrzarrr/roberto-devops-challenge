# DevOps Challenge

## First Part of the Challenge:

1. Clone an OpenSource public .NET Repository of your preference. Hosted at GitHub, GitLab, BitBucket, you choose.

2. Create a local new branch. _Note:_ see instructions below on how you'll name your branch.

3. Add a new environment variable with PowerShell or Shell Scripting.

4. Add code in a new function to read such environment variable. Assume this variable to be an user's secret key.

5. Add a new Unit Test to to prove such method works correctly.

7. Add NUnit framework and any other one needed to the project's dependencies.

6. Run your test along with all other tests in the Unit Tests suite.

8. Build and run the project.

9. Using Shell scripting: Create a new README.md file describing the new method you just created. If it already exist, add new line(s) at the end of the file describing the new method you just created.

10. Commit your changes.

11. Push your branch.

12. Create merge request.

Naming your branch: _<your_username>-devops-challenge_. So if your username is _linus123_, the branch you'll be pushing and requesting to merge would be named _linus123-devops-challenge._ Message me with the name and URL of the project you've decided to clone/fork so we can have a copy. Then message me once you are ready to merge your work.

## Second Part of the Challenge:
1. Build a pipeline (CircleCI, Terraform or both) so it can be deployed into AWS automatically after being merged into 'master'.
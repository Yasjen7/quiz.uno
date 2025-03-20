# quiz.uno

> The project is the backbone of an application that will print if the user is eligible for voting or not based on their age. Feature-A; created by Eric, shows a greeting message to user and ask for their name. Feature-B; created by Lucy, asks the user for their age. A user is only eligible to vote if their age is greater than or equal to 18. Then Feature-C; created by Adam, In the end asks the user to participate in a simple survey to determine their experience (on a scale of 1 to 5).

## Getting Started

1. Create a New Repository, ensure it is Public and Add README file.
2. Go to ‘Settings and under ‘Collaborators’, add each of your teammates. Ensure they Accept Invite.
3. On your repository’s web page, click the Branch button, then click ‘View All Branches’
4. click the ‘New Branch’ button and Name it ‘Develop’
5. On the Settings page of your repository is a section called ‘Branches’
6. Click ‘Add rule’
7. Under ‘Branch name pattern’, enter `main`
8. Add the ‘Require a pull request before merging’ and ‘Require approvals` rules just below. Set the required amount to 1
9. Whoever created the repository should see a ‘Code’ button above their commit history, Copy the URL provided.
10. run the ‘git clone’ command with provided URL at the end Example: `git clone https://github.com/randomuser/randomrepository.git`

### Prerequisites

The things you need before.

- Create your GitHub profile
- Ensure that you are logged in

### Installation

A step by step guide that will tell you how to get the development environment up and running.

```
1. Check your current branch: git branch
2. Create and switch to your feature branch: git checkout -b feature-a
3. Create new files with this code: 
welcome.js
import { verifyName } from './getName.js';

console.log("=".repeat(35));
console.log("Welcome to eligibility check");
console.log("=".repeat(35));
console.log("\n");

const userName = verifyName(username);
console.log(`Hello ${userName}!\n`);
 getName.js

export function verifyName() {
  const input = prompt("Enter your age: ");
  return input;
}

4. Stage the files: git add welcome.js getName.js
5. Check the status of your files: git status
6. Commit your changes: git commit -m "([Your Name]) Feature-A: Show a greeting message and ask for the user's name"
7. Push your branch to the remote repository: git push --set-upstream origin feature-a
8. Go to your repo on GitHub and refresh the page.
9. Click ‘Compare & Pull Request’.
10. Set the base branch to develop (not main).
11. Merge the changes.
12. Verify your changes are in the remote repository.

```

## Usage

A few examples of useful commands and/or tasks.

```
1. Using the terminal to run git commands
2. Creating branches
3. Creating new files
4. Add changed files to your commits
5. Resolving merge conflicts
6. Approving merge requests
7. Completing merge requests

```
### Branches

* Main:
* Develop:
* etc...

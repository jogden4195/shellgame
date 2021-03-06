# Shellgame

## Table of Contents
* [Installation](#installation)
* [Submissions](#submissions)

## Installation
1. Clone the shellgame repo:
   - `git clone https://github.com/srinitude/shellgame.git` (HTTPS)
   - `git clone git@github.com:srinitude/shellgame.git` (SSH)
2. Change your working directory to shellgame: `cd shellgame`
3. Start the test suite: `./init.sh [your github username]`

## Submissions
Before adding test cases, follow this procedure so that the master branch doesn't get corrupted:
1. Check which branch you're currently on (`git branch`). An asterisk/star (`*`) will indicate which branch you're on.
2. If you're on a branch other than master, checkout to master (`git checkout master`).
3. Pull the most updated verison of master before adding your test cases (`git pull origin master`).
4. Checkout a branch for the case(s) you want to add (`git checkout -b [test-case]`).
5. Add your test case(s) to the directory related to the specific task.
6. Add and commit your change(s).
7. Push that branch, not to master (`git push origin [test-case]`).
8. Open a pull request on Github.
9. Slack the sf-0517 channel with the link to the pull request and have someone merge to master for you.
10. Delete the branch you committed and pushed after merging to master.

## Credits
Thanks to everyone who contributed! The contributors are listed in the [AUTHORS](https://github.com/srinitude/shellgame/blob/master/AUTHORS) page.
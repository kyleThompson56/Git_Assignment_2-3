Branch Structure

Main - stable branch containing production ready version

Dev - Working branch where active development happens.

feature1 - adds feedback messages for guesses, play again loop functionality, and ability to quit the game by inputting a negative number.

feature2 - adds maximum attempts and game over condition

feature3 - adds hint system

documentation - branch dedicated to writing and updating project documentation



Learning review

Merge merges once branch with another, resolving any conflicts between them.

Rebase adds any changes applied to one branch to another. Rewrites any commits on the current branch onto another branch.

Squash merges commits into one commit for ease of understanding.

Cherry pick takes one commit from another branch and puts it into another branch.



These all have distinct use cases.

Merge is used when a feature is complete to ensure put it into the original, production, or development branch.

Rebase is used on a feature branch to replay any features built on top of any changes made to the development branch. It cleans up any conflicts and keeps it fairly up to date.

Squash is used when messy commits exist, and is used to clean up commit history.

Cherry pick is used when one commit is needed from another branch, and not anymore than that. The simplest usecase is for hotfixes, where a single bug is fixed in a hotfix environment, then cherry-picked directly into main.




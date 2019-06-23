## Ensomate client
Ensomate client to display integration details and analytics

#### Setup instructions

```
git clone git@code.spritle.com:ensomate/client.git
cd client
yarn dev
```

#### Contribution

* Create your feature or bug fix in a separate branch.
* Always checkout from master.
* Create specific branch.
* Eg:
    * branch_name: `feature/login` 
    * branch_name: `feature/login_logout_forgot_password `
    * **Please do not work or push to master branch**
* **Commit**
    * Do not have too many changes in one commit. Do not commit unrelated files or directory. 
    * Write useful commit messages. Good title and good description. Don't hesitate to write descriptive commit message.
* **Pull request**

    **Before Pull Request:**
    * Squash commits  if needed.
    * Be up to date with master
    * git pull --rebase origin master

    **After Pull Request:**
    * Give pull request
    * Look at the diff of your pull request, just skim through to find any spelling or any other error.
    * Wait for some one to review your code. 
    * Do not merge the pull request yourself.
    * Demand review from someone even if you're 100% confident. Possibly, assign someone to review.
* **General advice:**
    * Push multiple commits a day. Even if it's incomplete or not working.
    * Give pull request in chunks. Not with **20+ files**.
    * Rebase with repo's master frequently. `git fetch origin ; git rebase master.`
    * Write good commit messages with proper one line or possible description about commit message
    * Do **NOT** use `git push -f` or `git push origin master`

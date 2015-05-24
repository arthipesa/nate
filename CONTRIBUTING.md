# Contributing to Nate

We'd love for you to contribute(source code, stars, issues, etc.)

## Found an Issue?

You can help us by using the [issue tracker](issues).

## General Guidelines

We love pull requests from everyone, but for them to be accepted, we'll
encourage that you do the following:

* Fork, then clone the repo:

    git clone git@github.com:your-username/nate.git

* Make your changes(accompanied with appropriate tests) in a new git branch:
    
    git checkout -b my-feature-branch master

* Commit your changes using a descriptive commit message. You should read
  https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message to see
  how we like our commit messages ;)

    git commit -a

* Build your changes locally to ensure everything works as intended
     grunt

* Push your branch to Github:
        
        git push origin my-feature-branch

* If there are any changes to be made:
  * Make needed changes/updates
  * Test

  * Rebase your branch and force push to Github to update your PR
        
          git rebase master -i
          git push origin my-feature-branch -f

### After Your PR is merged

Delete your local & remote branches. Checkout the master branch and pull the
latest upstream version:
    
    git chekcout master -f
    git branch -D my-feature-branch
    git pull --ff upstream master



[issues]: https://github.com/NibbleIT/nate/issues/

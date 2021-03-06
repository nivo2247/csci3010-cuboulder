1. Get a function from Felix to implement in the [collaboration repo](https://github.com/muzny/csci3010-spring2019-collab/) with 2 other people. Groups must be 2 or 3 people big.
    1. Create a new branch, including at least one person's name in your group and the function that you are implementing in it's name (example: `felix-james-iseven`). `git checkout -b [branchname]`
    2. Push this new branch to remote. `git checkout -u origin [branchname]` or `git push --set-upstream origin [branchname]`
    3. Implement your function in `ManyFunctions.[h|cpp]` and `main.cpp` in the [`utility_functions` folder](https://github.com/muzny/csci3010-spring2019-collab/tree/master/utility_functions).
    4. Push your changes to remote. `git push origin [branchname]`
    5. When you are ready, [create a pull request on github](https://help.github.com/articles/creating-a-pull-request/) and raise your hands to get matched with a group of reviewers.
2. Review the PR assigned to your group on github, making sure to address all points in the [code review checklist](../7_git_branches/code_review_checklist.md).
    1. Everyone should pull the branch that you've been assigned to, compile it, and test it. `git fetch`, then `git checkout [branchname]`
    2. Take a screen shot of your terminal after you have run `git status` and `make` on the branch that you are testing. Turn this screenshot in on canvas.
    3. Everyone should make at least 1 comment on the pull request. If you think that no changes need to be made, birefly describe why.
---
3. Complete the [lecture 8 activities regarding Catch and unit tests](lec8_turnin.txt) with your partners from questions 1 and 2.
    1. [Catch2 tutorial](https://github.com/catchorg/Catch2/blob/master/docs/tutorial.md#top)
    2. [Catch2 assertion macros](https://github.com/catchorg/Catch2/blob/master/docs/assertions.md#top)
    3. These are also linked [in our resources document](https://github.com/muzny/csci3010-cuboulder/blob/master/resources.md#unit-testing)

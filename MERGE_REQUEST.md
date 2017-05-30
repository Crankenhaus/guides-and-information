# How we manage merge requests

## You are requesting a merge
* Make sure your commits adhere to our [standards](GIT_COMMITS.md)
* Pick the right prefix-tag for your merge request (list of tags can be found [here](COMMIT.TAGS.md))
* Think of a good title for your merge request, it should reflect the changes you've made.  
    * If your merge request is still a work in progress, but you already want feedback, prefix it with `WIP:` to let everyone know you are still working on it
    * If you are fixing an issue just reference the issue # in the description  
    * If you are pushing something that has no related issue, detail your changes and the need for them in the description of the merge request
* Select the people you want to review your merge request (Review is mandatory!)
* You can also mention people using `cc @example @example2` at the bottom of your description  

__*time passes*__  

* You address any changes that have been request by pushing them into your branch
* The merge request is accepted or closed

## You are asked to review a merge request
* Review the code and point out any problems that you find
* Request changes from the author if you happen to find anything that requires adjustment.
* If your notes have been addressed, comment `Looks good to me!` to let everyone know you are happy with the merge request

## You are assigned to a merge request
* Go through the same process as when reviewing a merge request
* Remember the author to squash small commits
* Accept the merge request and __rebase__ it onto the base branch
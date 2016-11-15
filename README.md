# Exercises for the remaining weeks

As per request, this repository contains the exercises for the week on object-oriented programming and the week on R packages as a joint repository. This will also serve as an introduction to handing in solutions via so-called *pull requests* since we are changing the plan for the use of GitHub for exercises anyway.

## Forking repositories and merging through pull requests



### Forking a repository

Unlike the exercises repositories you have used so far, that are isolated from the template they were based upon, this repository is tied up to an original repository. This one.

With the previous exercises you had your very own repository and there were never any intent to update your version based on mine, or of merging your changes with my code. This is not the typical pattern used when working with source code in a git setting. There the idea is more that we have a network of versions of the code and we can merge code from one version to another.

The typical pattern is that there is a main repository, which in this case would be this repository, and then forks of that. The forks are really just other repositories, but ones you can use to push your changes to. You create a forked repository by clicking on the **fork** button at the top of the repository web page.

![Fork button](figures/fork.png)

This creates a new repository that lives at your own GitHub account. Your repository and mine live separate lives. You can push changes to your own version and they won't be pushed to mine, and changes I make to this repository will not automatically be merged into your repository.

You *can* pull any changes I make to this repository into your own version -- something I don't plan to have happen in this class -- but you cannot push your changes into my version. You don't have write permission to make changes to my code, after all.

If I *do* happen to make changes to this repository it will show up on the page of your repository just above the list of files.

![Repository behind original](figures/behind.png)

If this happens you can click the **Compare** button and switch branches to make a pull request to yourself that include my changes ... I don't expect it to happen, so that is all I will say about that.

Since you cannot push your changes into repositories you do not control, the typical pattern is instead to request from a repository maintainer that he or she pulls changes into the main repository from your fork. I won't actually pull your code into this repository in this class, but we will use such pull requests as the way to hand in project exercises.

### Making pull requests

To make a pull request you push the **New Pull request** button.

![New pull request](figures/new-pull-request.png)

This takes you to a page that should look similar to the one shown below:

![Pull request page](figures/new-pull-request-first-page.png)

Here you simply have to press the **Create pull request** button. This will then send you to a page where you can describe the pull request.

![Creating a pull request](figures/creating-pull-request.png)

In this class you only need to make one such pull request, and I would prefer if the title you give it is your name -- that way I know which pull request was made by each one of you. Normaly, when sharing code on GitHub the pull request is used to describe that changes you have made to a repository and explain why you think it is worth merging into the main code base.

Below the field for documentation there is another green button. Press this to actually create the pull request.

![Create pull request button](figures/create-button.png)

Creating the pull request now sends you to a page that looks like this:

![New pull request](figures/pull-request.png)

In your case you won't have the option of merging the pull request. I have that because I can modify both my own repository and this class repository. You will have a similar page, though. It shows the history of what you have done to your code and the comments you have made when creating the pull request. There is also a message about code being checked. I describe that below.

This pull request remains open until either I merge it into this repository -- which I do not plan to do -- or until you delete it. Don't delete it, though, since we will use it to hand in exercises. Whenever you push changes to your repository it will also show up on this pull request, so you now have an automatic way of submitting your handins. You just push changes to GitHub.

(Strictly speaking it is only changes pushed to the branch that was used in the pull request, but since we are not using branches here it won't matter. You can just push your changes and they should show up on the pull request and I will be informed about them).

I will use the pull request to comment on your code -- I can do that both by adding comment to individual code lines or through general comments, and I can even commit my own changes to your pull request -- and you can add comments to the pull request at any time.

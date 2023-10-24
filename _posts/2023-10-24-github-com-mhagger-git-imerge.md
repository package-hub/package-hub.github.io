---
title: git-imerge
categories: ['python', 'git', 'merge-conflicts']
---
## [git-imerge](https://github.com/mhagger/git-imerge)

### Incremental merge for git


Perform a merge between two branches incrementally. If conflicts are encountered, figure out exactly which pairs of commits conflict, and present the user with one pairwise conflict at a time for resolution.

`git-imerge` has two primary design goals:

* Reduce the pain of resolving merge conflicts to its unavoidable minimum, by finding and presenting the smallest possible conflicts: those between the changes introduced by one commit from each branch.

* Allow a merge to be saved, tested, interrupted, published, and collaborated on while it is in progress.

I think that it is easiest to understand the concept of incremental merging visually, and therefore I recommend the video of my [git-imerge presentation from the GitMerge 2013 conference](https://www.youtube.com/watch?v=FMZ2_-Ny_zc) (20 min) as a good place to start. The full slides for that talk are available in this repository under `doc/presentations/GitMerge-2013`. At the same conference, I was interviewed about `git-imerge` by Thomas Ferris Nicolaisen for his [GitMinutes Podcast #12](https://episodes.gitminutes.com/2013/06/gitminutes-12-git-merge-2013-part-4.html).

To learn how to use the `git-imerge` tool itself, I suggest the blog article [git-imerge: A Practical Introduction](https://softwareswirl.blogspot.com/2013/05/git-imerge-practical-introduction.html) and also typing `git-imerge --help` and `git-imerge SUBCOMMAND --help`. If you want more information, the theory and benefits of incremental merging are described in minute detail in a series of blog articles [[1](#REF1)], as are the benefits of retaining history when doing a rebase [[2](#REF2)].

Multiple incremental merges can be in progress at the same time. Each incremental merge has a name, and its progress is recorded in the Git repository as references under `refs/imerge/NAME`. The current state of an incremental merge can be visualized using the `diagram` command.

An incremental merge can be interrupted and resumed arbitrarily, or even pushed to a server to allow somebody else to work on it.

`git-imerge` comes with a Bash completion script, `completions/git-imerge`, which is installed automatically when installing `git-imerge`.


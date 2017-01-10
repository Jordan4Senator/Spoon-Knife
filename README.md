### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:

The first attempt to test MantisBT github integration failed.
Trying again to close Issue #24 with a more explicit commit message
(instead of "Fixes#24" using the EXACT same format as on the web page: Fixes issue #17

Looking at the reg ex from setting page:
/(?:bugs?|issues?|reports?)+\s*:?\s+(?:#(?:\d+)[,\.\s]*)+/i
will track it
/(?:fixe?d?s?|resolved?s?)+\s*:?\s+(?:#(?:\d+)[,\.\s]*)+/i
will set it to resolve and add the commit code.

It would be nice if there were the same hooks 'pre-baked' in git so
that during the check-in the URL replaces the text (the URL is shown
within the Mantis tool, but not within the git comment in the repo)

Works fine. Both issues were appropriately closed - no local hooks howeve
means that in github, the bug numbers tries to reroute to their issue
tracker.

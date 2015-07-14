A Crash Course in Version Control and Git
=============

These are the presentation materials and notes used at the PowerShell.org TechSession [A Crash Course in Version Control and Git](https://www.youtube.com/watch?v=wmPfDbsPeZY)

At the end of the day, this is quite similar to PowerShell. You're not going to pick up Git and GitHub from an hour long webinar or a three day course. Start using Git and GitHub for a project. Get involved with a repository on GitHub.

The only way you'll pick this up is if you start using it on a regular basis... And if you're not on some fancy development team, this is going to be far simpler than picking up PowerShell.

## Resources from the PowerPoint:

### Interactive Guides

These are a great way to spin up quickly. The GitHub guide is short and sweet.

* [GitHub’s interactive guide](https://try.github.io/) - Learn Git in 15 minutes
* [Learn Git Branching](http://pcottle.github.io/learnGitBranching)
* [Interactive Cheat sheet](http://ndpsoftware.com/git-cheatsheet.html)

### References

* [Official Git reference](http://git-scm.com/docs)
* [Pro Git](http://www.git-scm.com/book/en/v2) (free!) - the first two or three chapters are a great intro
* [Understanding Branches](http://blog.thoughtram.io/git/rebase-book/2015/02/10/understanding-branches-in-git.html)
* [Git Explained: For Beginners](http://www.dotnetcodegeeks.com/2015/06/git-explained-for-beginners.html)
* [GitHub Flow – GitHub from a Browser](https://github.com/blog/1557-github-flow-in-the-browser)

### Contributing to Microsoft’s DSC Resources on GitHub

* [Guide to getting started with GitHub](https://github.com/PowerShell/DscResources/blob/master/GettingStartedWithGitHub.md)
* [DSC Contributions guide](https://github.com/PowerShell/DscResources/blob/master/CONTRIBUTING.md)
* [DSC Resource Style Guidelines](https://github.com/PowerShell/DscResources/blob/master/StyleGuidelines.md)

### More references

* [Pro Git](http://www.git-scm.com/book/en/v2) (free!) - the rest of the book : )
* [A Visual Git Reference](http://marklodato.github.io/visual-git-guide/index-en.html)
* [Git From the Inside Out](https://codewords.recurse.com/issues/two/git-from-the-inside-out)
* [Git For Computer Scientists](http://eagain.net/articles/git-for-computer-scientists) - Great read with helpful pictures, don’t be intimidated by the title
* [Branching, forking, other concepts explained](http://stackoverflow.com/questions/3329943/git-branch-fork-fetch-merge-rebase-and-clone-what-are-the-differences)

### Oh shoot, something went wrong!

* [So you have a mess on your hands workflow](http://justinhileman.info/article/git-pretty/git-pretty.png)
* [How to undo (almost) anything with Git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git)

### A few recent articles:

* [Git Disciplined](http://blog.8thlight.com/makis-otman/2015/07/08/git-disciplined.html)
* [Git for IT Professionals: Getting Started](http://www.powershellmagazine.com/2015/07/13/git-for-it-professionals-getting-started-2/) - Thanks to Ravikanth! More to come in this series
* [PowerShell.org Community Build Server](http://powershell.org/wp/community-build-server/) - A big thanks to Dave Wyatt, PowerShell.org, Chef, and anyone else involved in this : )

### Shameless plug!

* [Source Control Survey Results](http://ramblingcookiemonster.github.io/Source-Control-Survey/)
* [GitHub for PowerShell Projects](http://ramblingcookiemonster.github.io/GitHub-For-PowerShell-Projects/)
* [Fun with GitHub, Pester, and AppVeyor](http://ramblingcookiemonster.github.io/GitHub-Pester-AppVeyor/)
* [GitHub, Pester, and AppVeyor: Part Two](http://ramblingcookiemonster.github.io/Github-Pester-AppVeyor-Part-2/)
* [Testing DSC Configurations with Pester and AppVeyor](http://ramblingcookiemonster.github.io/Testing-DSC-with-Pester-and-AppVeyor/)
* [GitHub pages](http://ramblingcookiemonster.github.io/GitHub-Pages/) - a great way to host your blog content, if you don’t mind a little yak shaving

## Notes

* The vast majority of the youtube video should be reasonable, content wise.
* Paraphrased / simplified a few things.
* The description of 'HEAD' was a bit shaky, not sure why I tried to reword that on the spot - sorry about that! You probably won't even need this, but here's an explanation of [HEAD](http://stackoverflow.com/a/4381549).
* Contributing to the Microsoft DSC resources? You can ignore most of the branch and HEAD discussion. Long story short, just make sure you are working on the dev branch, and that you submit your pull request to the dev branch.
* I mentioned there weren't many solid Git server solutions in the Microsoft ecosystem. Haven't used it, but [SCM-Manager](https://www.scm-manager.org/) might be worth a peak if you want a free on-prem solution, and you don't mind Java.
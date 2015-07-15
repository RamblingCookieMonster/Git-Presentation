A Crash Course in Version Control and Git
=============

These are the presentation materials and notes used at the PowerShell.org TechSession [A Crash Course in Version Control and Git](https://www.youtube.com/watch?v=wmPfDbsPeZY).

At the end of the day, this is quite similar to PowerShell. You're not going to pick up Git and GitHub from an hour long webinar or a three day course. Start using Git and GitHub for a project. Get involved with a repository on GitHub.

The only way you'll pick this up is if you start using it on a regular basis... And if you're not on some fancy development team (or even if you are), this is going to be far simpler than picking up PowerShell.

## Resources from the PowerPoint:

Here are some handy resources from the last slide, and a few extracted from the slide notes. Don’t be intimidated, you don’t need all this, but it may come in handy if you want to dive a bit deeper into the weeds.

### Why Use Version Control?

Research your own scenario. Chances are you should be using version control. A few examples:

* [The Operations Report Card](http://www.opsreportcard.com/section/6) - Because Tom said so.
* [A stackoverflow thread](http://stackoverflow.com/questions/1408450/why-should-i-use-version-control)
* [Why Use a Version Control System?](http://www.git-tower.com/learn/git/ebook/mac/basics/why-use-version-control)
* [Why revision control?](http://hgbook.red-bean.com/read/how-did-we-get-here.html)
* [A Visual Guide to Version Control](http://betterexplained.com/articles/a-visual-guide-to-version-control/)

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
* [GitHub for PowerShell Projects](http://ramblingcookiemonster.github.io/GitHub-For-PowerShell-Projects/) - Shameless plug

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
* [Linus Torvalds' Google Tech Talk on Git](https://www.youtube.com/watch?v=4XpnKHJAok8) - More focused on design, but a fun talk

### Oh shoot, something went wrong!

* [So you have a mess on your hands workflow](http://justinhileman.info/article/git-pretty/git-pretty.png)
* [How to undo (almost) anything with Git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git)

### A few recent articles:

* [Git Disciplined](http://blog.8thlight.com/makis-otman/2015/07/08/git-disciplined.html)
* [Git for IT Professionals: Getting Started](http://www.powershellmagazine.com/2015/07/13/git-for-it-professionals-getting-started-2/) - Thanks to Ravikanth! More to come in this series

### Popular Git clients on Windows

* [GitHub for Windows](https://windows.github.com/) - I use this; it's simple, and it works.
* [Atlassian SourceTree](https://www.sourcetreeapp.com/) - I use this; Supports Mercurial, more functionality than GitHub for Windows, if you need it.
* [msysgit](http://msysgit.github.io/) - Command line and a basic GUI
* [TortoiseGit](http://tortoisegit.org/) - I don't use this, but I've heard good things.
* [Yada yada yada](http://git-scm.com/downloads/guis)

### Continuous Integration and Delivery

This is an interesting topic, excited to see this mature in the MSFT / PowerShell ecosystem. You should start exploring this, it's incredibly helpful.

* [Automating with Jenkins and PowerShell on Windows](https://www.hodgkins.net.au/powershell/automating-with-jenkins-and-powershell-on-windows-part-1/)
* [PowerShell + Pester + Jenkins : Journey to Continuous Integration](http://www.dexterposh.com/2015/06/powershell-pester-jenkins-ci.html)
* [Fun with GitHub, Pester, and AppVeyor](http://ramblingcookiemonster.github.io/GitHub-Pester-AppVeyor/)
* [GitHub, Pester, and AppVeyor: Part Two](http://ramblingcookiemonster.github.io/Github-Pester-AppVeyor-Part-2/)
* [Testing DSC Configurations with Pester and AppVeyor](http://ramblingcookiemonster.github.io/Testing-DSC-with-Pester-and-AppVeyor/)
* [Sergei Vorobev from the PowerShell team, talking GitHub, Pester, and AppVeyor](https://www.youtube.com/watch?v=zFd9DJPERIo)
* [PowerShell.org Community Build Server](http://powershell.org/wp/community-build-server/) - Thanks to Dave Wyatt, PowerShell.org, Chef, and anyone else behind this!

## Notes

* The vast majority of the youtube [video](https://www.youtube.com/watch?v=wmPfDbsPeZY) should be reasonable, content wise.
* Paraphrased / simplified a few things.
* The description of 'HEAD' was a bit shaky, not sure why I tried to reword that on the spot - sorry about that! You probably won't even need this, but here's an explanation of [HEAD](http://stackoverflow.com/a/4381549).
* Contributing to the Microsoft DSC resources? You can ignore most of the branch and HEAD discussion. Long story short, just make sure you are working on the dev branch, and that you submit your pull request to the dev branch.
* I mentioned there weren't many solid Git server solutions in the Microsoft ecosystem. Haven't used it, but [SCM-Manager](https://www.scm-manager.org/) might be worth a peak if you want a free on-prem solution, and you don't mind Java.

Thanks to Nick Getchell and PowerShell.org for the invite, it was an honor and a pleasure to give this presentation!

Git for Teams of One or More
=====================

Supporting files for workshops and sessions about creating a developer work flow for your project (and your team) with the version control system, git.

You may also be interested in the companion book, [Git for Teams](http://shop.oreilly.com/product/0636920034520.do), and the hands-on videos [Collaborating with Git](http://shop.oreilly.com/product/0636920034872.do).

## Content

*/slides*

Reveal.js slides for various workshops and conference sessions.

- OSCON workshop (2014, 2015)
  - [one-page summary](slides/slides/workshop-oscon-gitforteams.md)
  - [slide deck](http://emmajane.github.io/gitforteams/slides/slides/workshop-oscon.html)
  - [PDF slides](http://emmajane.github.io/gitforteams/handouts/slides-gitforteams-oscon.pdf)
- LoneStar PHP (2014)
  - [one-page summary](slides/slides/session-lonestarphp-strategy.md)
  - [slide deck](http://emmajane.github.io/gitforteams/slides/slides/session-lonestar.html)
  - [PDF slides](http://emmajane.github.io/gitforteams/handouts/slides-gitforteams-lonestarphp.pdf)

*/resources*

The following work flow documents are referenced in the presentation:

- [Star Wars Work flow](resources/workflow-sample-starwars.md)
- [Whispering Pines Weekly Workflow](resources/workflow-sample-whisperingpines-code.md)
- [Whispering Pines - release cycle philosophy](resources/workflow-sample-whisperingpines-releasecycle.md)
- [Whispering Pines - deployment](resources/workflow-sample-whisperingpines-deployment.md)

## Acknowledgements

Emma is grateful for the support she received while employed at Drupalize.Me (Lullabot) for the development of this material. The first version of the reveal.js slides for this work were posted at [workflow-git-workshop](https://github.com/DrupalizeMe/workflow-git-workshop).

## Process

1. Create a new ticket in your issue tracking system; note the number on the issue
2. In your local repository, create a new branch using the format issuenumberdescription.
3. Do the work described in the ticket (and only the work described in the ticket).
4. Test your work and make sure it is complete and correct. Ensure it passes your
QA test from the ticket you wrote in the development environment.
5. You now have a “dirty” working directory that contains new and/or modified
files. Add your changes to the staging area of your local repository.
6. Commit your staged changes to the repository.
7. Push your changes to a backup server. In many cases, this will also be where your
tickets are being tracked, such as GitLab, Bitbucket, or GitHub. Depending on
Issue-Basedyour ticketing system, the ticket may now be marked as resolved but not necessarily closed.
8. When you are completely satisfied with your work, merge your ticket branch into
your main branch (usually master) and push the revised branches to the code
hosting system.
9. Test your work again to ensure there are no follow-up issues.
10. Update your ticket as appropriate to close it out.

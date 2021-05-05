<!--- ORGANISER THINGS TO CONSIDER 
- Which technical competencies, behaviours and knowledge module topics does the bootcamp cover/meet
- Structuring retros so that they can inform thinking for individual's personal learning records (off the job training record tab in their learning logs)
- Introducing some sort of test or quiz on basic concept learning points from the bootcamp to validate that they have taken stuff in, and provide organisation mentors with results to help them focus follow ups
--->

## Competencies, Behaviours and Knowledge units

* TC1 Logic
* TC4 Test
* TC8 Deployment
* TC9 Software development life cycle

## Resources 

* Slides
* Laptops
* Internet access
* Post-its
* Pens
* Whiteboard

## Mentors / Languages
 
Two–three mentors required in addition to leads. These should be able to cover support for the required languages.

Exercises (katas and code starters) will need to be ported to required languages.

Mentors should be comfortable with branching, feature toggles, setting up Travis for their chosen language.

## Prep-work for apprentices

* See [the preparation description](https://github.com/MCR-Digital/tax_calculator/#preparation)

### Follow-on tasks

Organisation mentors should look to exercise the knowledge we’ve covered in the boot camp. Below are suggestions for tasks that would do this, but please use your own judgement to work out what to do. There is no need for anything to be returned to MD or the presenters—it’s just a learning exercise.

* Find out what CI systems the organisation uses
* Find out how the team works with branches and discuss this with your mentor
* Find out how the team deploys code and manages releases to mitigate risk

## Further reading / learning resources

<!--- For end of boot camp: Signposting for apprentices self study, further learning, online resources, practice etc. --->

### CI/CD

* Five minute read: [Continuous Integration by ThoughtWorks](https://www.thoughtworks.com/continuous-integration)
* Book: [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley-ebook/dp/B003YMNVC0) by Jez Humble and David Farley
* [Feature Toggles](https://martinfowler.com/articles/feature-toggles.html) by Pete Hodgson at ThoughtWorks
* [Knightmare: A DevOps Cautionary Tale](https://dougseven.com/2014/04/17/knightmare-a-devops-cautionary-tale/) about Knight Capital disaster
* [The Cathedral and the Bazaar](http://www.catb.org/~esr/writings/cathedral-bazaar/cathedral-bazaar/)
* [Six Strategies for Application Deployment](https://thenewstack.io/deployment-strategies/)

### Git

* [Git Pretty](http://justinhileman.info/article/git-pretty/) explains how to fix git messes you find yourself in
* [Git-it](https://github.com/jlord/git-it-electron) is a desktop (Mac, Windows and Linux) app that teaches you how to use Git and GitHub on the command line.
* [Trunk Based Development](https://trunkbaseddevelopment.com/)—a while site dedicated to explaining TBD
* [Git for Teams](http://gitforteams.com/) is has a book and some video aimed at helping you create a workflow strategy with your team, and learn to use Git

## Slides

The slides can be viewed from the link at the top of the repository.

## Exercises

The code for the exercises in this boot camp is currently in the [tax_calculator repository](https://github.com/MCR-Digital/tax_calculator).

* Setting up Travis CI, changing tax_calculator & watching Travis fail/pass
* Changing tax_calculator using feature branches
* Changing tax_calculator using trunk development and feature toggles

# Boot Camp Summary

* Continuous Integration
  * What it is and why we do it
  * Examples of different CI systems
  * Exercise: add Travis to fork of existing repo
  * Exercise: Make change to their fork and show (hopefully) successful build
* Continuous Delivery/Deployment
  * What it is and why we do it
  * Benefit of fast feedback—small/fast deployments
* Branch based development
  * What is a branch
  * Explain feature branching and pull requests
  * Exercise: Get them to make two changes using feature branches
* Trunk based development
  * What is a feature shield
  * Exercise: Get them to implement a feature shield
* Comparison of approaches

# Briefing for organisation mentors

* Review the summary above
* Have a go at the exercises to get a gist for the
    * Exercises are described in the slides linked to at the top of the repo
    * Code for the exercises is in the [tax_calculator repository](https://github.com/MCR-Digital/tax_calculator)
* On the day get involved when they are doing the exercises and help them when they get stuck
* Ask them open questions about what they are doing
  * Ask to see what they’ve done
  * Start with the tests
* Help resolve language specific issues
* Coach them towards finding their own solutions rather than fixing things for them

# Working with the slides

The slides are stored as Markdown files in `docs/_posts` and are presented using a combination of Jekyll and [reveal.js](https://revealjs.com/#/). A [remote Jekyll theme](https://github.com/autotraderuk/jekyll-revealjs) is used to help make changes to the Jekyll code centrally.

The easiest way to preview your changes locally is to use docker to run Jekyll. To do this, [install docker](https://www.docker.com/get-started) if you haven’t already and run `docker-compose up` from the root of this project in a terminal. Your changes will be visible on <http://localhost:4000/>. Any changes you make to the slides will be reflected in your browser—there’s no need to restart docker. You can hit `ctrl-c` to stop the process.

Once you push your changes the slides will be published using GitHub Pages automatically (see the link at the top of the repository).

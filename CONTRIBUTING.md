# Contributing to missioncontrol

Thank you for taking the time to get involved with DAV Foundation projects! :+1:
The DAV project you are looking at is **missioncontrol**. 

Mission Control is a service running on the DAV network, and serving as a marketplace connecting DAV users looking to ship packages, with drone owners.

There are several ways you can help the project out:

* [Contributing code](#contributing-code)
* [Reporting Bugs](#reporting-bugs)
* [Feature Requests and Ideas](#feature-requests-and-ideas)

## How Can I Contribute?

### Contributing Code

A lot of **missioncontrol** functionality came from pull requests sent over GitHub. Here is how you can contribute too:

- [x] Fork the repository from the [missioncontrol GitHub page](https://github.com/DAVFoundation/missioncontrol).
- [x] Clone a copy to your local machine with `$ git clone git@github.com:YOUR-GITHUB-USER-NAME/missioncontrol.git`
- [x] Based on your platform install docker
        + [mac](https://docs.docker.com/docker-for-mac/install/)
        + [win](https://docs.docker.com/docker-for-windows/install/)
- [x] In the missioncontrol directory, run `docker-compose build && docker-compose up`
- [x] Incase you get the error `ERROR: Network dav declared as external, but could not be found. Please create the network manually using **docker network create dav** and try again.` Run `docker network create dav` and you are good to go.
- [x] Run `npm install` to install all the dependencies.
- [x] Run `npm start` to build and launch the project.
- [x] Code, code, code. 
- [x] Once you've made sure all your changes work correctly and have been committed, push your local changes back to github with `$ git push -u origin master`
- [x] Visit your fork on GitHub.com ([https://github.com/YOUR-USER-NAME/missioncontrol](https://github.com/YOUR-USER-NAME/missioncontrol)) and create a pull request for your changes.
- [x] Makes sure your pull request describes exactly what you changed and if it relates to an open issue references that issue (just include the issue number in the title like this: #49)

#### Important:

* To get full experience out of this project you need to get **missions** also up and running. See the CONTRIBUTING.md of missioncontrol for more details.
* Please stick to the project's existing coding style. Coding styles don't need to have a consensus, they just need to be consistent :smile:.
* Push your changes to a topic branch in your fork of the repository. Your branch should be based on the `master` branch.
* When submitting [pull request](https://help.github.com/articles/using-pull-requests/), please elaborate as much as possible about the change, your motivation for the change, etc.

#### Automated Testing


### Reporting Bugs

Bugs are tracked as [GitHub issues](https://github.com/DAVfoundation/missioncontrol/issues). If you found a bug with missioncontrol, the quickest way to get help would be to look through existing open and closed [GitHub issues](https://github.com/DAVfoundation/missioncontrol/issues?q=is%3Aissue). If the issue is already being discussed and hasn't been resolved yet, you can join the discussion and provide details about the problem you are having. If this is a new bug, please open a [new issue](https://github.com/DAVfoundation/missioncontrol/issues/new).

When you are creating a bug report, please include as many details as possible.

Explain the problem and include additional details to help maintainers reproduce the problem.

* Fill in the predefined template provided.
* Use a clear and descriptive title for the issue to identify the problem.
* Describe the exact steps which reproduce the problem. Share the relevant code to reproduce the issue if possible.
* Try to isolate the issue as much as possible, reducing unrelated code until you get to the minimal amount of code in which the bug still reproduces. This is the most important step to help the community solve the issue.

### Feature Requests and Ideas

We track discussions of new features, proposed changes and other ideas as [GitHub issues](https://github.com/DAVfoundation/missioncontrol/issues). If you would like to discuss one of those, please first look through existing open and closed [GitHub issues](https://github.com/DAVfoundation/missioncontrol/issues?q=is%3Aissue) and see if there is already a discussion on this topic which you can join. If there isn't, please open a [new issue](https://github.com/DAVfoundation/missioncontrol/issues/new).

When discussing new ideas or proposing changes, please take the time to be as descriptive as possible about the topic at hand. Please take the time to explain the issue you are facing, or the problem you propose to solve in as much detail as possible.
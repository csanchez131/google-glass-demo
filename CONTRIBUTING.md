These are the contribution guidelines for the SPHERE.IO sample application.

Contributions are welcome!

## Contribution process for all committers

### Typos 

If you have push access to the repository you can fix them directly otherwise just make a pull request.

### Code

1. on bigger effort changes: open an issue and ask if you can/should/need to help
1. fork the repository
1. produce production code and unit tests
1. make a pull request

## Requirements for a pull request

We want to have a clear and tested code base.

* change as few lines as possible
* never reformat code, we want in diffs only real changes
* use code formatting like in the rest of the application
* your committed code should not emit warnings such as unchecked generics
* you need to use tests to prove that your code works, JUnit tests are sufficient
* your code is from you and not copied from third party sources
* use [good commit messages](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
* tests have to be passed in Travis CI

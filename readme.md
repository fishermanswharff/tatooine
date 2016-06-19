# Q4 Delivery

* What does the term "deployability" mean to you?
* As a developer, what can you do to make your RoR applications "highly deployable"?

## 'deployability'

Deployability, to me, refers to the ease with which a dev team can push new code to a production environment.

* ease of scalability (both algorithmically and from an infrastructure standpoint)
  * Does the codebase wilt under the pressure of high traffic?
  * Can the server infrastructure handle an increasing traffic load?
* no 'manual' steps to push production code (ie not having to manually copy/paste secrets)
* integration between CI provider and application host

## Making RoR applications 'highly deployable'

* test-driven development, excellent test coverage
* good error handling (gracefully handle errors)
* use coding best practices (ie lint ruby with rubocop)
* write tasks for commands that can be called during the build process
* test test test

ECE444 Lab 5 Nicholas Heeralal

Q1. This is my repository where I replayed the example on https://github.com/mjhea0/flaskr-tdd.
I followed the instructions from "First Test" to "Conclusion" and skipped the steps for "Deployment" and "Postgres Heroku".
If you look at commit history, you can see commits for each section.

Q2. Unit tests I wrote for my teams project were test_index_not_logged_in, test_register_new_user and test_register_existing_user which
 can be found at this link: https://github.com/ECE444-2023Fall/project-1-web-application-design-group25-pixelpals/blob/main/react-flask-app/api/tests/test_app.py 
 In case that link is broken, these test cases were introduced in this commit:
https://github.com/ECE444-2023Fall/project-1-web-application-design-group25-pixelpals/commit/1c4a0c4fc13c2543c86b8da7d6ca716967a0dd6a
More specifically, in commit commit 1c4a0c4 of Group 25's repository.

Q3. What are the pros and cons of TDD?

My answer:
Pros of TDD:

Improved Code Quality: TDD often results in cleaner code and a lower bug rate because the code is tested from the start.

Refactoring Confidence: With a suite of tests in place, developers can refactor or enhance code with confidence, knowing that regressions will be caught by the tests.

Better Design: Writing tests first forces developers to think about the design and interfaces of their code before implementation. This often results in more modular and maintainable code.

Documentation: The test suite acts as a form of documentation that demonstrates how the system is supposed to work. New developers can refer to the tests to understand expected behavior.

Early Bug Detection: Bugs are detected and fixed earlier in the development cycle, which can lead to cost savings compared to detecting and fixing bugs later in the process or post-release.

Enhanced Collaboration: TDD can improve collaboration between developers, testers, and other stakeholders because it sets clear expectations of functionality.

Cons of TDD:

Learning Curve: There's a learning curve associated with mastering TDD, and not every developer is familiar with it. This can lead to initial resistance or improper implementation.

Time Consumption: Writing tests before code can seem to slow down the development process, especially initially. However, proponents argue that the time saved in debugging and maintenance offsets this initial cost.

Overhead: There's additional overhead in managing and maintaining the test suite, especially if tests become out-of-date or if there's poor test coverage.

Incomplete Test Coverage: Just because tests pass doesn't mean the software is bug-free. Tests are only as good as their coverage, and it's possible to miss certain edge cases.

False Sense of Security: Passing tests can sometimes give developers a false sense of security, leading them to believe the code is flawless when there might be scenarios not covered by the tests.

Potential for Over-Engineering: TDD can sometimes lead to over-engineering or writing more code than necessary because of an excessive focus on making tests pass.

Context Dependency: TDD might not be suitable for every project or context. For example, some exploratory or prototyping efforts might not benefit as much from TDD as a well-defined project would
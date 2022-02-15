# Engineering Core Values

The core values are:

1. [Clean Code](/corevalues/cleancode/cleancode.md)
2. [Fast Feedback](/corevalues/fastfeedback/fastfeedback.md)
3. [Repeatability](/corevalues/repeatability/repeatability.md)
4. [Simplicity](/corevalues/simplicity/simplicity.md)
5. [Operational Excellence](/corevalues/operationallyready/operationally-ready.md)
6. [Security](/corevalues/security/security.md)

## Practices

In order to realize these values there are 8 practices that we as an organization need to agree to adhere to. These are:

### [Vertical Slicing](practices/verticalSlicing/readme.md)

Ensures that business value has been delivered at the end of every feature/story. This is as opposed to "horizontal slicing" i.e. creating two different user stories for the frontend and backend work required to deliver some business value.

### [Simple Design](practices/simpleDesign/readme.md)

The simplest design is often (almost always) the best solution to a given problem. The simplest solution is the easiest to maintain, the easiest to change (assuming you have appropriate testing of course) and often provides extensibility and future reuse without adding complexity.

### [Collective Code Ownership](practices/collectiveCode/readme.md)

In collective code ownership, the entire team is responsible for the code. Everyone works together to produce a product of quality. No one individual is greater than the rest of the team members. This practice helps to reduce the need for hero work and eliminate silos of information within the team.

### [Pair Programming](practices/pairProgramming/readme.md)

Pair programming is the concept of two team members working on a single story/feature. Often, this is two developers working back and forth (there are numerous patterns/strategies to use) to deliver business value. Some high value pairs could be frontend and backend specialists. Each can help drive their specialty areas as well as help train the other. Additionally, QA and Devs can pair to ensure that their features are delivered with appropriate tests in place.

### [Refactoring](practices/refactoring/readme.md)

Refactoring is very tightly coupled to Simple Design and TDD. TDD enables simple design, while the practice of refactoring ensures that our code bases adapt to new or changing requirements while still keeping its maintainability.

### [Test Driven Development](practices/tdd/readme.md)

Test driven development enables us to build software with a simple design and enables us to ruthlessly refactor. It also enables us to ship software quickly and frequently (umm Agile anyone??) as we have a bed of tests delivered with all new functionality. This also allows you to refactor with confidence.

### [Continuous Integration](practices/cicd/readme.md)

Continuous Integration is a software development practice where members of a team integrate their work frequently, usually each person integrates at least daily - leading to multiple integrations per day. Each integration is verified by an automated build (including test) to detect integration errors as quickly as possible. Many teams find that this approach leads to significantly reduced integration problems and allows a team to develop cohesive software more rapidly.

### [Automate Repeatable Tasks](practices/automateRepeatableTasks/readme.md)

Humans are error prone; we are very bad at doing the same thing over and over. Machines, on the other hand, are very good at repeatable tasks! When working on a software project, we should strive to reduce any manual steps as much as possible. This will save time, reduce errors, but also add predictability to our software. "Works on my machine" is never an acceptable excuse! =)
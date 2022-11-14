# ECE444-F2022-Lab6

## Test cases from my group project
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-5-io/blob/main/Education_Pathways/tests/test_app.py#L281-L308 

## What are the pros and cons of TDD?
### Pros
- Allows more modular design: From writing tests for small features (or so called 'microfeatures'), developers can easily validate the code at a modular level and detect problems in the architecture at an early stage of development. 
- Easier to Maintain & Refactor: Since all segments of the program are covered by their respective tests, any minor change in the code can be easily detectable since their corresponding unit tests will fail. Also, since the features in the program are decoupled from one another, it makes it easier for parallel development as well as rewriting segments of the code as all the developers can simly re-verify the unit tests.
- High Test Coverage: Since there are tests for each micro-feature, there is an extremely high test coverage allowing code confidence.
- Documentation: Since only necessary code is produced from its tests, giving intutive unit test names allows for rapid understanding of the requirements for other developers.
### Cons
- Slow Development Process: Since TDD is more centric on developing a quality product that rapid product development, having to create tests for every micro-feature reduces the development speed especially during the initial phase.
- Committment and Learning: The entire team (not only developers) must believe in the TDD process. Also, TDD has a learning curve and all developers must be opted to be responsible for their own unit tests and development.
- Test Maintenance: The tests have to be maintained and altared as the requirements change. 
### References
- https://www.geeksforgeeks.org/advantages-and-disadvantages-of-test-driven-development-tdd/
- https://devqa.io/pros-cons-test-driven-development/
- https://www.encora.com/insights/understanding-the-pros-cons-of-test-driven-development-tdd
# Readings: Data Modeling

## Review, Research, and Discussion

**1- Name 3 advantages to Test Driven Development**

* *Better program design and higher code quality*

* *Detailed project documentation*

* *TDD reduces the time required for project development*

**2- In what case would you need to use beforeEach() or afterEach() in a test suite?**

* *(beforeEach) and (afterEach) can handle asynchronous code in the same ways that tests can handle asynchronous code - they can either take a done parameter or return a promise. For example, if initializeCityDatabase() returned a promise that resolved when the database was initialized.*

*use (beforeEach) to do some setup before each test runs in order to avoid repetition. In this case*

*(afterEach) runs a function after each one of the tests in this file completes. If the function returns a promise or is a generator, Jest waits for that promise to resolve before continuing.3*

**3- What is one downside of Test Driven Development**

* *When feature changes, implementation will change as well, and many test cases will fail. ... This problem exists as long as unit test exists, but more severe especially when the test cases are written during TDD. Since during TDD process people tend to focus on implementation, the test cases are more prone to change.*

**4- What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?**

* *Classes can’t be called without new, but functions intended as constructors can (and their this will be wrong)*
* *Classes can extend more types than constructors can (like functions and arrays)*
* *Classes’ prototypes are their parents (they inherit static properties); writers of constructor functions usually don’t bother with this*

**5- Why REST?**

* *Easy to Learn and Implement*
* *REST Makes your Application More Scalable*
* *Faster Data Interchange Format*
* *REST is Flexibile*
* *No state*
* *Caching is Easier with REST*

## Document the following Vocabulary Terms

**1- functional programming**

* *it is a programming paradigm where you mostly construct and structure your code using functions.*

**2- object-oriented programming (OOP)**

* *it is about creating objects that contain both data and functions.*

**3- Class**

* *it's a special functions in ES6, it's like a bluebrint for data modeling.*

**4- Super**

* *we use this when extending the class, to inherit the previous properties from the parent class.*

**5- this**

* *it is a keyword in javascript that refers to the scope that will be called in.*

**6- Test Driven Development (TDD)**

* *it's a software development practice, by testing then correct the test, then refactor the code.*

**7- jest**

* *it is a JavaScript testing framework designed to ensure correctness of any JavaScript codebase. It allows you to write tests.*

**8- Continuous Integration (CI)**

* *it is the practice of automating the integration of code changes from multiple contributors into a single software project.*

**9- REST**

* *REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.*

**10- Data Model**

* *Data Model is the modeling of the data description, data semantics, and consistency constraints of the data. It provides the conceptual tools for describing the design of a database at each level of data abstraction. there are four data models used for understanding the structure of the database.*
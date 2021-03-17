# Testing Main Information.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [JUnit 5.](https://github.com/descriptions-of-it-technologies/junit-5)
* [Mockito.](https://github.com/descriptions-of-it-technologies/mockito)
* [Spring Framework Testing.]()
* [Spring Boot Testing Annotations.](https://github.com/descriptions-of-it-technologies/spring-boot/blob/master/spring-boot-testing-annotations.md)
* [Integration Testing.](integration-testing.md)
* [Functional Testing.](functional-testing.md)
* [General.](#general)
* [Type of Testing.](#type-of-testing)
* [Common Testing Frameworks for Java.](#common-testing-frameworks-for-java)
* [Assertion Frameworks](#assertion-frameworks)
* [Help.](#help)





## About.





## Documentation.





## General.





## Type of Testing.
* Functional testing.
  * Unit Testing.
  * Integration Testing.
  * Interface Testing
  * Smoke Testing
  * Sanity Testing
  * Component Testing
  * System Testing
  * User Acceptance Testing
  * Localization Testing.
  * Globalization Testing.
  * Interoperability Testing.
  * Layout Testing.
* Non-Functional testing.
  * Performance Testing.
  * Endurance Testing.
  * Load Testing.
  * Volume Testing.
  * Scalability Testing.
  * Usability Testing.
* Maintenance.
  * Regression Testing.
  * Maintenance Testing.

* End-to-End Tests.
* A/B testing.





## Agile Testing Methods.
* [Test-Driven Development. TDD.](https://github.com/descriptions-of-it-technologies/tdd)
* [BDD - Behavior Driven Development.](https://github.com/descriptions-of-it-technologies/bdd)





## 
* [Eradicating Non-Determinism in Tests](https://martinfowler.com/articles/nonDeterminism.html)





## Common Testing Frameworks for Java.
* [JUnit.]()
* [TestNG.]()
* [Spock.]()
  * Testing Framework in Groovy for testing Java.
  * Does require knowledge of Groovy.
  * Follows BDD approach.
  * Include own Mocking Framework.
  * Very popular where Groovy is used.
  
* [cucumber]()
  * BDD Testing Framework.
  * Available for Java, JavaScript, and Ruby.
    * Very popular in Ruby community.
    * Gaining popularity in Java community.
  * Uses Gherkin syntax.
    * Natural English like syntax.
    * Describe the what, not the how.
    
* [Mockito.]()
  * Mocking Framework for testing.
    * Only does mocks.
    * Need to use with testing frameworks such as JUnit or TestNG.
  * Very popular for testing Spring applications.
  
* [Spring MVC Test.]()
  * Testing module found in the Spring Framework.
  * Very versatile for testing Spring MVC Controllers.
  * Provides mock Servlet environment.
  * Used in conjunction with a testing framework such as JUnit, TestNG, or Spock.
  
* [REST-assured]()
  * Java framework for testing RESTful web services.
  * Provide very powerful DSL for testing RESTful interfaces.
  * Can be used with Spring Mock MVC.
  * Test follow a BDD syntax.
  
* [Selenium.]()
  * Web Browser Automation.
  * Allows you to write functional tests against web applications.
  * Only Web Browser Automation.
    * Need to use a testing framework such as JUnit, TestNG, or Spock.
* [GEB]()
  * Groovy Browser Automation.
  * Uses Selenium under the cover.
  * Has JQuery-ish page element selector.
  * Need to be used with a Test Framework.
    * Very popular to use with Spock
* [TESTCONTAINERS]()
  * Allows you to launch Docker container from JUnit Tests.
  * Allow you to start databases, message brokers, etc for integration and functional tests.
  * Can be combined with Selenium for testing web applications.





## Assertion Frameworks.
* JUnit 5 will also work with popular assertion frameworks.
* The Java community has variety of assertions frameworks.
  * Some generalized.
  * Others specialized - ie JSON assertions.
* Popular options.
  * AssertJ.
  * Hamcrest.
  * Truth. 





## Help.

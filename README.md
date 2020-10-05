# Testing Main Information.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [JUnit Testing.](junit-testing.md)
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
* Unit Tests. Unit Testing.
* Integration Tests.
* Functional testing.
* End-to-End Tests.
* Performance Tests.
* Regression testing.
* A/B testing.





## Agile Testing Methods.
* TDD - Test Driven Development.
  * Write test first, code to 'fix' tests, refactor code to clean up, improve etc.
  
* BDD - Behavior Driven Development.
  * Very similar to TDD.
  * Describes the expected behavior of software.
    * Often expressed as: when/then; given/when/then.





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

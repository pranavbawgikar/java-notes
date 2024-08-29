## Page Object Model
There is a common misconception regarding the Page Object Model (POM) that it is a framework, but in reality it is a design pattern. Here, we maintain the locators or web elements in separate classes. POM is best applicable for the applications which contain multiple pages. Each of which have fields which can be uniquely referenced with respect to the page.

When any requirement is changed / deleted / added we need to update automation code as well to keep it up and running. If any element is changed in one web page which is used by 20 test class files in the automation framework, we need to update at 20 different places if PON design is not followed.

Page Object is a class that represents a web page and holds the web page elements and action methods. Page Factory is a way to initialize the web elements we want to interact with within the Page Object when you create an instance of it.

```java
LoginPage lp = new LoginPage(driver); // Creating object of Page class at test class level
PageFactory.initElements(driver, this); // Initializing the web elements in page class
```

If there are any new changes on the application page, the test cases needn't be changed, only the code within the Page Object Model needs to change. According to the POM, the test cases and element locators need to be kept separate, which ensures cleaner code and easier maintainability.

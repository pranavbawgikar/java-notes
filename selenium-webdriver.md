## Locators in Selenium WebDriver
Selenium locators helps to interact with the elements in the DOM. There are different types of locators in Selenium WebDriver like `id`, `name`, `tagName`, `className`, `xpath` and `cssSelector` to interact with respective web elements.
### `xpath`
`xpath` locates the WebElements using relative or absolute path. It helps to locate elements on the web page using XML expressions. The basic syntax for using `xpath` as a `cssSelector` is:
```
xpath: //tagName[@attribute='value']
```
Here, `tagName` signifies the tag in the DOM structure that you target for locating the desired WebElement. `attributes` are defined via the prefix `@` and their corresponding value. Thus, attributes like `name`, `id`, `className`, etc. can be used along with `tagName`.
### `id`
`id` is the fastest of all locators; however; it requires that the WebElement should contain the `id` attribute. The same applies to the `name` locator as well. This locator is the fastest approach since under-the-hood it calls `getElementById()` which browsers know how to optimize. `id` and `className` attributes make your testing code readable, easily understandble as well as explicit and robust.

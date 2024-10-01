## Appium
### Capabilities
Capabilities is the name given to the set of parameters used to start an Appium session. The information in the set is used to describe what sort of `capabilities` you want your session to have, for example, a certain mobile OS or a certain version of device. When the Appium session is started, the Appium client includes the set of capabilities defined as an object in JSON-formatted body of the request. Capabilities ar represented as key-value pairs; the values can be valid JSON type, including objects.

For example:
| Capability Name                 | Type                               | Description                                     |
|---------------------------------|------------------------------------|-------------------------------------------------|
| `browserName`                   | `string`                           | The name of the browser to lauch and automate.  |
| `browserVersion`                | `string`                           | The specific version of the browser.            |
| `platformName`                  | `string`                           | The type of platform hosting the browser.       |

# CSharp

Strictly typed
semi-colons to end commands
string interpolation is done with `$"Some text with an interpolated value here: {varName}"`
multiline strings are done with an `@"Text with multiple lines"`

No truthy or falsy values for checking values using if statements. Nothing is 'undefined'

Arrays are a fixed length at creation. Cannot push, splice, etc.
Preferred collections are lists `List<string> coolList = new List<string>();` or `List<string> coolList = []`
Lists can use add methods. `coolList.Add("Apple")`

Inheritance syntax is colon. `public class CatsController : ControllerBase {}`

Startup file is where we will create a service instance to hand out for Controllers to use
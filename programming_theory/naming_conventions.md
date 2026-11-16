## Cases
#### camelCase
#### PascalCase
#### snake_case
#### SCREAMING_SNAKE_CASE
#### kebab-case

### Hungarian notation
Prefixing the name with the intention/type. Typing a variable in the name
#### Apps Hungarian
prefixing with the intention/kind
`usName` - _unsafe string_ containing name; what to do with it? sanitize it into a safe string.
`nSize` - _count_ of size
`btnLogin` - the button used for login, not the login page or username
#### Systems Hungarian
prefixing with the type - incorrect applicaiton of the intended/proposed use of Hungarian notation
`strName` - string containing name; what is name, what to do with it? IDK
`bBusy` - bool

## Other common conventions
Each language documentation usually includes suggested naming convention, but in general:
- nouns for classes, verbs for functions, and names that show purpose for variables, attributes and arguments, ex.
    - class LoginPage
    - func click()
    - var fullName
- include descriptive verbs for booleans and functions that return booleans, like `isBusy` or `hasWeight()`
- start interface names with I and it should be an Adjective, ex. `IClickable`
- `_` prefix for private, ex. `_count` or `_process()` inside a class (sometimes also `__` aka, `__secret`)
- SCREAMING_SNAKE_CASE for constants and global variables, camelCase for variables and methods, PascalCase for classes and constructors
- avoid Systems Hungarian notation in dynamically typed languages since data types can change
- describe content rather than storage: `user_info` is better than `user_list`
- make distinctions: `moneyInDollars` is better than `money`
- put the distinguishing aspect first: `dollarMoney` is better than `moneyInDollars`

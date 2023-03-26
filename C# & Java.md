# C# & Java Coding Guideline

## General Guidelines

1. Be consistent and follow established conventions
   - Use the same conventions and patterns across your codebase.
   - Use established conventions and patterns for your language, framework, and libraries.
2. Write clean and readable code
   - Write code that is easy to read and understand.
   - Use meaningful and descriptive names for variables, functions, and classes.
3. Use comments to explain complex or important parts of your code
   - Use comments sparingly and only when necessary.
   - Write comments that are concise and to the point.
4. Use proper formatting and indentation
   - Use consistent formatting and indentation across your codebase.
   - Use tools like linters and code formatters to automate formatting and ensure consistency.

## Naming Conventions

### Variables

1. Use camelCase for variable names
   - Start with a lowercase letter and capitalize the first letter of each subsequent word.
   - For example: `firstName`, `totalPrice`, `isCompleted`.
2. Use meaningful and descriptive names for variables
   - Use names that accurately reflect the purpose and content of the variable.
   - For example: `customerName`, `orderDate`, `productDescription`.

### Functions and Methods

1. Use PascalCase for function and method names
   - Capitalize the first letter of each word in the name, including the first word.
   - For example: `CalculateTotalPrice`, `CreateCustomer`, `SubmitOrder`.
2. Use meaningful and descriptive names for functions and methods
   - Use names that accurately reflect the purpose and functionality of the function or method.
   - For example: `CalculateTotalPrice`, `CreateCustomer`, `SubmitOrder`.
3. Use consistent parameter naming
   - Use meaningful and descriptive names for function and method parameters.
   - Use the same naming conventions across related functions and methods.

### Classes

1. Use PascalCase for class names
   - Capitalize the first letter of each word in the name, including the first word.
   - For example: `Customer`, `Order`, `Product`.
2. Use singular nouns for class names
   - For example: `Customer`, not `Customers`.
3. Use meaningful and descriptive names for classes
   - Use names that accurately reflect the purpose and functionality of the class.
   - For example: `Customer`, `Order`, `Product`.

### Constants

1. Use all capital letters for constant names
   - Separate words with underscores.
   - For example: `MAX_WIDTH`, `MIN_PRICE`, `DEFAULT_COLOR`.
2. Use meaningful and descriptive names for constants
   - Use names that accurately reflect the purpose and content of the constant.
   - For example: `MAX_WIDTH`, `MIN_PRICE`, `DEFAULT_COLOR`.

## Code Style

### Indentation

1. Use 4 spaces for indentation
   - Use 4 spaces instead of tabs for indentation.
   - Use it consistently across your codebase.

### Line Length

1. Use a maximum line length of 80 or 120 characters
   - Choose one and use it consistently across your codebase.
   - Use line breaks to split long lines into multiple lines.

### Braces

1. Use the "K&R" style for braces
   - Place the opening brace on the same line as the statement or declaration.
   - Place the closing brace on a new line.

### Semicolons

1. Use semicolons to terminate statements and declarations
   - Use semicolons consistently across your codebase.
   - Do not rely on automatic semicolon insertion.

### Quotes

1. Use double quotes for string literals
   - For example: `"Hello, World!"`.
2. Use single quotes for character literals
   - For example: `'a'`.

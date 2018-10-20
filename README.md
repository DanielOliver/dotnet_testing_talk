# ASP.NET Core Testing Talk

"Business logic code" is the golden grail of code isolation: code that says what the application does without depending on other systems or any persistent storage, like a database.

Isolated business logic comes into effect when following the Dependency Inversion Principle, the fifth letter of the SOLID principles. The tenets of the Dependency Inversion Principle being that "High-level modules should not depend on low-level modules. Both should depend on abstractions." and "Abstractions should not depend on details. Details should depend on abstractions."

Using ASP.NET Core, I'm going to walk through both some theory and reasons to test, what to test, how to test, and why the Dependency Inversion Principle is so important to testable business logic code.

# Wholistic
Wholistic Visual Studio Extension - Code generation and IDE syntax extensions for Visual Studio.
- Extends Entity Framework
    - Generates Business Layer
    - Generates Web Service Layer
    - Generates Type Script
- Adds restricted Basic Types (code rigidity; shouldn't be able to add ids or confuse entity ids)
- Breaking changes are handled elegantly by maintaining versions
- Support for React, Bootstrap, and Angular code generation
- Contains an authentication and authorization convention that is extensible and transparent
    - Decorating attributes can be applied either restrictively or permissively
- Multiple project aware
    - Microservices implementation
        - Conductor and discovery support
- Creates complex web service graphs based on solution setup

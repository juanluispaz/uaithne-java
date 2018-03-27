# Uaithne Java
Agile backend architecture oriented to improve the productivity of the development team using Java.

## Goals
-   Easy application for backend development
-   Regardless of its complexity or size
-   Allow to grow without increasing complexity or reduce maintainability
-   Allow to modify the behaviour easily
-   Allow to improve the productivity of the team involved in the application development

## Philosophy
Get the backend resemble a **set of LEGO**, where there are **highly interchangeable pieces** that are **made up to achieve** the desired result.

## Design
- **English**: [Uaithne Java (EN).pdf](https://github.com/juanluispaz/uaithne-java/raw/master/Uaithne%20Java%20%28EN%29.pdf)
- **Spanish**: [Uaithne Java (ES).pdf](https://github.com/juanluispaz/uaithne-java/raw/master/Uaithne%20Java%20%28ES%29.pdf)

## Generator
Improving the productivity of the development team has been one of the great motivations behind the design of the architecture of Uaithne, and it alone represents a great improvement over the classical n-tier architecture. After implementing the new architecture there was still room to improve productivity, automatically generating code that is responsible for handling the verbosity required by Java, and above all, that generates the access code to the database with its respective SQL queries that handles most operations. Its usage is entirely optional.

**Code generator project**: [Uaithne generator Java](https://github.com/juanluispaz/uaithne-generator-java)
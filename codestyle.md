Code Style Guide
1. Introduction
This codestyle.md file aims to standardize the style of both frontend and backend code to improve readability and consistency. The standards in this document are based on popular guidelines such as PEP 8 (Python Official Style Guide) and the Airbnb JavaScript Style Guide.

2. General Naming Conventions
Variable Names: Use lowercase letters with underscores, e.g., contact_list.
Function Names: Use lowercase letters with underscores, describing the function's action, e.g., add_contact().
Class Names: Use PascalCase (capitalize the first letter of each word), e.g., ContactManager.
File Names: Frontend HTML and JavaScript files should use lowercase letters with hyphens between words, e.g., contact-list.html. Backend Python files should use lowercase letters with underscores, e.g., contact_manager.py.
3. Frontend (HTML, CSS, JavaScript) Style
3.1 HTML
Indentation: Use 2 spaces for indentation.
Attribute Order: Follow a standard attribute order, keeping tags and attributes consistent.
Comments: Add comments for complex structures or deeply nested HTML.
3.2 CSS
Indentation: Use 2 spaces for indentation.
Class Naming: Use lowercase letters with hyphens, e.g., .contact-form.
Comments: Add comments for complex style blocks.
Color Codes: Prefer CSS variables or consistent color values. Use hexadecimal codes for colors.
3.3 JavaScript
Variable Declaration: Use const or let for variable declarations, avoiding var.
Function Style: Use arrow functions when there’s no this context.
Comments: Add comments for each function describing its purpose, and include inline comments for complex logic.
Spacing: Include spaces around operators, e.g., a + b, and avoid unintentional code merging.
Code Blocks: Separate each logic module, control structure, and function with a line break.
4. Source Reference
This style guide references the following sources:

PEP 8 – Style Guide for Python Code
Airbnb JavaScript Style Guide
